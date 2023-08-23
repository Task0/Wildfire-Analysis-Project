# Wildfire Analysis Project

## Project Overview

This project aims to analyze wildfire data to gain insights into their distribution, causes, and severity. It involves using Python, Spark, PostgreSQL, and various data analysis techniques to achieve these goals.

## Dataset

The wildfire dataset used in this project can be found on [Kaggle](https://www.kaggle.com/datasets/elmadafri/the-wildfire-dataset). It includes information about wildfire incidents, their locations, dates, causes, and more.

## Project Steps

1. **Data Acquisition and Preprocessing:**
   - Download and load the dataset using Python and Pandas.
   - Perform data exploration and handle missing values, duplicates, and outliers.

2. **Data Storage:**
   - Set up a PostgreSQL database to store the cleaned data.
   - Insert the preprocessed data into the database for efficient querying.

3. **Data Analysis and Prediction:**
   - Use PySpark to explore and analyze the dataset.
   - Prepare features for a wildfire severity prediction model.
   - Split the data into training and testing sets.
   - Build and evaluate a predictive model using Spark's MLlib.

4. **Text Analysis:**
   - Process text data from the dataset for sentiment analysis.
   - Use NLP techniques to determine emotions related to wildfires.

5. **Visualization:**
   - Create various visualizations using Matplotlib and Seaborn.
   - Visualize wildfire distribution on a geographical map.
   - Plot trends over time and correlations between variables.

6. **Reporting and Presentation:**
   - Summarize findings, insights, and challenges faced.
   - Explain data preprocessing steps and visualization choices.
   - Present results of predictive models and sentiment analysis.

## Getting Started

1. Clone this repository to your local machine.
2. Set up the PostgreSQL database and create the necessary schema and tables.
3. Install the required Python libraries using `requirements.txt`.
4. Run the Jupyter Notebook files in sequential order to follow the project steps.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.

## Acknowledgments

- Special thanks to Kaggle and the dataset contributors for providing valuable data.

