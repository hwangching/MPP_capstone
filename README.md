# Microsoft Professional Program

Predicting Mortgage Approvals From Government Data


https://datasciencecapstone.org/competitions/14/mortgage-approvals-from-government-data/data/


#### Best score: 0.7257
#### Final rank: 28 (total 558 competitors)


### About the Data
The goal is to predict whether a mortgage application was accepted (meaning the loan was originated) or denied according to the given dataset, which is adapted from the Federal Financial Institutions Examination Council's (FFIEC).

### Features
There are 21 variables in this dataset. Each row in the dataset represents a HMDA-reported loan application, and the dataset we are working with covers one particular year.

 - msa_md (categorical) - A categorical with no ordering indicating Metropolitan Statistical Area/Metropolitan Division 
 - state_code (categorical) - A categorical with no ordering indicating the U.S.
 - county_code (categorical) - A categorical with no ordering indicating the county 
 - lender (categorical) - A categorical with no ordering indicating which of the lenders was the authority in approving or denying this loan
 - loan_amount (int) - Size of the requested loan in thousands of dollars
 - loan_type (categorical) - Indicates whether the loan granted, applied for, or purchased was conventional, government-guaranteed, or government-insured
 - property_type (categorical) - Indicates whether the loan or application was for a one-to-four-family dwelling (other than manufactured housing), manufactured housing, or multifamily dwelling
 - loan_purpose (categorical) - Indicates whether the purpose of the loan or application was for home purchase, home improvement, or refinancing
 - occupancy (categorical) - Indicates whether the property to which the loan application relates will be the owner's principal dwelling
 - preapproval (categorical) - Indicate whether the application or loan involved a request for a pre-approval of a home purchase loan
 - applicant_income (int) - In thousands of dollars
 - applicant_ethnicity (categorical) - Ethnicity of the applicant
 - applicant_race (categorical) - Race of the applicant
 - applicant_sex (categorical) - Sex of the applicant
 - co_applicant (bool) - Indicates whether there is a co-applicant (often a spouse) or not
 - population - Total population in tract
 - minority_population_pct - Percentage of minority population to total population for tract
 - ffiecmedian_family_income - FFIEC Median family income in dollars for the MSA/MD in which the tract is located (adjusted annually by FFIEC)
 - tract_to_msa_md_income_pct - % of tract median family income compared to MSA/MD median family income
 - number_of_owner-occupied_units - Number of dwellings, including individual condominiums, that are lived in by the owner
 - number_of_1_to_4_family_units - Dwellings that are built to house fewer than 5 families
 - row_id - A unique identifier with no intrinsic meaning, but the IDs in your submission must match the submission format exactly
accepted - Indicates whether the mortgage application was accepted (successfully originated) with a value of 1 or denied with a value of 0
