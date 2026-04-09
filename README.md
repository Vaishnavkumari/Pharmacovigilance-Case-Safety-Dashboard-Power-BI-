# Pharmacovigilance Case Safety Dashboard (Power BI)

##  Overview
This project presents an interactive Pharmacovigilance (PV) dashboard built using Power BI to analyze Individual Case Safety Report (ICSR) data.  

The dashboard provides insights into case seriousness, outcome distribution, causality assessment (WHO-UMC), and SOC-based adverse event patterns using MedDRA coding.


##  Key Features
- Case-level analysis using DISTINCTCOUNT to handle follow-up duplicates  
- Serious vs Non-serious case distribution (70% serious cases)  
- Outcome distribution (Recovered, Fatal, Recovering, Not-recovered)  
- Causality assessment based on WHO-UMC criteria  
- SOC (System Organ Class) distribution using MedDRA coding  
- Identification of key safety signals (e.g., fatal case requiring expedited reporting)  


##  Tools & Technologies
- Power BI  
- Microsoft Excel  
- Pharmacovigilance Concepts (ICSR, MedDRA, WHO-UMC)  


##  Problem Solved
ICSR datasets often contain duplicate records due to follow-up reports (e.g., the same case appearing multiple times).  

This project handles this challenge by applying DISTINCTCOUNT on Case ID to ensure accurate case-level analysis instead of incorrect row-level counting.


##  Key Insights
- 70% of cases were classified as serious  
- Majority of cases resulted in recovery  
- One fatal case (Atorvastatin) identified requiring expedited reporting  
- Skin & Subcutaneous disorders showed highest case frequency  


##  Conclusion
This project demonstrates the application of data analytics in pharmacovigilance by combining domain knowledge with visualization to support drug safety monitoring and decision-making.
