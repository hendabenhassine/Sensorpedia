# Sensorpedia -  Data Analytics  Project
# 🌡️ Sensorpedia -  Data Analytics  Project

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" alt="Jupyter">
  <img src="https://img.shields.io/badge/Web-Scraping-green" alt="Web Scraping">
  <img src="https://img.shields.io/badge/Data-Analysis-yellowgreen" alt="Data Analysis">
</div>

<br>


## 🚀 Overview
This project demonstrates **web scraping**, **data cleaning**, and **exploratory data analysis (EDA)** of sensor-related data sourced from Wikipedia. It was created as part of the CodeAlpha Data Analytics Internship program.


## Project Structure
The notebook contains three main tasks:

1. **Web Scraping**: Extracts sensor data from Wikipedia's List of Sensors page
2. **Data Cleaning**: Processes the scraped data to create a structured dataset
3. **Exploratory Data Analysis**: Provides insights into the collected sensor data

## Key Features
- Scrapes technical descriptions of various sensors from Wikipedia
- Cleans and structures the data into a pandas DataFrame
- Performs comprehensive EDA including:
  - Basic dataset information
  - Summary statistics
  - Missing values analysis
  - Category distribution
  - Most common words in descriptions
- Visualizations of the data distribution

## Data Output
The processed data is saved as `sensors_technical_descriptions.csv` containing:
- Sensor names
- Categories
- Technical descriptions

## Requirements
- Python 3.x
- Required packages:
  - requests
  - BeautifulSoup
  - pandas
  - re
  - collections
  - seaborn (for visualizations)

## Usage
1. Run the Jupyter Notebook cells sequentially
2. The script will:
   - Scrape data from Wikipedia
   - Save cleaned data to CSV
   - Perform and display EDA results

## Insights
The analysis revealed:
- 403 unique sensors across 18 categories
- "Others" was the most common category (52 sensors)
- "Measures physical characteristics" was the most frequent description
- Temperature, pressure, and optical sensors were well-represented

## Future Enhancements
- Add more visualizations
- Implement natural language processing on descriptions
- Expand data sources beyond Wikipedia
- Create a sensor classification system


