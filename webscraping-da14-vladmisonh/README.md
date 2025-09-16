# Webscraping with Python – BeautifulSoup & Requests  

This project demonstrates web scraping techniques using Python libraries **Requests** and **BeautifulSoup**. The exercises focus on extracting structured data from websites, transforming it into **pandas DataFrames**, and performing further analysis.  

The project was completed as part of the **Nashville Software School (NSS) Data Analytics Bootcamp**, designed to practice applied data collection from the web.  

---

## Project Overview  

The project consists of two main parts:  

### 1. Job Listings Scraper 
Website: [Fake Jobs Page](https://realpython.github.io/fake-jobs/)  
- Extract job titles, companies, locations, and posting dates.  
- Collect "Apply" button URLs in two different ways:  
  1. Directly with BeautifulSoup (`find_all`).  
  2. Constructing URLs using extracted text patterns.  
- Extract job descriptions from individual job pages.  
- Write a function to retrieve all job descriptions and add them to the DataFrame.  

**Skills Practiced:**  
- HTML parsing (`find`, `find_all`, `select`).  
- String cleaning for URL construction.  
- DataFrame creation with pandas.  
- Using `.apply()` for function application across a column.  

### 2. Billboard Hot 100 Scraper  
Website: [Billboard Hot 100](https://www.billboard.com/charts/hot-100/)  
- Extract current chart data:  
  - Rank, song title, artist, last week’s position, peak position, and weeks on chart.  
- Write a function to scrape charts for any given date.  
- Loop through 10 weeks of charts to collect historical data.  

**Skills Practiced:**  
- Navigating HTML differences between elements (e.g., #1 ranked song vs. others).  
- Function design for reusable scraping.  
- Automating collection with loops.  

---

## Tools & Libraries  

- **Python** – Jupyter Notebook environment  
- **Requests** – Retrieve HTML pages  
- **BeautifulSoup (bs4)** – Parse and extract structured data from HTML  
- **pandas** – Organize and analyze extracted data  

---

## Key Insights  

- Successfully converted unstructured HTML content into structured tabular data.  
- Learned how to handle **inconsistent HTML structures** (special cases like top-ranked songs).  
- Built reusable scraping functions to collect multi-week datasets.  
- Demonstrated **data cleaning and transformation** before storing results in DataFrames.  

---

## Learning Outcomes  

This project strengthened my skills in:  
- Writing Python scripts for web scraping.  
- Parsing HTML with BeautifulSoup.  
- Handling messy and inconsistent web data.  
- Automating multi-page scraping workflows.  
- Structuring extracted data for further analytics.  

---

## Repository Contents  

- **webscraping_project.ipynb** – Job listings scraping project  
- **webscraping_project_bonus.ipynb** – Billboard Hot 100 bonus scraper  
- **README_task.md** – Main assignment description  
- **README_Bonus_task.md** – Bonus task description  

---

This project highlights how **web scraping can transform raw web content into structured datasets**, a critical skill for modern data analysts.  
