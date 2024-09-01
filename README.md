# Data Analyst Job Listings on LinkedIn

## Introduction

This project extracts and analyzes LinkedIn job ads for data analyst positions in the USA. The results are intended to help an educational institute optimize its data analysis program to better align with industry needs. Specifically, the analysis seeks to provide:

- The number of job ads analyzed.
- The period during which the data was collected.
- The requested experience levels.
- The most common technical terms mentioned in job postings (e.g., Python, R, SQL, Git).
- The geographic distribution of job postings across US states.

The project is divided into the following steps:

- **Step 1:** Data extraction from LinkedIn using web scraping techniques in Python.  
- **Step 2:** Data cleaning and preparation in Python.  
- **Step 3:** Creation of a Power BI report.  

**Note:** Scraping public data from LinkedIn is legal according 
to [LinkedIn's guide](https://www.linkedin.com/pulse/unlocking-power-linkedin-scraping-comprehensive-guide-tikflow-rpa/) (accessed on 09/13/2023).

## Technical Details

**Step 1: Web Scraping**

- Performed web scraping to select 1000 job postings from the LinkedIn website.
- Automated the data extraction from each job posting using the Selenium package.
- Exported the data to a CSV file, including job posting details such as date, 
company name, job title, job description, seniority level, location, and other 
relevant information.

**Step 2: Data Cleaning and Preparation**

- **Data Cleaning:**
  - Utilized Python libraries such as Pandas and NumPy to handle missing values, correct data types, and remove duplicates.
- **Tech Terms Extraction:**
  - Applied regular expressions to identify and list the most common technical terms and skills mentioned in job postings.
  - Filtered the ads to focus exclusively on data analysis positions.
- **Geographic Analysis:**
  - Aggregated job postings by US states to visualize the regional demand for data analyst positions.

**Step 3: Report**

- Created bar charts to display the top technologies mentioned in job ads.
- Developed a heatmap highlighting US regions with the highest number of job openings.
- Analyzed and described the distribution of required seniority levels in job ads.
- Provided additional information about the total number of job ads analyzed and the data collection period.
