# GLP1a-In-The-Real-World
A work in progress of the long-winded process of using R to clean data and gathering cohort statistics to inform a retrospective study measuring the primary outcome of weight loss over time. 


The different raw data tables used in the analyses are from the PCORnet relational database. 
Tables include:

- Demographics
- Death
- Enrollment
- Encounter
- Dispensing
- Condition
- Diagnosis
- Procedures
- Lab Results
- Vital


The raw data is not included for confidentiality purposes. 

Tidyverse is used ad nauseum since it is vastly versatile for data querying and cleaning. 

This work is highly iterative and a constantly changing process in two ways

1. I had self-learned R as my first programming language in Jan 2021 (gateway was Hadley Wickham's R4DS textbook), and by May 2021 I had received an offer for this analyst position. Thus, this position was also my first experience working with large, often-messy, real-world datasets and the early drafts include a lot of "just trying to figure out how this data is structured" and getting used to ways of querying and summarizing the data 
2. Being a retrospective cohort study, the analysis plan is constantly revised based on new collections of counts. e.g. To determine an ideal baseline time window, I generated the number of patients (who meet the inclusion criteria) who have weights in weeks (-8,0] AND followup, in weeks (-12, 0] AND followup, in weeks (-16, 0] AND followup, etc., all relative to the first dispensement date of a GLP1a. 


This repository will be frequently updated, as the data cleaning process is ongoing. Later drafts will include table one output as well as mixed models for factors relating to missing data. 
