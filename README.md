# Netflix Content Analysis

## Overview
This project presents a comprehensive exploratory data analysis (EDA) of Netflix’s content library using Python. The objective is to analyze content distribution, production trends, audience targeting, and platform growth through data preprocessing, visualization, and insight generation.

Netflix, being one of the largest global streaming platforms, offers a diverse catalog of movies and television shows. This analysis provides meaningful business and content insights by examining genre trends, geographical content distribution, release patterns, ratings, and director contributions.

---

## Project Objectives
The primary objectives of this project are:

- To analyze the distribution of Movies and TV Shows available on Netflix
- To identify the most popular genres across the platform
- To examine country-wise content production trends
- To study Netflix’s content expansion over time
- To evaluate audience rating classifications
- To analyze movie duration distribution
- To identify directors with the highest number of titles on Netflix

---

## Technology Stack
This project was developed using the following tools and technologies:

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## Dataset Information
**Dataset:** Netflix Movies and TV Shows Dataset

The dataset contains metadata related to Netflix content, including:

- Show ID
- Content Type
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre Classification
- Description

---

## Data Preprocessing
To ensure data quality and consistency, the following preprocessing steps were performed:

- Dataset loading and structural inspection
- Identification of missing values
- Handling null values in categorical columns
- Removal of invalid or incomplete records
- Conversion of date fields into datetime format
- Feature engineering for trend analysis (`year_added`)
- Data cleaning and formatting for visualization readiness

---

## Exploratory Data Analysis

### 1. Content Type Distribution
A comparative analysis was performed to understand the distribution between Movies and TV Shows available on Netflix.

**Key Finding:**  
Netflix’s catalog is predominantly composed of movies, indicating a stronger emphasis on feature-length content.

---

### 2. Genre Analysis
Genre-based exploration was conducted to identify the most frequently occurring content categories.

**Key Finding:**  
Drama, comedy, and international content categories represent a significant portion of Netflix’s offerings.

---

### 3. Country-wise Content Production
A geographical analysis was performed to evaluate the countries contributing the highest volume of Netflix content.

**Key Finding:**  
The United States leads content production, followed by India and the United Kingdom, highlighting Netflix’s strong presence in major entertainment markets.

---

### 4. Content Growth Trend Analysis
A time-series analysis was conducted to understand Netflix’s expansion in content additions over the years.

**Key Finding:**  
A significant surge in content growth was observed after 2015, reflecting aggressive platform expansion and increased content acquisition.

---

### 5. Rating Distribution Analysis
Audience rating categories were analyzed to understand Netflix’s target demographic segmentation.

**Key Finding:**  
TV-MA and TV-14 ratings dominate the platform, indicating a strong focus on mature and teenage audiences.

---

### 6. Movie Duration Analysis
The duration distribution of Netflix movies was analyzed to identify content length trends.

**Key Finding:**  
The majority of movies fall within the standard 80–120 minute runtime range.

---

### 7. Director Contribution Analysis
An analysis of directors was performed to identify recurring contributors to Netflix’s content catalog.

**Key Finding:**  
Several directors contribute multiple titles, indicating consistent collaboration patterns with the platform.

---

## Key Insights
- Netflix maintains a significantly larger movie catalog compared to television series.
- Content production is highly concentrated in the United States and India.
- Drama and international genres form a major share of available content.
- Netflix’s content expansion accelerated substantially in recent years.
- Mature audience-focused content dominates the platform.
- Standard feature-length movies remain the most common format.
- Repeated contributions from specific directors suggest strategic content partnerships.

---

## Project Structure
```bash
Netflix-Content-Analysis/
│
├── dataset/
│   └── netflix_titles.csv
│
├── notebooks/
│   └── netflix_analysis.ipynb
│
├── images/
│   ├── content_type_distribution.png
│   ├── genre_analysis.png
│   ├── country_distribution.png
│   ├── growth_trend.png
│   ├── ratings_distribution.png
│   ├── duration_analysis.png
│   └── director_analysis.png
│
├── README.md
└── requirements.txt
```

---

## Installation and Execution

### Clone the Repository
```bash
git clone https://github.com/yourusername/Netflix-Content-Analysis.git
```

### Install Required Dependencies
```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook
```bash
jupyter notebook
```

### Execute the Analysis
Open the notebook file and run all cells sequentially.

---

## Requirements
```txt
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## Future Enhancements
Potential improvements for this project include:

- Development of an interactive dashboard using Streamlit or Power BI
- Implementation of sentiment analysis on content descriptions
- Integration of a recommendation engine
- Predictive analysis for trending genres using machine learning
- Deployment as a web-based analytics application

---

## Author
**Lubna Shireen R**

---

## Status
**Completed**
