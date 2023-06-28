# Covid-19 Dashboard
## Overview
This repository contains a Covid-19 Dashboard developed using Power BI. The dashboard provides visualizations and insights based on Covid-19 dataset obtained from the website "https://www.trackcorona.live ". Additionally, it includes it's corresponding SQL dataset files.
## Dataset
The dataset used for this project is sourced from the website "https://www.trackcorona.live". This website provides real-time Covid-19 data for various countries. Please refer to the website for more details on the dataset and its availability.
## Project Structure
This repository is structured as follows:
-	Readme file: README.md
-	SQL dataset files:
	- covid_confirmed_global.sql
	- covid_death_global.sql
	- covid_recovered_global.sql
-	Covid-19_Dashboard.pbix:
	- This power bi file contains the dashboard comprising of various visualizations performed on the dataset.
	- Feel free to explore the Covid-19_Dashboard.pbix file to view the specific visualizations used in this analysis.
## Dashboard Components
The Covid-19 Dashboard includes the following components:
-	KPI Metrics: Presents key performance indicator metrics such as confirmed cases, active cases, recovered cases, death count, recovery rate, and death rate.
-	Country-wise Cases: Displays the number of confirmed cases, active cases, recovered cases, and deaths for each country.
-	Geographic Map Visual: Visualizes the number of confirmed cases by geographical location on a world map, allowing for a geographical understanding of the spread.
-	Confirmed cases analysis (by Country): Shows the number of confirmed cases for each country in descending order of their occurrences and highlights the top five countries with the highest case counts.
-	Confirmed cases analysis (by Year & Month): Presents the number of confirmed cases by year and month, highlighting the top five periods with the highest case counts.
-	Current vs Previous Period Comparison: Compares the number of confirmed cases to the same period in the previous year, allowing for an assessment of the growth or decline.
## Usage
To explore the Covid-19 Dashboard:
1.	Clone the repository: git clone https://github.com/chinmoy2306/Covid-19_dashboard.git
2.	Open Power BI Desktop or Power BI Online.
3.	Import the SQL files located in the repository into your SQL database management system (e.g., MySQL, Microsoft SQL Server).
4.	Open the Power BI project file (Covid-19_dashboard.pbix) located in the repository.
5.	In Power BI, refresh the data connection to ensure the dashboard is using the latest dataset.
6.	Interact with the different dashboard components to gain insights into the Covid-19 data.
7.	Customize the dashboard as per your requirements by modifying the visuals, adding new insights, or connecting additional data sources.
## Dependencies
To work with the Covid-19 Dashboard, you will need the following:
-	Power BI Desktop or Power BI Online: The dashboard was designed using Power BI and requires Power BI Desktop or Power BI Online to explore the visuals and interact with the data.
-	SQL Database Management System: You need a SQL database management system (e.g., MySQL, Microsoft SQL Server) to import and store the Covid-19 dataset from the provided SQL files in the repository.
-	Please ensure that you have the appropriate software and dataset available before using the dashboard.
## License
The dataset used in this project is sourced from the website "https://www.trackcorona.live" and is subject to the licensing terms provided by the website owner. Please refer to the website or contact the owner for more information on licensing and usage permissions for their data.
## Acknowledgments
Special thanks to the website "https://www.trackcorona.live" for providing the Covid-19 data, enabling us to create this analytics dashboard. We appreciate their efforts in collecting and sharing the data for analysis.
