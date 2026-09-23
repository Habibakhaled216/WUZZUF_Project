**WUZZUF Job Scraping** 📊

An automated Python-based web scraping project designed to extract job listing data from Wuzzuf. Where it searches for multiple jobs and gets the required information. This scraper targets the first 3 pages of search/category results (can be modified for # number of pages) and gathers essential job information into a structured format for data analysis or storage.
-----------------------------------------------------
📌 **Extracted Data Fields** 

For each job required
the scraper searches for the job and click on the search button to get posts of job-offers

the scraper extracts the following attributes:
* Job Title 
* Company Name 
* Location
* Experience Required (in years)
* Job Description 
* Job URL
--------------------------------------------------------
🛠️ **Tools \& Technologies**

* Python 3.x
* Selenium 
* Pandas (For exporting to CSV)
* Time (So that it can collect and load the data)
---------------------------------------------------------
⚙️ **How It Works** 

* URL Targeting: The script iterates through the first 3 pagination pages of Wuzzuf search results. 
**(Can be used for more pages)** 
* It searches for the following jobs: ['Data Engineer', 'Data Scientist','AI Developer', 'Machine Learning Engineer']
* HTML Parsing: HTML elements containing job cards are parsed using CSS Selectors / Class Name / XPATH / Name.
* Data Extraction: Extracts specific details (Title, Company, Location, Experience, Description and URL) from each job card or individual detail page and saves them as a text.
* Data Export: Saves the gathered dataset into a CSV file format for further use
--------------------------------------------------------------------------------
**The collected data contains more than one job**

