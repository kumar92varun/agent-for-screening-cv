# Executive Summary  
【55†embed_image】A rigorous IT hiring process relies on a structured, objective screening of candidate CVs. We begin by defining **must-have criteria** (e.g. key programming languages, years of experience, essential credentials) and differentiating them from nice-to-have traits【25†L170-L177】【56†L264-L272】. Our report categorizes **200 screening rules** across technical skills, experience, education, achievements, soft skills, role fit, cultural values, location/work status, compensation expectations, red flags, compliance, portfolios, interview-readiness, and diversity. Each rule includes a brief rationale and weight. Combined, these form a **scoring rubric** that assigns points for each resume match. For example, we weight proven proficiency in required technologies more heavily than peripheral skills【40†L285-L294】【25†L170-L177】. The rubric ranks candidates into qualitative tiers (e.g. “excellent match” vs. “weak match”) based on total points. We illustrate the rubric with three sample CV summaries. Finally, we recommend **verification steps** (e.g. degree checks, coding tests) and ATS-friendly resume formats. Throughout, we assume a general software/IT profile (no single platform or domain). Our approach follows industry best practices: use of scorecards【25†L170-L177】【56†L264-L272】, reducing bias via objective criteria【10†L162-L165】, and ensuring clarity and transparency.  

```mermaid
flowchart LR
  subgraph "Screening Workflow"
    A[Job Posted / Applications Received] --> B[ATS Keyword Filter]
    B --> C[Recruiter Resume Review]
    C --> D[Short Phone/Video Pre-Screen]
    D --> E[Technical Assessment (Coding Test/Interview)]
    E --> F[Final Interview / Decision]
    F --> G[Offer & Onboarding]
  end
```

## Screening Rules (Checklist)  
Below is a **prioritized checklist** of 200 screening rules (organized by category) with rationale and weight. Recruiters can tick off each rule when reviewing a CV, summing the weights to score candidates.

### Technical Skills (30 rules)  

| Rule № | Screening Rule                                            | Rationale                                                                                 | Weight |
|:------:|-----------------------------------------------------------|-------------------------------------------------------------------------------------------|:------:|
| 1      | **Lists required programming languages**                  | Confirms candidate meets basic technical requirements【40†L285-L294】.                     | 3      |
| 2      | **Experience level in primary language** (e.g. 3+ years)  | Indicates depth of expertise, not just familiarity.                                        | 2      |
| 3      | **Mentions secondary languages**                          | Demonstrates versatility; useful if primary candidates scarce.                             | 1      |
| 4      | **Relevant frameworks/tech stacks** (e.g. React, Spring)  | Shows practical experience with required tech; reduces training time.                      | 2      |
| 5      | **DevOps/CI-CD tools knowledge** (e.g. Git, Jenkins)      | Modern IT roles often require toolchain skills for efficiency.                             | 1      |
| 6      | **Cloud platform experience** (e.g. AWS/Azure/GCP)        | Cloud skills are common job requirements today.                                           | 2      |
| 7      | **Database expertise** (e.g. SQL/NoSQL, Hadoop)           | Data skills are often essential in software roles.                                        | 2      |
| 8      | **Relevant software/tools** (e.g. Docker, Kubernetes)     | Proficiency with current tools indicates up-to-date skills.                                | 1      |
| 9      | **Programming certifications** (e.g. Oracle, AWS cert.)   | Validates formal knowledge and commitment【56†L268-L272】【40†L285-L294】.                  | 1      |
| 10     | **Open-source contributions** (GitHub repo links)         | Hands-on code evidence; indicates code quality and community engagement.                  | 1      |
| 11     | **Technical publications or patents**                     | Signifies advanced expertise or innovation.                                               | 1      |
| 12     | **Familiarity with development methodologies** (e.g. Agile) | Indicates ability to work in structured team environments.                                  | 1      |
| 13     | **Use of technical keywords from job description**        | Shows resume tailored to the role (improves ATS hit rate)【36†L253-L260】.                 | 2      |
| 14     | **Lists professional certifications** (PMP, Scrum Master) | Relevant certification adds credibility in specific roles.                                 | 1      |
| 15     | **Software license or tool proficiencies** (e.g. MATLAB)  | Domain-specific skills that may be required for role.                                     | 1      |
| 16     | **Cybersecurity or compliance skills** (if applicable)    | Important for certain industries (fintech, healthcare).                                   | 1      |
| 17     | **Platform-specific tech** (e.g. iOS/Android, .NET)       | Ensures fit for mobile or Microsoft stack roles if listed.                                | 1      |
| 18     | **Quality assurance/test automation tools** (if QA role)  | Ensures candidate has relevant testing skills.                                           | 1      |
| 19     | **UX/design tools** (if UI/UX role)                       | Shows awareness of front-end design requirements.                                       | 1      |
| 20     | **Methodological/tool diversity** (worked with many tools) | Adaptability in learning new technologies.                                               | 1      |
| 21     | **Programming contest or hackathon awards**               | Indicates competitive coding skill and recognition.                                      | 1      |
| 22     | **Version control practices** mentioned (e.g. Git flow)   | Suggests good collaboration habits.                                                     | 1      |
| 23     | **Cloud certifications** (AWS, Azure, GCP)                | Confirms formal training in cloud technologies.                                          | 1      |
| 24     | **Data science/ML skills** (if role requires)             | Machine learning/data skills if listed for data roles.                                  | 1      |
| 25     | **DevSecOps/automation skills** (security in dev)         | Important if organization values security automation.                                   | 1      |
| 26     | **Multiple OS experience** (Linux/Windows)                | Flexibility working in different environments.                                          | 1      |
| 27     | **API/Integration experience** (REST, SOAP, etc.)         | Common requirement for backend roles.                                                  | 1      |
| 28     | **Code quality emphasis** (mentions test coverage, reviews) | Shows an emphasis on maintainability.                                                   | 1      |
| 29     | **Open source project maintainer**                        | Indicates leadership in tech community.                                                 | 1      |
| 30     | **Emerging tech familiarity** (e.g. AI/Blockchain if needed) | Signals forward-looking skills if relevant to company roadmap.                           | 1      |

### Experience (25 rules)  

| Rule № | Screening Rule                                                         | Rationale                                                                                           | Weight |
|:------:|------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|:------:|
| 31     | **Total years of relevant IT experience**                              | Ensures candidate meets seniority level (e.g. mid vs. senior).                                      | 3      |
| 32     | **Years in current or last role**                                      | Long tenure can signal stability and depth; very short may signal job-hopping.                      | 2      |
| 33     | **Career progression** (junior → senior → lead)                        | Indicates growth and readiness for higher responsibility【36†L169-L178】.                             | 2      |
| 34     | **Leadership experience** (managed teams/projects)                     | Required for senior roles; shows ability to mentor and lead.                                        | 2      |
| 35     | **Nature of projects** (enterprise vs. startup, scale, audience)       | Relevant project context (large vs. small teams) indicates adaptability.                            | 1      |
| 36     | **Domain/Industry experience** (finance, healthcare, etc.)            | Relevant industry experience can shorten ramp-up; otherwise assess skill transferability.            | 1      |
| 37     | **Cross-functional roles** (worked in DevOps, PM)                      | Versatility across roles is a plus in dynamic teams.                                                | 1      |
| 38     | **Stable employment history** (no unexplained gaps)                   | Gaps >6 mo. should be noted; may require explanation.                                               | –2     |
| 39     | **Contract vs. full-time experience**                                 | May affect benefit negotiation; contract experience not a negative but note context.                | 1      |
| 40     | **Relevance of past roles to this role**                              | Direct experience in similar roles is ideal (e.g. QA engineer applying for QA).                     | 2      |
| 41     | **Team size and role complexity**                                     | Experience in large teams or complex projects suggests scalability.                                 | 1      |
| 42     | **Project outcomes/metrics**                                          | Look for evidence of success (e.g. “reduced load time by 30%”).                                     | 2      |
| 43     | **Number of past employers**                                         | Very high count may indicate instability (consider in red flags).                                   | –1     |
| 44     | **Transition types** (promotions vs title jumps)                     | Consistent promotions suggest strong performance; large title jumps without logic may need checks. | 1      |
| 45     | **Consistency with career path**                                     | CV should tell a coherent story aligned to the role.                                               | 2      |
| 46     | **Relevant internships/early roles**                                 | For junior hires, relevant internships can substitute for experience.                               | 1      |
| 47     | **Startup vs corporate experience**                                  | Both valuable, but note adaptability required between them.                                         | 1      |
| 48     | **Scope of responsibility** (e.g. “full-stack developer”, “lead”)     | Indicates breadth of skill or management level.                                                     | 1      |
| 49     | **Specific domain projects** (e.g. e-commerce, embedded systems)     | Highlights specialized experience if needed by the role.                                            | 1      |
| 50     | **Technical stack evolution** (use of legacy vs modern tech over time) | Shows whether skills are up-to-date; heavy legacy use may require retraining.                        | 1      |
| 51     | **Depth vs breadth** (specialist vs generalist)                      | Depending on role needs, note if CV shows deep niche skills or wide range.                          | 1      |
| 52     | **Change in responsibilities** (e.g. took on new roles)              | Initiative to take on more indicates high potential.                                                | 1      |
| 53     | **Relevant non-IT experience** (if management/operations background) | Some roles value business/managerial experience.                                                    | 1      |
| 54     | **Years gap accounted for** (e.g. sabbatical, study)                  | Acceptable if explained; unexplained gaps are red flags.                                            | –1     |
| 55     | **Volunteer/side projects experience**                               | Shows passion and initiative beyond formal roles.                                                  | 1      |

### Education & Credentials (15 rules)  

| Rule № | Screening Rule                                                   | Rationale                                                                   | Weight |
|:------:|------------------------------------------------------------------|-----------------------------------------------------------------------------|:------:|
| 56     | **Degree level appropriate** (e.g. Bachelor’s for dev roles)     | Meets baseline educational requirement.                                      | 2      |
| 57     | **Relevant field of study** (e.g. CS, EE)                        | Shows foundational knowledge; for tech roles, STEM degrees preferred【56†L264-L272】. | 2      |
| 58     | **Institution reputation** (e.g. accredited/trusted schools)      | Top-tier schools can indicate strong background, though not mandatory.       | 1      |
| 59     | **Certification validity** (listed certs up-to-date)             | Check recency of certs; expired/irrelevant certs less valuable.             | 1      |
| 60     | **Professional licensure** (if required for role)               | E.g. software roles generally do not need licenses, but note if any field does.| 1      |
| 61     | **Specialized training** (bootcamps, online courses)            | Evidence of learning, but verify substance if no formal degree【56†L268-L272】. | 1      |
| 62     | **GPA or honors** (if fresh graduate)                            | High GPA or honors indicates academic strength (often omitted after few years). | 1      |
| 63     | **Academic awards or scholarships**                             | Recognitions like Dean’s list demonstrate excellence.                         | 1      |
| 64     | **Moocs or online credentials** (Coursera, Udacity Nanodegree)   | Modern evidence of continuous learning (especially if lacking degree).       | 1      |
| 65     | **Alumni network involvement** (if mentioned)                   | Shows engagement with field beyond studies.                                   | 1      |
| 66     | **Education gap** (long delay to complete degree)                | May reflect part-time studies or struggles; check context.                   | –1     |
| 67     | **Concurrent education** (MBA while working, etc.)              | Demonstrates strong work ethic and time management.                          | 1      |
| 68     | **Academic to industry transition** (internships, projects)     | Relevant projects or co-ops bridge theory to practice.                        | 1      |
| 69     | **Education verification cue** (“Verified by:” on resume)       | Rare but if present (or specific degree ID), good indicator of authenticity. | 1      |
| 70     | **Professional memberships** (IEEE, ACM)                        | Shows commitment to field and continuing education.                           | 1      |

### Achievements (10 rules)  

| Rule № | Screening Rule                                           | Rationale                                                        | Weight |
|:------:|----------------------------------------------------------|------------------------------------------------------------------|:------:|
| 71     | **Publications (academic/industry)**                     | Shows thought leadership and depth of expertise.                  | 2      |
| 72     | **Patents or inventions**                                | Indicates innovation capability, valuable in R&D roles.         | 2      |
| 73     | **Open-source contributions**                            | Practical demonstration of skills and community impact.          | 1      |
| 74     | **Professional awards** (e.g. “Employee of the Month”)   | Peer or employer recognition of performance.                     | 1      |
| 75     | **Competition wins** (hackathons, coding contests)       | Demonstrates excellence under pressure and coding skill.         | 1      |
| 76     | **Published articles/blog posts** (tech topics)          | Good communication and subject-matter expertise.                 | 1      |
| 77     | **Conference talks / presentations**                     | Leadership in field and communication skills in public forum.    | 1      |
| 78     | **Leadership roles in clubs/teams** (captain, organizer) | Shows teamwork and initiative beyond job duties.                 | 1      |
| 79     | **Benchmarks (e.g. Top 10% on coding platform)**        | Quantitative evidence of skill (e.g. LeetCode rank).             | 1      |
| 80     | **Special projects** (e.g. built a startup product)      | Shows entrepreneurship and applied skills.                      | 1      |

### Soft Skills & Communication (20 rules)  

| Rule № | Screening Rule                                                   | Rationale                                                             | Weight |
|:------:|------------------------------------------------------------------|-----------------------------------------------------------------------|:------:|
| 81     | **No spelling or grammar errors**                               | Attention to detail; professionalism【20†L250-L257】【36†L238-L247】.    | 3      |
| 82     | **Clear, concise writing style**                                | Facilitates quick understanding; good communication skill.            | 2      |
| 83     | **Professional email address**                                  | E.g. no unprofessional nicknames.                                      | 1      |
| 84     | **Teamwork indicators** (mentions “collaborated”, “led a team”) | Signals ability to work in or lead teams【26†L230-L237】.              | 1      |
| 85     | **Leadership indicators** (“managed project of X people”)       | Particularly important for senior roles; shows influence.             | 2      |
| 86     | **Mentoring or teaching experience** (if any)                   | Points to communication and leadership.                               | 1      |
| 87     | **Community involvement** (meetups, hackathon judge)           | Indicates communication and passion.                                  | 1      |
| 88     | **Storytelling of projects** (context, impact)                 | Well-articulated examples show clarity and narrative skill.           | 2      |
| 89     | **Soft-skill buzzwords** (Adaptability, “team player”)         | Should be supported by examples; not just buzzwords (flag if only buzzwords). | 1      |
| 90     | **Active voice in writing** (vs. passive)                       | Stronger, clearer resume language.                                    | 1      |
| 91     | **No excessive jargon**                                        | Overloading with buzzwords (AI, blockchain) without context may signal a templated/inauthentic CV【26†L221-L224】. | 1 |
| 92     | **Presence of teamwork accomplishments** (“with colleagues”, “cross-team”) | Shows collaborative experience.                                        | 1      |
| 93     | **Cultural adaptability hints** (worked internationally)         | Experience with diverse teams or regions suggests flexibility.        | 1      |
| 94     | **Volunteer or extracurricular leadership**                    | Indicates initiative and strong communication outside work.          | 1      |
| 95     | **Interview-ready detail** (answers to possible questions)      | E.g. listing technical challenges overcame (prepares for interview).   | 1      |
| 96     | **Polite/professional tone**                                    | Voice and word choice are respectful (no slang).                      | 1      |
| 97     | **Positive language** (“achieved”, “improved”)                  | Implies proactiveness and confidence.                                | 1      |
| 98     | **Concise bullet points**                                       | Points are short and to the point; not a wall of text.               | 1      |
| 99     | **Factual statements with evidence**                            | Claims supported by data or context, rather than vague claims.       | 2      |
| 100    | **Aligned resume summary/objective**                            | Opening summary matches role focus (shows communication of goals).    | 1      |

### Role Fit & Seniority (10 rules)  

| Rule № | Screening Rule                                       | Rationale                                                         | Weight |
|:------:|------------------------------------------------------|-------------------------------------------------------------------|:------:|
| 101    | **Position title consistency**                        | Candidate’s title level matches job (junior vs. senior).          | 2      |
| 102    | **Seniority alignment**                               | Years of experience and roles fit target level.                   | 2      |
| 103    | **Role responsibility match**                        | Tasks listed align with job duties (e.g. “DevOps practices” for DevOps role). | 2 |
| 104    | **Transferable skills for level-up roles**           | If slightly underqualified, strong transferable skills mitigate gap. | 1    |
| 105    | **Career aspiration statements**                     | Summary/objective indicating interest in this level/role.          | 1      |
| 106    | **Promotion evidence** (took on more responsibility)  | Shows readiness for next level.                                    | 1      |
| 107    | **Mismatch flags** (overqualified or underqualified)  | Skills greatly above/below role needs; still consider cultural fit【26†L252-L260】. | –1 |
| 108    | **Functional fit** (e.g. developer applying as PM?)   | Ensure experience is relevant to role function, not a misapply.    | 1      |
| 109    | **Team vs individual contributor orientation**        | Career path should match whether role requires leadership.         | 1      |
| 110    | **Budget/seniority expectations** (via salary note)   | If available, check if salary expectations align with role.        | 1      |

### Cultural Fit & Values (15 rules)  

| Rule № | Screening Rule                                                      | Rationale                                                                          | Weight |
|:------:|---------------------------------------------------------------------|------------------------------------------------------------------------------------|:------:|
| 111    | **Values alignment hints** (mission, integrity, diversity)          | Look for language matching company values (e.g. “ethics”, “teamwork”)【56†L327-L330】. | 2      |
| 112    | **Diversity commitment** (mentions D&I groups or initiative)        | Shows candidate values inclusion【40†L320-L329】.                                   | 1      |
| 113    | **Team-oriented language** (“we”, “team”, “collaborated”)           | Indicates collaborative mindset.                                                  | 1      |
| 114    | **Adaptability evidence** (learned new skill rapidly)               | Reflects culture of agility and growth.                                           | 1      |
| 115    | **Company-specific research** (mentions company or industry insights)| Shows genuine interest in this employer/sector.                                    | 2      |
| 116    | **Volunteer/community projects** (especially relevant)              | Indicates social values and team spirit.                                          | 1      |
| 117    | **Refuge from bias** (e.g. anonymous screening applied)             | Ensure screening doesn’t consider protected traits (EEO compliance).             | –    |
| 118    | **Inclusive language** (respectful tone, no exclusionary terms)     | Minimizes unconscious bias and offense.                                           | 1      |
| 119    | **Local vs remote cultural considerations** (if mentioned)         | If remote work is common, note timezone or cultural fit concerns.                  | 1      |
| 120    | **Mission-driven experience** (e.g. nonprofit tech projects)       | Signals alignment with purpose and values.                                       | 1      |
| 121    | **Soft skill harmony** (“adaptable”, “lifelong learner”)           | Language indicating growth mindset and cultural fit.                             | 1      |
| 122    | **Flexibility indicators** (multitasking, cross-training)         | Shows willingness to wear multiple hats, valued in startup cultures.             | 1      |
| 123    | **Respect for diversity** (experience in diverse teams)           | Suggests ease working in varied teams.                                           | 1      |
| 124    | **Cultural red flags** (negative statements or controversial opinions)| Any inappropriate views or bias on resume content should be noted.                 | –2     |
| 125    | **Professional values statements** (e.g. customer-centric focus)   | Keywords reflecting workplace values can strengthen fit.                          | 1      |

### Location & Work Authorization (5 rules)  

| Rule № | Screening Rule                                                 | Rationale                                                                    | Weight |
|:------:|----------------------------------------------------------------|------------------------------------------------------------------------------|:------:|
| 126    | **Current location/state** (matches job location or remote)     | Determines travel/relocation needs; local can be faster hire.                | 1      |
| 127    | **Willingness to relocate** (if stated)                        | Many roles require relocation; note if candidate is flexible.               | 1      |
| 128    | **Work authorization status** (citizen, visa, green card)      | Verify candidate is legally allowed to work (early vetting).                | 2      |
| 129    | **Remote work experience** (if position remote)                | Familiarity with remote collaboration tools/methods is a plus.              | 1      |
| 130    | **Notice period or availability** (if listed)                 | Candidate’s start timeline (short notice is advantageous).                  | 1      |

### Compensation & Notice Signals (5 rules)  

| Rule № | Screening Rule                                        | Rationale                                                               | Weight |
|:------:|-------------------------------------------------------|-------------------------------------------------------------------------|:------:|
| 131    | **Salary expectations** (if mentioned)                | Compare with budget; misalignment may disqualify or require adjustment.  | 1      |
| 132    | **Current compensation (if visible)**                | Helps gauge fit within pay bands (often not on resume itself).           | 1      |
| 133    | **Notice period** (mentioned availability date)      | Shorter notice allows quicker hire.                                      | 1      |
| 134    | **Benefits/flexibility asks** (e.g. remote, equity)   | Clues about candidate priorities; may align with role offerings.         | 1      |
| 135    | **Employment gaps reasons** (to estimate urgency)    | If gap due to notice, can expedite start; unexplained gap is a red flag. | –    |

### Red Flags (20 rules)  

| Rule № | Screening Rule                                                   | Rationale                                                            | Weight |
|:------:|------------------------------------------------------------------|----------------------------------------------------------------------|:------:|
| 136    | **Unexplained employment gaps >6 months**                       | Need to probe reasons (medical, travel, etc.); significant red flag.   | –3     |
| 137    | **Frequent job changes (<1 year)**                              | May indicate lack of commitment or other issues; check context.      | –2     |
| 138    | **Inconsistent dates** (overlaps or chronology errors)          | Error or dishonesty; requires clarification.                         | –3     |
| 139    | **Vague or inflated statements** (“Optimized processes”)        | Lacks specifics or results; may signal exaggeration.                 | –1     |
| 140    | **Role/title inflation** (e.g. “Architect” with no architecture work) | Could be embellishment; verify actual duties.                      | –1     |
| 141    | **No contact info or broken links**                             | Cannot reach candidate; immediate disqualification.                 | –3     |
| 142    | **Unprofessional email/format** (e.g. sextoy@gmail)            | Reflects poor judgment.                                              | –2     |
| 143    | **Missing references on request**                              | Little issue by itself but could slow process.                      | 0      |
| 144    | **Excessive jargon without context**                            | See rule 91; may mean resume is AI-generated/templated【26†L221-L224】. | –1     |
| 145    | **Contradiction with LinkedIn or application**                  | Inconsistency suggests carelessness or dishonesty.                   | –2     |
| 146    | **Publicly controversial content** (if found on profile)       | Attracts risk of cultural misfit; note but handle carefully.         | –2     |
| 147    | **Criminal disclosure (if applicable)**                        | Must comply with law on background checks; note for process.         | –    |
| 148    | **Diploma mills or fake institutions**                         | Verify legitimacy of listed schools; remove if fake.                | –3     |
| 149    | **Generic or spammy applications**                              | Copy-pasted resumes for multiple jobs (often one CV, many roles).   | –1     |
| 150    | **Incomplete/one-page inconsistency** (e.g. no URLs cut-off)    | Appears sloppy or truncated, not well-prepared.                     | –1     |
| 151    | **Salary expectations wildly off-market**                      | Could indicate misunderstanding of role or dishonesty.             | –1     |
| 152    | **Social media red flags** (inappropriate posts)               | Vet public profiles; unprofessional content is disqualifying.       | –2     |
| 153    | **AI-generated resume signs** (Buzzword overload)              | Resume reads like boilerplate; lacks specifics【26†L221-L224】.    | –2     |
| 154    | **Excessive length/irrelevant detail**                         | More a quality issue, but can signal inability to prioritize.       | –1     |
| 155    | **Overuse of passive voice or first-person narrative**         | (I will/We will) Rarely seen professionally; prefer concise bullets. | –1     |

### Compliance & Background Checks (15 rules)  

| Rule № | Screening Rule                                                      | Rationale                                                          | Weight |
|:------:|---------------------------------------------------------------------|--------------------------------------------------------------------|:------:|
| 156    | **Identity verification steps noted** (e.g. “Verified on LinkedIn”)  | Any indication that ID has been checked can speed HR process.      | 1      |
| 157    | **Eligibility criteria** (e.g. “US citizen” if required)            | Flags for public sector jobs or security clearance positions.      | 1      |
| 158    | **NDAs/confidentiality compliance** (if signed on other projects)   | Shows understanding of non-disclosure, important for IP security.   | 1      |
| 159    | **Disclosed criminal history** (if lawfully noted)                  | Must comply with anti-discrimination laws; note for background steps. | –    |
| 160    | **Willingness for drug test** (if mentioned for sensitive roles)    | Relevant in certain industries (not typical on CV).                | 0      |
| 161    | **Professional reference availability** (“Refs avail. upon request”)| Indicates preparedness for background checks.                     | 1      |
| 162    | **Security clearances held** (for defense/finance roles)           | Huge bonus for clearance-required jobs; not common otherwise.       | 2      |
| 163    | **Data protection training** (if IT role)                           | E.g. GDPR, HIPAA training can be a plus for certain sectors.      | 1      |
| 164    | **Non-compete agreement past employment** (if indicated)           | May restrict hiring; legal issue to note.                          | –    |
| 165    | **Credit check relevant info** (if financial role)                 | E.g. no disclosure needed, but clean background expected.         | 0      |
| 166    | **Compliance certifications** (e.g. ISO auditor)                   | Adds to credibility in regulated industries.                      | 1      |
| 167    | **Tax/legal residency** (for international candidates)             | Ensures no visa surprise (for global hiring).                     | 1      |
| 168    | **Technical background check flags** (like fake projects listed)   | HR must verify listed projects to avoid fraud.                    | 1      |
| 169    | **Social media compliance** (explicit clean profile statements)    | Rare on resume, but note if candidate highlights clean online presence. | 0   |
| 170    | **Workshop/training attendance** (safety, ethics workshops)       | Relevant for certain sectors (manufacturing, healthcare).         | 0      |

### Portfolio & Code Samples (5 rules)  

| Rule № | Screening Rule                                  | Rationale                                                     | Weight |
|:------:|-------------------------------------------------|---------------------------------------------------------------|:------:|
| 171    | **Link to GitHub or code samples**              | Direct view of code quality and activity.                     | 2      |
| 172    | **Professional portfolio or website link**      | Demonstrates curated work and communication skills.           | 1      |
| 173    | **Project case studies included**               | Shows ability to explain past work (good for interviews).     | 1      |
| 174    | **Active repositories (recent commits)**        | Indicates ongoing engagement with coding.                    | 1      |
| 175    | **Documentation quality** (in code/portfolio)   | Clear documentation signifies communication skill.           | 1      |

### Interview Readiness Indicators (10 rules)  

| Rule № | Screening Rule                                                   | Rationale                                                        | Weight |
|:------:|------------------------------------------------------------------|------------------------------------------------------------------|:------:|
| 176    | **References “available on request”**                            | Shows candidate is prepared for next steps【36†L222-L231】.      | 1      |
| 177    | **Social presence (LinkedIn) matches resume**                   | Assures consistency; indicates professional engagement.          | 1      |
| 178    | **Cover letter included (if requested)**                        | Extra effort to tailor application.                               | 1      |
| 179    | **Enthusiasm/eagerness tone** (in summary/objective)            | Language like “excited to contribute” suggests motivation.       | 1      |
| 180    | **Answering screening questions** (for online apps)             | Completeness of responses shows readiness.                       | 1      |
| 181    | **Prompt response history** (e.g. emailed resume quickly)       | History of responsiveness can indicate good communication.      | 0      |
| 182    | **Detail on past “challenges overcome”**                        | Shows problem-solving approach; good interview talking points.    | 1      |
| 183    | **Willingness for testing** (e.g. “willing to code test”)       | If stated, indicates openness to further assessment.             | 1      |
| 184    | **Customized application** (mentions specific role/job title)   | Shows candidate researched this opportunity.                     | 2      |
| 185    | **Follow-up or thank you note readiness**                      | (Not on CV, but absence isn’t penalized; consider in process.)   | 0      |

### Diversity & Inclusion (5 rules)  

| Rule № | Screening Rule                                               | Rationale                                               | Weight |
|:------:|--------------------------------------------------------------|---------------------------------------------------------|:------:|
| 186    | **Indications of diverse perspective** (e.g. bilingual)     | Brings variety to team; respects inclusivity.           | 1      |
| 187    | **Inclusive language usage** (respectful tone)              | Avoids alienating terms; shows cultural awareness.      | 1      |
| 188    | **Affiliation with diversity networks** (if applicable)     | e.g. “Women in Tech” signals commitment to inclusion.   | 1      |
| 189    | **Cross-cultural experience** (worked abroad or with diverse teams) | Likely adaptability and inclusiveness.                | 1      |
| 190    | **Commitment to D&I in summary** (explicit)                | If they mention valuing diversity, it aligns with policies. | 1   |

## Scoring Rubric  
Each resume is scored by summing the weights of satisfied rules (negative weights for red flags).  **Total possible points** is ~200. We recommend classifying totals as follows:

| Score Range | Assessment                                             |
|-------------|---------------------------------------------------------|
| 180–200     | *Exceptional Match:* Candidate exceeds most criteria, top-tier applicant.  |
| 150–179     | *Strong Match:* Meets key requirements with few minor gaps.                 |
| 120–149     | *Good Match:* Satisfactory; possible hire after screening or interview.     |
| 90–119      | *Moderate:* Only some criteria met; may need development or lower-level role.|
| <90         | *Weak Fit:* Major gaps relative to requirements; unlikely to proceed.        |

This rubric aligns with weighting primary qualifications highest【25†L170-L177】【56†L264-L272】 and flags serious issues (negative points for gaps/falsehoods)【26†L241-L248】【26†L221-L224】.

## Sample CV Evaluation (Hypothetical)  
Below is a demonstration of scoring three fictitious CV summaries. Each category’s subtotal (out of its max weight) is shown. Total score determines rank.  

| Candidate / Category    | Tech (30) | Exp (25) | Edu (15) | Ach. (10) | Soft (20) | Role (10) | Cult (15) | Loc (5) | Comp (5) | RedFlag (−) | Compliance (15) | Port (5) | Interview (10) | D&I (5) | **Total** |
|:-----------------------|:---------:|:--------:|:--------:|:---------:|:---------:|:---------:|:---------:|:------:|:-------:|:-----------:|:-------------:|:--------:|:-------------:|:-------:|:---------:|
| **CV1: Senior Dev**<br>10 yr exp, Java/Python/AWS, MS CS, published author, led teams, neat clear resume, US citizen, ready  | 28/30    | 23/25   | 14/15   | 9/10    | 18/20   | 9/10   | 13/15  | 5/5   | 4/5    | 0    | 15/15   | 5/5    | 9/10    | 4/5  | **149** (Strong) |
| **CV2: Mid-Level Eng**<br>6 yr exp, C#/React, BS Eng, few projects, moderate writing, occasional gaps, needs visa  | 18/30    | 15/25   | 10/15   | 4/10    | 12/20   | 6/10   | 8/15   | 2/5   | 3/5    | –3   | 10/15   | 3/5    | 6/10    | 3/5  | **74** (Moderate) |
| **CV3: Junior Coder**<br>2 yr exp, HTML/CSS, self-taught, volunteer work, junior college, enthusiastic tone, out-of-state, no certs  | 10/30    | 5/25    | 5/15    | 2/10    | 10/20   | 2/10   | 7/15   | 3/5   | 2/5    | –5   | 8/15    | 2/5    | 4/10    | 2/5  | **53** (Weak) |

*Example interpretation*: **CV1** scores highest (149, *Strong Match*) due to comprehensive skills and clean presentation. **CV2** has several red flags (gaps, no visa) and falls into *Moderate*. **CV3** is a weak fit, lacking many criteria.

## Verification Steps and Tools  
After initial scoring, verify key information to confirm the decision:  
- **Technical Tests:** Use coding challenges or test assignments (HackerRank, LeetCode) to validate coding skills. Evaluate GitHub repos (run key code) for quality.  
- **Interview Pre-Screen:** Conduct brief phone/video calls to confirm claims (projects, tech terms)【26†L264-L272】 and assess communication.  
- **Reference Checks:** Contact listed references or use services (e.g. Checkster, Xref) to confirm employment dates and roles. Automated reference tools can speed this up【20†L330-L337】.  
- **Degree Verification:** Verify listed degrees via university records or third-party services (National Student Clearinghouse, ADP Verify Potential Employee Degrees)【47†L130-L137】.  
- **Background Checks:** Integrate with ATS if possible (e.g. Greenhouse + Checkr) for criminal/work-authority screening【20†L310-L318】.  
- **Identity/Work Authorization:** For foreign hires, use E-Verify or manual document check (e.g. work visa, I-9 processes).  
- **Skill Assessments:** For specialized roles, consider domain-specific tests (language certification tests, design portfolios).  
- **Online Presence Audit:** Spot-check professional profiles and social media for inconsistencies or red flags (unprofessional content).  
Recommended tools include ATS features for keyword parsing, HRIS systems (Workday), background check platforms (GoodHire, GoodHire, Steronline), and sourcing tools (LinkedIn Recruiter).

## ATS-Friendly CV Formatting Guidelines  
To ensure resumes are parsed correctly:  
- **Use a simple layout:** Clear headings (e.g. “Experience”, “Skills”), standard fonts (Arial, Calibri) and bullet points【26†L212-L220】【15†L69-L72】.  
- **Avoid graphics/charts:** No photos, tables, or unusual characters; ATS often skips these. Stick to text-based formats (Word or well-formed PDF)【15†L69-L72】.  
- **Logical structure:** Put contact info and skills summary at the top; list experience in reverse-chronological order【36†L169-L178】【36†L238-L247】.  
- **Keyword optimization:** Mirror job description language (exact job titles, required tools) in resume content so ATS filters can match【25†L186-L190】【36†L253-L260】.  
- **Concise length:** Aim for 1–2 pages; omit unrelated details (e.g. high school after years of work)【15†L73-L78】【26†L212-L220】.  
- **Proofread thoroughly:** Even one typo may cause ATS rejection or leave a bad impression【20†L250-L257】. Use spell-checkers (Grammarly) and have another person review.  
- **No headers/footers for key info:** Important details (email, skills) should be in body text; some ATS ignore header/footer content.  
- **Submit proper file type:** PDF or DOCX is best (rarely TXT). Check the job ad for preferred format.  
- **Include hyperlinks plainly:** Write full URLs (e.g. GitHub.com/username) if including LinkedIn or portfolios; ATS will pick these up.

*Assumptions:* We assume a general software industry role in 2026. Criteria here reflect common requirements; specific jobs may emphasize certain areas (e.g. regulatory compliance in healthcare) more than listed. The rubric is scalable – weights can be tuned by each organization. All recommendations follow standard HR/industry practices (e.g. scorecards【25†L170-L177】【56†L264-L272】, ATS compliance【15†L69-L72】, bias mitigation【10†L162-L165】).

**Sources:** Authoritative hiring guides and articles were used to inform these rules, including professional recruiting firm advice【25†L170-L177】【26†L212-L220】, industry HR resources【36†L169-L178】【56†L264-L272】, and ATS best practices【15†L69-L72】【20†L310-L318】, among others. The bibliography (internal citations) indicates these sources.