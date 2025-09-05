# Tennessee Opioid Prescribing & Overdose Analysis (2015–2018)  

This project explores the opioid crisis in Tennessee using **Medicare Part D Prescriber data** and **state overdose death statistics**. The analysis investigates opioid prescription patterns, overdose mortality trends, and the association between prescribing rates and overdose deaths.  

This project was completed as part of the **Nashville Software School (NSS) Data Analytics Bootcamp**, combining SQL, Python, and visualization tools to analyze large healthcare datasets.  

---

## Project Overview  

In this project, we analyzed data from the **2017 Medicare Part D Prescriber Public Use File (PUF)** alongside Tennessee Department of Health overdose statistics. Key questions addressed include:  

- Which Tennessee counties had disproportionately high opioid prescription rates?  
- Who are the top opioid prescribers in the state?  
- What was the trend in opioid-related overdose deaths in Tennessee from 2015 to 2018?  
- Is there a correlation between opioid prescriptions and overdose deaths by county?  
- Is there any association between specific opioids and overdose deaths?  

---

## Data Sources  

- **CMS Medicare Part D Prescriber PUF** – Provider-level prescription claims and drug costs  
- **Tennessee Overdose Death Records (2015–2018)** – County-level overdose statistics  
- **Supplementary Tables** – Linking prescriber NPI, specialty, geography, and opioid classification  

---

## Tools & Technologies Used  

- **Python (Jupyter Notebook)** – Data cleaning, joining, statistical analysis  
- **SQLAlchemy** – Querying and joining large relational datasets  
- **Pandas** – Aggregation, correlation, and filtering  
- **Matplotlib / Seaborn** – Trend lines, scatterplots, and correlation visualization  
- **ERD (Entity Relationship Diagram)** – For database schema design and relationships  

---

## Key Insights  

- **Overdose deaths increased steadily** from 2015 to 2018 in Tennessee.  
- A **strong positive correlation** exists between opioid prescriptions and overdose deaths at the county level.  
- Certain counties, such as **Scott County**, showed extreme overdose-to-prescription ratios, identifying them as hotspots.  
- A small group of **high-volume prescribers** accounted for thousands of opioid claims, disproportionately impacting prescription totals.  
- No direct link could be established between **specific opioid types** and overdose deaths, since death records lack case-level drug information.  

---

## Learning Outcomes  

Through this project, I developed expertise in:  

- Working with **large-scale healthcare datasets** (Medicare Part D PUF)  
- Designing and interpreting **ERDs** for relational data analysis  
- Combining **prescription claims data with public health outcomes**  
- Performing **statistical correlation and regression** analyses  
- Communicating insights with clear visualizations and presentations  

---

## Repository Contents  

- **ERD.png** – Entity Relationship Diagram for database design  
- **prescribers.ipynb** – Jupyter Notebook with prescriber analysis  
- **sqlalchemy.ipynb** – SQL queries and database joins using SQLAlchemy  
- **overdose_chart.png** – Tennessee overdose death trend chart  
- **prescriptions_vs_deaths.png** – Visualization of prescription counts vs. overdose deaths  
- **tennessee_opioid_claims_map.png** – Geographic distribution of claims by county  
- **Prescribers Presentation.pdf** – Final presentation deck summarizing findings  
- **Part D Prescriber PUF Methodology.pdf** – CMS official data documentation  

---

This analysis demonstrates the intersection of **data analytics and public health policy**, showing how prescription monitoring can inform efforts to address the opioid epidemic.  
