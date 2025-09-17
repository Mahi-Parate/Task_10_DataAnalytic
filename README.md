# Task_10_DataAnalytic
# Job Scraping & Analysis – Internship Task

This project scrapes **Data Analyst Internship** job listings from [Internshala](https://internshala.com/) using **Python + BeautifulSoup**, cleans the data, and performs **basic analysis** with visualizations.


## Tools & Libraries
- Python 3  
- `requests` – fetch webpages  
- `BeautifulSoup` – parse HTML  
- `pandas` – store & clean data  
- `matplotlib` – visualize results  
- `collections.Counter` – count frequency of skills  

## Features
✔ Scrapes Job Title, Company, Location, Salary, Skills  
✔ Handles missing values (fills with realistic companies, cities, and skills)  
✔ Saves results into **CSV file** (`data_analyst_jobs.csv`)  
✔ Analyzes top job locations and most in-demand skills  
✔ Provides **bar plot** & **pie chart** for insights  

Challenges Faced:
1. Website structure changes frequently; tags/classes may differ.
2. Pagination limits – only first few pages scraped to avoid blocking.
3. Salary/Stipend formats vary; need regex cleaning for proper analysis.
4. Ethical scraping: added delays (time.sleep) to avoid overwhelming server.
5. Some Company/Location/Skills were missing -> filled with realistic sample data.
