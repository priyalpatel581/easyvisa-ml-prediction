# Visa Approval Facilitation

## Project overview
This repository contains an end-to-end data science solution to help the Office of Foreign Labor Certification (OFLC) prioritize and shortlist employer visa applications that have a higher probability of approval. The goal is to speed up the review process by providing a machine learning classification model and insights about the features that most strongly influence case outcomes.

## Context
Business communities in the United States face high demand for skilled workers. The Immigration and Nationality Act (INA) permits foreign workers to come to the United States to work, while protecting U.S. workers by ensuring employers comply with statutory requirements. The OFLC administers applications for labor certifications and evaluates whether employers have demonstrated that there are insufficient U.S. workers available for the job at prevailing wages.

In FY 2016, OFLC processed 775,979 employer applications for 1,699,957 positions (a 9% increase over the previous year). Reviewing each case manually is time-consuming and becoming infeasible as application volumes grow.

## Objective
Create a machine learning classification model to:
- Facilitate visa approval processing by predicting whether a case will be certified or denied.
- Recommend which applicant profiles should be prioritized (certified) or flagged (denied) based on the factors that most affect case status.
- Provide interpretable insights to assist OFLC reviewers in decision support.

## Data description
The dataset contains attributes of applicants and employers. Key fields:

- case_id: ID of each visa application
- continent: Continent of the employee
- education_of_employee: Education level of the employee
- has_job_experience: Does the employee have job experience? Y = Yes; N = No
- requires_job_training: Does the employee require job training? Y = Yes; N = No
- no_of_employees: Number of employees in the employer's company
- yr_of_estab: Year the employer's company was established
- region_of_employment: Intended region of employment in the U.S.
- prevailing_wage: Average wage paid to similarly employed workers in the area of intended employment
- unit_of_wage: Unit for prevailing_wage (Hourly, Weekly, Monthly, Yearly)
- full_time_position: Is the position full-time? Y = Full Time; N = Part Time
- case_status: Target — whether the visa was certified or denied

