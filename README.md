# n8n-Job-Posting-Analyzer
This is the second part of my job posting analyzer pipeline. The first is built into the email sorter automation, which can be viewed here: https://github.com/Cainisable/n8n-Email-Sorter/tree/main

Workflow: [Job_Analyzer__Public_.json](https://github.com/user-attachments/files/19745588/Job_Analyzer__Public_.json)

![Job Analyzer](https://github.com/user-attachments/assets/104d722b-b4c0-4cfc-8bf7-def226911ab5)

This workflow performs a number of tasks:
- Performs scraping on job posting links to grab job details
- Checks the job details against my experience using a custom GPT agent
- Collects any job skills mentioned on the posting in order to collect keyword/skill trends for my main positions I'm interested in.
- Analyzes the job fit, and checks for any competencies missing from each posting if the GPT determines it's a pass.

