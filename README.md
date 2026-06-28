Bangalore Tech Salary Decoder

A salary-intelligence analysis of 1,000+ Bengaluru tech professionals, built as a 2-hour live project for The Unlox Academy.

What this is

A synthetic but realistically-patterned dataset of Bengaluru tech salaries was cleaned and analyzed using Python and Pandas to answer five business questions about compensation, then summarized into a printed report and three key insights.

Dataset

bangalore_tech_salaries.csv — 1,015 rows covering role, years of experience, current/previous CTC, company, company type, skills, location, education tier, joining year, and work mode. The raw data was intentionally messy: inconsistent role naming, CTC stored as text in four different formats, and case-inconsistent categorical fields.

What was done


Cleaning: standardized 40+ raw role labels into 11 canonical roles, parsed CTC strings (handling Indian-style number formatting like 15,50,000 → 15.5 LPA) into numeric LPA values, normalized company type and education tier labels, removed duplicate rows.
Analysis:

CTC distribution by role (median/mean/min/max)
SDE Backend pay growth across experience bands
Skill premium for AWS, ML, System Design, and Kubernetes
Company-type pay premium (Unicorn vs MNC vs Mid-size vs Early-stage)
Identification of the most underpaid professionals relative to their peer group (role + company type + experience band)



Output: a printed ASCII-style summary report and three data-backed, action-oriented insights.


Key findings


Product Managers earn close to double the median CTC of Data Analysts.
SDE Backend pay grows fastest in the first 2–3 years on the job (~72% jump).
System Design is the strongest individual skill premium for SDEs (~+20%); AWS is now close to baseline.
Unicorns pay SDE Backend roles ~25% more than MNCs and ~32% more than early-stage companies at the same experience level.


How to run


Open LiveProject_Salary_Decoder_YourName.ipynb in Google Colab or Jupyter.
Upload bangalore_tech_salaries.csv to the same environment.
Run all cells top to bottom.


Tools

Python, Pandas, NumPy.
