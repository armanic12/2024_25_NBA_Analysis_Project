# 2024-25 NBA Analysis Project  
By Armani Correia, MS  

## Summary  
This project extracts, cleans, and exports NBA player per-game data for the 2024-2025 season. It feeds the cleaned data into a Tableau dashboard for exploratory analysis and interactive visualization.

## Data Pipeline  
The notebook `NBA_Data_Web_Scrape.ipynb`:
- Uses Requests to fetch data from Basketball Reference  
- Parses HTML with BeautifulSoup  
- Gathers table headers and stats into a pandas DataFrame  
- Cleans data via regex and text processing  
- Offers two export modes: via GitHub API or saved locally  
- Includes final output file `NBA25_output.csv`  

## Tableau Visualization  
Hosted on Tableau Public. The dashboard connects to the scraped and cleaned data. It enables filtering, trend exploration, and interactive display of key player stats.

URL to interactive dashboard: https://public.tableau.com/views/NBAAnalysis_17549436755440/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## How to Run  
1. Open `NBA_Data_Web_Scrape.ipynb` in Jupyter  
2. Run all cells to recreate data extraction, cleaning, and export  
3. View `NBA25_output.csv` directly or load it into your own analysis tools  
4. Explore the Tableau dashboard using the public link for interactive insights  

## Files Included  
- `NBA_Data_Web_Scrape.ipynb` — scraper plus data transformation pipeline  
- `NBA25_output.csv` — final dataset for the 2024-25 season  
- `README.md` — project overview and instructions  

## Skills and Techniques Used  
- Web scraping with Python  
- HTML parsing using BeautifulSoup  
- Data extraction from structured HTML tables  
- Data cleaning with regex and string operations  
- Data transformation and organization using pandas  
- API-based file export to GitHub  
- CSV file handling and local export workflows  
- Data visualization design in Tableau  
- Integration of scraped datasets into interactive dashboards  
- Workflow documentation and reproducible analysis setup  

## Tools Used  
- Python with Requests, BeautifulSoup, pandas  
- GitHub API for exporting data
- Tableau for visualization
