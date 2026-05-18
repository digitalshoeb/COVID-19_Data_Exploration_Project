# COVID-19_Data_Exploration_Project

Project Overview

This project is designed to showcase technical proficiency in exploratory data analysis (EDA)
. Using a global COVID-19 dataset, the project utilizes Microsoft SQL Server to uncover trends in infection rates, mortality statistics, and vaccination progress across various countries and continents
. The final output includes a series of saved SQL Views intended for later visualization in Tableau
.

Technical Stack

- Data Tooling: Microsoft SQL Server, Excel

- SQL Proficiency: Joins, Common Table Expressions (CTEs), Temp Tables, Window Functions, Aggregate Functions, and Creating Views


Data Workflow

1. Preparation & Cleaning

- Data Sourcing: Downloaded a comprehensive global dataset from "Our World in Data," covering statistics from early 2020 onwards
.

- Excel Pre-processing: Re-formatted the raw data and separated it into two distinct tables—CovidDeaths and CovidVaccinations—to facilitate advanced joining and querying
.

- SQL Ingestion: Successfully imported the datasets into a SQL Server database, overcoming technical 32-bit/64-bit compatibility errors using the SQL Server Import and Export Wizard
.

2. Exploratory Data Analysis (EDA)

   A series of complex queries were developed to extract high-level business intelligence:

- Mortality Risk: Calculated the Death Percentage (Total Deaths vs. Total Cases) to determine the likelihood of dying if infected in a specific country
.

- Infection Prevalence: Analyzed the Infection Rate (Total Cases vs. Population) to show what percentage of a country's population has contracted the virus
.

- Regional Benchmarking: Identified countries with the highest infection rates and death counts per population
.

- Global Aggregation: Summarized total global cases (approx. 150 million) and deaths (approx. 3.1 million), resulting in a global death percentage of roughly 2.11%
.

3. Advanced SQL Implementation

   To demonstrate professional-level database management, the project implemented:

- Joining Tables: Linked deaths and vaccinations data on location and date
.

- Window Functions: Created a rolling count of new vaccinations using SUM over a PARTITION BY location and ORDER BY date
.

- CTEs & Temp Tables: Utilized Common Table Expressions and Temporary Tables to store intermediate rolling counts for secondary calculations, such as determining the percentage of a population vaccinated over time
.

- Creating Views: Established permanent Views to store processed data for efficient retrieval by data visualization software
.

Project Outcomes

- Provided a clear statistical picture of the pandemic's impact at both country and continental levels
.

- Established a foundation for a Tableau dashboard by creating optimized data views
.

- Documented all queries in a clean, commented SQL script suitable for a professional portfolio
.
