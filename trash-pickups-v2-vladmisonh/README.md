# Missed Trash Pickups – Data Analytics Project  

This project analyzes **missed trash pickup service requests** from [hubNashville](https://hub.nashville.gov), Metro Nashville’s customer service system. The goal of the project is to determine the financial penalties (liquidated damages) owed by contractors for repeated missed pickups and to explore patterns in waste collection performance.  

The analysis was completed as part of the **Nashville Software School (NSS) Data Analytics Bootcamp**, applying Python, Pandas, and geospatial methods.  

---

## Project Overview  

Metro Nashville’s contract with **Red River Waste Solutions** includes fines for chronic service issues. Specifically:  

- The **first missed pickup** at an address does not result in a fine.  
- Every **subsequent missed pickup** at the same address results in a **$200 fine** .  

Additional questions explored:  
- What other types of service complaints exist?  
- How do Metro crews compare to contractors?  
- How much does each trash hauler owe?  
- What are the total missed pickups by route?  
- Can we identify geospatial patterns in missed pickups?   

A bonus task was also included: testing **alternative fine structures**, such as a **$1500 fine for three or more missed pickups within 180 days** and a variation where each date can only be used once.

---

## Tools & Technologies Used  

- **Python (Jupyter Notebook)** – Data cleaning, transformation, and analysis  
- **Pandas** – Aggregations, filtering, and calculations  
- **Matplotlib / Seaborn** – Data visualization  
- **Geospatial Analysis** – Mapping missed pickups with latitude/longitude  
- **Microsoft Excel / CSV** – Data storage and exploration  

---

## Key Insights  

- Calculation of **total damages owed** under the existing $200-per-event policy.  
- Comparison of **alternative fine models** and their financial impact.  
- Geospatial analysis of missed pickups to identify neighborhoods with chronic issues.  
- Contractor vs. Metro performance benchmarking.  

---

## Learning Outcomes  

This project helped reinforce skills in:  

- Translating **real-world policies into data logic** (fine calculation rules).  
- Using **Python and Pandas** to perform grouped calculations and conditional logic.  
- Applying **geospatial analysis** to service delivery datasets.  
- Comparing **alternative business rules** to assess their policy impact.  
- Communicating results in a clear, structured way via Jupyter Notebooks.  

---

## How to Use This Repository  

The repository contains:  

- **Dataset (`trash_hauler_report_with_lat_lng.csv`)** – Service requests data with latitude/longitude.  
- **Notebook (`trash-pickup.ipynb`)** – Full analysis, calculations, and visualizations.  
- **README_task.md** – Description of the main task and expected outputs.  
- **README_Bonus_task.md** – Description of the bonus task (alternative fine calculations).  