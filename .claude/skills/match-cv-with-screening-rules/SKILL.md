---
name: match-cv-with-screening-rules
description: >
  Use this skill whenever asked to screen, evaluate, or review a candidate's CV or resume against a job opening. Trigger when the user says things like "screen this candidate", "evaluate this CV", "should we proceed with this applicant", "check this resume against the job", or provides a job opening folder path and asks for a screening decision. Also trigger when the user mentions "openings/" folder, "cv-to-screen", "screening-rules", or asks Claude to pass/reject a candidate. Use this skill even if the user only gives a folder path — it will guide the full screening workflow.
---

# HR CV Screener

A skill for thorough, structured evaluation of a candidate's CV against layered screening rules for a specific job opening.

---

## Overview

This skill merges **three layers** of screening intelligence and produces a detailed, well-reasoned screening decision with full justification.

---

## Inputs

At runtime, expect to receive one or both of:
- **`[OPENING_FOLDER]`** — path to the job opening folder inside `openings/`, e.g. `openings/senior-backend-engineer/`
- **`[CV_PATH]`** — explicit path to the candidate's CV file (if not, derive it as `[OPENING_FOLDER]/cv-to-screen/<filename>`)

If neither is provided, ask the user to supply the job opening folder path before proceeding.

---

## Step-by-Step Workflow

### Step 1 — Load All Screening Rules

Read and internalize rules from **all three layers**:

**Layer 1 — Common Rules** (project-wide):
```
common-screening-rules.md   (root of project)
```

**Layer 2 — Opening-Specific Rules**:
```
[OPENING_FOLDER]/screening-rules.md
```

**Layer 3 — Your Own Intelligence**:
Apply general hiring best practices as a senior technical recruiter / engineering manager. This includes:
- Assessing trajectory and growth pattern in career history
- Detecting red flags: unexplained gaps, job hopping without apparent reason, vague role descriptions, inflated titles
- Noticing green flags: promotions, quantified impact, diverse project exposure, leadership signals
- Checking for realistic skill-experience alignment (e.g., 2 years exp claiming 5+ technologies to expert level)
- Evaluating communication quality from how the CV is written (clarity, precision, professionalism)

**After loading**, create a **merged rule set** in your working memory. If any Layer 2 rule conflicts with Layer 1, Layer 2 (job-specific) takes precedence unless Layer 1 explicitly marks a rule as non-overridable.

---

### Step 2 — Load and Extract the CV

Locate the CV file:
- If `[CV_PATH]` is given, use it directly.
- Otherwise, list files in `[OPENING_FOLDER]/cv-to-screen/` and pick the CV file (PDF, DOCX, or TXT).

**Extract ALL of the following** — do not skip sections even if they seem irrelevant:

| Category | What to Extract |
|---|---|
| **Identity** | Name, contact info, location, LinkedIn/GitHub/portfolio URLs |
| **Summary / Objective** | Verbatim or close paraphrase of any profile summary |
| **Work Experience** | For each role: company, title, duration (start–end), responsibilities, achievements, technologies used |
| **Education** | Degrees, institutions, graduation years, relevant coursework or distinctions |
| **Skills** | All listed skills — technical, tools, languages, frameworks, soft skills |
| **Certifications** | Name, issuing body, year |
| **Projects** | Personal, freelance, or open-source — name, description, tech stack, outcome |
| **Publications / Talks** | If any |
| **Gaps / Anomalies** | Any unexplained gaps, short stints, overlapping dates |
| **Overall Presentation** | Quality of writing, structure, clarity |

Do not compress or skip any section. You will reference this extracted data throughout the evaluation.

---

### Step 3 — Deep Evaluation Against Merged Rules

Go through the merged rule set **rule by rule**. For each rule:
1. State the rule
2. Identify the relevant CV evidence
3. Give a verdict: ✅ Passes / ❌ Fails / ⚠️ Partial / 🔍 Cannot Determine

Take your time. Do not rush to a final verdict. Think carefully about edge cases — e.g., a rule says "5 years experience" and the candidate has 4.5 years: flag it as ⚠️ with context.

---

### Step 4 — Compose the Screening Report

Produce a structured report in the following format:

---

```
## CV Screening Report

**Candidate:** [Name]
**Position:** [Job Title from opening folder or screening-rules.md]
**Screened On:** [Today's date]
**Screened By:** Claude (AI Screener)

---

### Candidate Summary
[3–5 sentence snapshot: who this person is, their career arc, their core strengths]

---

### Extracted Profile

**Total Experience:** X years
**Current/Last Role:** [Title] at [Company]
**Education:** [Degree, Institution, Year]
**Key Skills:** [comma-separated top skills]
**Notable Achievements:** [1–3 bullet points]
**Potential Red Flags:** [if none, say "None identified"]

---

### Rule-by-Rule Evaluation

#### Common Rules
| # | Rule | Evidence | Verdict |
|---|---|---|---|
| 1 | [rule text] | [evidence from CV] | ✅ / ❌ / ⚠️ / 🔍 |
| ... | | | |

#### Job-Specific Rules
| # | Rule | Evidence | Verdict |
|---|---|---|---|
| 1 | [rule text] | [evidence from CV] | ✅ / ❌ / ⚠️ / 🔍 |
| ... | | | |

#### Intelligence-Based Assessment
[Paragraph covering trajectory, red flags, green flags, realism of claims, and CV quality — written in prose, not just a table]

---

### Strengths
- [Bullet 1]
- [Bullet 2]
- [Bullet 3]

### Concerns / Gaps
- [Bullet 1]
- [Bullet 2]

---

### Final Verdict

**Decision: [PASS ✅ / REJECT ❌ / HOLD ⚠️]**

**Confidence:** [High / Medium / Low]

**Reasoning:**
[2–4 sentence explanation of the decision, citing the most decisive factors]

**Recommended Next Step:**
[e.g., "Schedule a technical phone screen", "Request clarification on employment gap", "Reject — does not meet minimum experience requirement"]
```

---

## Edge Cases

- **No CV found in cv-to-screen/**: Tell the user the folder is empty and ask them to place the CV there.
- **CV is a scanned image PDF**: Note this limitation, extract what you can, flag unreliable extraction.
- **Screening rules file is missing**: Proceed with just common rules + your intelligence; note in the report that job-specific rules were absent.
- **Common rules file is missing**: Proceed with job-specific rules + your intelligence; note in the report.
- **Conflicting rules**: Apply the more specific (Layer 2) rule, note the conflict in the report.
- **Ambiguous candidate data** (e.g., role title doesn't match responsibilities): Flag it and reason about what's more likely true.

---

## Tone & Principles

- Be **fair and specific** — every verdict must cite actual CV evidence.
- Be **decisive** — don't hedge everything. Make a call.
- Be **thorough over fast** — this is a hiring decision. Take time.
- Avoid **bias** — assess skills, experience, and evidence only. Do not comment on name, photo, nationality, gender, or age.
- **HOLD** is a valid verdict when a candidate is borderline or when key information is missing that could swing the decision either way.
