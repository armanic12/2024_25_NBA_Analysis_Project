# 2024/25 NBA Analysis Project
## By Armani Correia, MS.
### Summary
This project builds a pipeline to extract, preprocess, and export NBA player data for the 2024–2025 season. The exported data will be connected to Tableau for exploratory analysis and for creating an interactive visualization dashboard.

### Data Wrangling and Cleaning
The "NBA_Data_Web_Scrape" script collects NBA player per game statistics for the 2024–2025 season from Basketball Reference. It uses the Requests library to download the webpage and BeautifulSoup to parse the HTML content. The script searches for table headers and data cells, extracts column names, and stores them in a set to remove duplicates. It then builds a pandas DataFrame with these column labels and populates it with player statistics extracted from the table. Regular expressions and text parsing are applied to clean the data. The script ensures that the final dataset is structured with accurate labels for further analysis.

After building the DataFrame, the script performs basic data cleaning and manipulation to prepare it for export. It provides two export options. The first uses the GitHub API to save the file directly to a repository. The second saves the file locally. These options allow flexibility in how the data is stored and shared. The techniques used here include HTML parsing for targeted data extraction, structured data handling with pandas, and conditional logic to support multiple export workflows.

### Tableau Data Visualization

URL to interactive dashboard: https://public.tableau.com/views/NBAAnalysis_17549436755440/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
