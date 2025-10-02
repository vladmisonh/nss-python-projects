# Web Scraping the Country Music Hall of Fame  

This project demonstrates web scraping with **Python, Requests, and BeautifulSoup**, applied to the **Country Music Hall of Fame** website.  
The goal was to build a structured dataset of all Hall of Fame inductees, their induction years, and additional biographical details.  

---

## Project Overview  

The tasks included:  

1. **Extract Names of Inductees**  
   - Scraped the Hall of Fame page to identify all inductees’ names.  

2. **Extract Induction Years**  
   - Captured the year each artist was inducted, storing only the numeric year (e.g., `1962`).  

3. **Create a DataFrame**  
   - Combined names and years into a pandas DataFrame for structured analysis.  

4. **Extract Biographical Details from Artist Pages**  
   - For each inductee, followed their profile URL.  
   - Extracted:  
     - **Birth Date**  
     - **Death Date** (if available)  
     - **Birthplace**  
   - Handled missing values gracefully (e.g., some artists like *Alabama* do not have all fields available).  

---

## Tools & Technologies  

- **Python** – Jupyter Notebook environment  
- **Requests** – Fetching HTML content  
- **BeautifulSoup (bs4)** – HTML parsing and data extraction  
- **pandas** – Structuring and cleaning data  

---

## Key Insights  

- Successfully transformed unstructured HTML into a structured dataset.  
- Created reusable scraping functions for robust data collection.  
- Built a complete dataset of **inductee name, induction year, birth date, death date, birthplace**.  
- Implemented error handling and missing value management.  

---

## Learning Outcomes  

Through this project, I strengthened my skills in:  
- Writing scraping logic with `requests` and `BeautifulSoup`.  
- Handling messy or inconsistent web page structures.  
- Automating scraping across multiple linked pages.  
- Organizing results into a DataFrame and exporting to CSV.  

---

## Repository Contents  

- **Scraping_CMA.ipynb** – Main Jupyter Notebook with scraping logic  
- **README_task.md** – Original assignment instructions  
- **README.md** – This project description and documentation  

---

This project highlights how **web scraping can be applied to build datasets from non-API sources**, enabling structured analysis of cultural and historical records.  
