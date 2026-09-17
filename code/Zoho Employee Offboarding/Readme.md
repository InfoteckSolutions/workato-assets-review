# Zoho Employee Offboarding Automation
This package includes the following files required to set up the Employee Offboarding Automation:
- resignation_resignation: Contains the recipes and components required for employee resignation submission and approval workflows.
- common_common: Contains common utility recipes, shared data models, and core notification components used across the entire offboarding lifecycle.
- exit-interview_exit-interview 1: Contains the modules for scheduling, collecting, and archiving exit interview feedback.
- noc_noc: Contains the workflows for cross-departmental No Objection Certificate (NOC) routing and approvals.
- check_list_check_list 1: Contains the automated checklists for asset collection, access revocation, and IT/HR clearance tasks.
- letter_relieving-letter: Contains the automated document generation recipes for Relieving and Experience letters.
- final_settlement_final_settlement: Contains the workflows for processing financial clearances, payroll updates, and final settlement computations.
- offboarding-zoho-_offboarding-zoho: Contains the Zoho API connection and base integration modules to retrieve and validate employee information.
## Import Order
All files must be imported in the exact order below to complete the setup:
1. Import resignation_resignation and common_common first into the project.
2. Import exit-interview_exit-interview 1 into the same project.
3. Import noc_noc into the same project.
4. Import check_list_check_list 1 into the same project.
5. Import letter_relieving-letter into the same project.
6. Import final_settlement_final_settlement into the same project.
7. Import offboarding-zoho-_offboarding-zoho into the same project.
Once all files have been imported into the same project in this sequence, the Employee Offboarding Automation setup will be complete.
 