# The-effect-of-SNF-VBP-on-intended-and-unintended-outcomes
README 

The code files posted here accompany the manuscript:

Burke RE, Hutchins F, Heintz J, et al. Skilled Nursing Facility Value-Based Purchasing Failed To Achieve Hospital Readmission Reductions And Other Targets. Health Aff (Millwood). 2025;44(6):722-730. doi:10.1377/hlthaff.2024.01402

Work for this manuscript was supported by the National Institue on Aging, funding number: NIA R01AG071610.

The code files apply logic published under the Skilled Nursing Facility Value-Based Purchasing (SNF VBP) Program. See:
https://www.cms.gov/medicare/quality/nursing-home-improvement/value-based-purchasing/measures

Some files are adapted from code provided by CMS via the following Freedom of Information Act (FOIA) request: 

Control/ID Number: 042320237001
Request Submitted to CMS: 04/26/2023
Records Released: 02/26/2024
Subject: Risk-Standardized Readmissions Rates
Submitting organization: University of Pennsylvania

The following files, used in order, create a cohort of skilled nursing facility visits occurring between 2011 and 2021 that meet eligibility criteria of the SNF VBP program, identify unplanned readmissions following eligible visits, and create additional variables required for the analysis: 

0a_MBSF_2011_2014.sas
0b_MBSF_2015_2019.sas
0c_MBSF_2020_2021.sas
1_MEDPAR_Cohort.sas
2_EXCLUSIONS.sas
3a_Unplanned_ICD9.sas
3b_Unplanned_ICD10.sas
4_Add_Variables.sas
5_FacilityLevel.sas
6_FacilityLevel_Exposure.sas

The following files are the analytic code for the difference in differences models presented:

DID_MACRO_WRITE.R
DID_MACRO_CALL.R
