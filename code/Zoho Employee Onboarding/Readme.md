# Zoho Employee Onboarding Automation
This package includes the following files required to set up the Employee Onboarding Automation:
- Data_table_1, Data_table_2: Contains required data tables.
- common_common: Contains common utility recipes, shared data models, and notification components used across all onboarding phases.
- job_requisition_job-requisition: Contains the recipes and components for managing and ingesting job requisitions.
- job_requisition_status_job-requisition-status: Contains workflows to track, update, and synchronize job requisition statuses across systems.
- interview_schedule_interview-schedule: Contains scheduling modules to coordinate interview slots and candidate communications.
- interviewer_feedback_interviewer-feedback-form: Contains components for capturing and processing interviewer evaluations and candidate feedback.
- offer-letter_offer-letter: Contains automated document generation and routing recipes for job offer letters.
- onboarding_onboarding: Contains the core candidate onboarding workflows, enterprise app provisioning, and final record creation.
Import Order
All files must be imported into the same project in the exact order below to complete the setup:
1. Import Data_table_1 first into the project.
2. Import Data_table_2 into the same project.
3. Import common_common into the same project.
4. Import job_requisition_job-requisition into the same project.
5. Import job_requisition_status_job-requisition-status into the same project.
6. Import interview_schedule_interview-schedule into the same project.
7. Import interviewer_feedback_interviewer-feedback-form into the same project.
8. Import offer-letter_offer-letter into the same project.
9. Import onboarding_onboarding into the same project.

Once all files have been imported into the same project in this sequence, configure the relevant connection parameters to complete the Employee Onboarding Automation setup.