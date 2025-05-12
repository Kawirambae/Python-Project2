🦠 COVID-19 Global Data Tracker

📊 Overview
The COVID-19 Global Data Tracker is a data analysis project designed to explore global COVID-19 trends, using real-world data from Our World in Data. The project includes data cleaning, exploratory data analysis (EDA), and insightful visualizations to communicate the progression of the pandemic across selected countries.

🎯 Objectives
Import and clean global COVID-19 data

Analyze time trends of total cases, deaths, and vaccinations

Compare daily new cases and death rates between countries

Visualize trends using Matplotlib, Seaborn, and Plotly

Generate narrative insights for reporting and presentations

📁 Dataset
Source: Our World in Data - COVID-19 Dataset

Format: owid-covid-data.csv

Key fields: date, location, total_cases, total_deaths, new_cases, total_vaccinations, population, etc.

🔧 Tools & Technologies
Python 3

Pandas – for data manipulation

Matplotlib & Seaborn – for data visualization

Plotly Express (optional) – for interactive maps

Jupyter Notebook – for combining code, visuals, and insights

📈 Visualizations
Line charts for total cases, deaths, and vaccinations over time

Daily new cases comparison

Bar charts for top countries by total cases and % vaccinated

Heatmaps to show metric correlations

Pie charts for vaccinated vs. unvaccinated population

(Optional) Choropleth maps of global spread

🔍 Key Insights
The United States had the highest total confirmed cases and deaths.

India experienced a sharp surge in daily new cases in mid-2021.

Germany led in vaccination coverage among the selected countries.

Kenya had lower reported case counts but possibly due to limited testing/reporting.

Some countries reported more vaccinations than population — likely due to dose-counting rather than people.

✅ How to Run
Clone or download this repository

Place the owid-covid-data.csv file in your working directory

Open the notebook: covid_global_tracker.ipynb

Run each cell sequentially to reproduce the analysis and visualizations

📜 License
This project is open for educational and non-commercial use. Cite Our World in Data as the original dataset provider.











