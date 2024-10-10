
# Traffic Accident Analysis in the United States

This project aims to analyze traffic accidents that occurred in the United States. The goal is to identify patterns in accidents based on various factors, such as weather conditions, road types, and regions.

This is a repository developed with Google Collaboratory:

<a href="https://colab.research.google.com/github/joaoangnes/us-accident-analysis/blob/main/us_accident_analysis.ipynb" target="_parent">
  <img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252"/>
</a>

## Project Objectives

* **Data Cleaning**: Using `pandas` to clean the data, remove duplicates, and fill in missing values.

* **Exploratory Data Analysis (EDA)**: Using `seaborn` to find correlations and patterns between accidents and the available variables.

* **Interactive Visualizations**: Creating interactive visualizations using `plotly`, such as interactive maps to display where the most severe accidents occur.

* **Temporal Analysis**: Implementing time-based heatmaps to identify the time of day or days of the week when accidents are most frequent.

## Group Goal

The main goal of this project is to understand the key factors that affect the occurrence and severity of traffic accidents. Our analysis will incorporate rich interactive graphs to help explore accident patterns over time and space.

## Dataset

* **Source**: <https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents>
* **Description**: The dataset contains various features, including accident severity, weather conditions, geographic location.

## Tools & Libraries

* **pandas**: For data manipulation and cleaning.
* **dask**: For data manipulation and benchmarking with pandas.
* **parquet file**: Zip the dataset in a parquet file.
* **seaborn**: For creating exploratory visualizations.
* **plotly**: For building interactive graphs, including maps.
* **matplotlib**: For additional plotting capabilities.

## Learnings

During the development of this project, I learned that working with large CSV files in Python can be challenging, especially when dealing with memory limitations in environments like Google Colab.

While the Dask library excels at reading large volumes of data due to its use of parallelism techniques, Pandas proved to be more efficient for manipulation and analysis after the data has been read. This experience taught me the importance of choosing the right tool for each stage of data processing and the need for strategies to handle the available memory.

These insights were essential in optimizing my workflow and ensuring the effectiveness of the data analysis.

For more details about the analysis and the comparisons made between the libraries, please refer to the associated notebook for this project.
