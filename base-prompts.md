This agent will be utilizing the skill "match-cv-with-screening-rules" to process a candidate's CV and pass or reject that candidate based on how the skill judges this candidate. Once you have processed the CV via "match-cv-with-screening-rules" skill, enter your processing result in the file "candidates-screened.csv" which will be present inside the job opening folder you will be given.

Use the information you find from reading the CV & what information provided by the skill "match-cv-with-screening-rules" to fill-in this candidate's information as a single row in the CSV file "candidates-screened.csv". The columns you have to fill in "candidates-screened.csv" are:
- "name"  --> the full name of this candidate
- "email" --> the email address of this candidate
- "phone" --> the phone number of this candidate
- "experience" --> number of years of experience of this candidate
- "skills" --> pipe-separated " | " technical skills of this candidate
- "verdict" --> a value of either "pass" or "reject" by you
- "good-points" --> mention all the good points you identified while processing this CV due to which you would like to pass this candidate. Separate multiple points with a pipe " | " for human to review manually
- "bad-points" --> mention all the bad points you identified while processing this CV due to which you would like to reject this candidate. Separate multiple points with a pipe " | " for human to review manually
- "reasons-for-verdict" --> mention all the thoughts and decision-making points you considered while giving the verdict "pass" or "reject". Take knowledge from the skill "match-cv-with-screening-rules" to fill this column. Separate multiple points with a pipe " | " for human to review manually

After writing your findings in "candidates-screened.csv", now move this CV into either "cv-passed" or "cv-rejected" based on your verdict of this candidate inside the same job opening directory you are reading CV from.



given path to a job opening inside "openings/" folder. Each job opening will be contained inside a folder inside "openings/" folder of this project. 

Inside each job opening folder read the file "screening-rules.md" to understand how to properly screen a candidate to find them a fit or not fit for this particular job role. In screening-rules.md file expect that all the job-related specific screening rules are mentioned. Also load "common-screening-rules.md" as well from this project's root directory. This file will contain all the common screening rules regardless of what the job opening is. Now after reading rules from both "common-screening-rules.md" and "openings/--job-opening-folder--/screening-rules.md" start processing candidates for this job role. Each job opening folder has 3 sub-folders  "cv-to-screen", "cv-passed" and "cv-rejected". You have to open the CV given to you to run (CV will be present inside "cv-to-screen" folder), read the CV contents, then use the skill "match-cv-with-screening-rules" to process candidate's CV with job screening rules & common screening rules. 






help me create a claude code skill that will be used to evaluate a candidate against job opening screening rules for a particular job opening.

Candidate's information will be located in their CV file whose path will be given to you at run time.

You will also get the job opening folder path from inside "openings/" folder. The CV is also present inside a sub-folder "cv-to-screen" inside this job opening folder.

There are three levels of screening rules:
- common screening rules defined in "common-screening-rules.md" located in root directory of this project
- job opening related specific screening rules present in "screening-rules.md" file of this job opening folder
- your intelligence on how you would screen a CV to either pass or reject for further job processing

Merge all three levels of screening rules and then analyze this candidate via its CV. Extract and keep all the information present in the CV with you when you are processing the candidate. Don't rush to results, take time and process the candidate properly.