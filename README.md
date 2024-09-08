# Data Analyst Job Listings on LinkedIn

## Introduction

This project extracts and analyzes LinkedIn job ads for data analyst positions in the USA.
The results are intended to help an educational institute optimize its data analysis program to better align with industry needs.

The project is divided into the following steps:

- **Step 1:** Data extraction from LinkedIn using web scraping techniques in Python.  
- **Step 2:** Data cleaning and preparation in Python.  
- **Step 3:** Creation of a Power BI report.  

## Technical Details

**Step 1: Web Scraping**

- Performed web scraping to select 1000 job postings from the LinkedIn website.
- Automated the data extraction from each job posting using the Selenium package.
- Exported the data to a CSV in table format.

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

## Impact
 
Visualizations in the Power BI report offer a clear overview of market trends and skill requirements. 
Insights on top technologies, experience levels, and regional job openings help guide curriculum 
development and identify valuable internship partnerships to better prepare students.

## Visuals

Power BI: heat map, stacked bar chart, clustered column chart, and cards. 

## Disclaimer
**Note:** Scraping public data from LinkedIn is legal according 
to [LinkedIn's guide](https://www.linkedin.com/pulse/unlocking-power-linkedin-scraping-comprehensive-guide-tikflow-rpa/) (accessed on 09/13/2023).