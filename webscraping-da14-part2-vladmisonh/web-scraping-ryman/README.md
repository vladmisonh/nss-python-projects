# Ryman Events Web Scraping Project  

This project focuses on extracting concert and event information from the [Ryman Auditorium Events](https://ryman.com/events/) page using **Python**, **Requests**, and **BeautifulSoup**.  
The scraped data is structured into a **pandas DataFrame** for further use and analysis.  

---

## Project Overview  

The primary goal was to automate data collection from the Ryman website to obtain a list of upcoming performances with key details such as:  
- **Performer Name**  
- **Event Date**  
- **Event Time**  

The project includes HTML parsing logic to clean and format the extracted data and prepare it for use in data analytics, scheduling, or content marketing automation.  

---

## Steps Performed  

1. **Web Request and Parsing**  
   - Fetched event listings using the `requests` library.  
   - Parsed HTML content with `BeautifulSoup`.  

2. **Data Extraction**  
   - Extracted performer names from `<h3>` tags with class `"title"`.  
   - Extracted event dates (e.g., *Oct 6, 2025*) and standardized them to format `YYYY-MM-DD`.  
   - Extracted event times (e.g., *7:30 PM*).  

3. **Data Structuring**  
   - Created a **pandas DataFrame** with the following columns:  
     - `Performer`  
     - `Date`  
     - `Time`  
   - Ensured all values were cleaned and aligned across multiple lists.  

4. **URL Construction (Bonus)**  
   - Built event URLs dynamically based on extracted performer names, event dates, and times using proper formatting (`yyyy-mm-dd/artist-name-at-time`).  

---

## Tools & Libraries  

- **Python 3.x**  
- **requests** – for HTTP requests  
- **BeautifulSoup (bs4)** – for HTML parsing  
- **pandas** – for data structuring and storage  

---

## Example Output  

| Performer         | Date       | Time   |  
|-------------------|------------|--------|  
| Chris Stapleton   | 2025-10-06 | 7:30PM |  
| Luke Combs        | 2025-10-08 | 8:00PM |  
| Carrie Underwood  | 2025-10-10 | 7:00PM |  

---

## Learning Outcomes  

- Learned to handle **dynamic HTML elements** and extract multiple parallel data fields.  
- Gained experience with **data cleaning and normalization** for consistent date formats.  
- Practiced **combining text extraction and transformation logic** in BeautifulSoup workflows.  

---

## Repository Contents  

- **scraping_ryman.ipynb** – Main Jupyter Notebook with web scraping logic  
- **README_task.md** – Original project instructions  
- **README.md** – This documentation file  

---

This project demonstrates how **web scraping can automate event data collection** for entertainment, marketing, or analytics applications.  
