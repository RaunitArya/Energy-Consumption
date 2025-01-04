# Energy Consumption Forecasting

## Project Overview

This project focuses on forecasting global energy consumption and carbon emissions using a comprehensive dataset spanning from 2000 to 2020. By leveraging machine learning models and advanced analytics techniques, the project aims to provide accurate predictions and insights that can empower policymakers, businesses, and individuals to make informed decisions aligned with sustainability goals.

## Objectives

1. Develop accurate forecasting models for global energy consumption and CO2 emissions.
2. Investigate the impact of renewable energy adoption on energy consumption and emissions.
3. Explore the relationship between economic growth and sustainable energy practices.
4. Evaluate the effectiveness of forecasting models over time.

## Key Features

- **Comprehensive Dataset:** Covers sustainable energy indicators, economic factors, and geographical information for various countries.
- **Temporal Analysis:** Analyzes trends and patterns over a two-decade period.
- **Holistic Approach:** Considers economic, renewable energy, and geographical factors.
- **Advanced Forecasting Models:** Implements machine learning techniques like Random Forest, Gradient Boosting, and XGBoost.

## Use Cases

- **Data-Driven Decision-Making:** Provides insights for policymakers and businesses.
- **Renewable Energy Planning:** Assists in integrating renewable energy sources into the grid.
- **Environmental Initiatives:** Supports campaigns to reduce carbon emissions.

## Dataset

The dataset includes:

- **Entity**: The name of the country or region for which the data is reported.
- **Year**: The year for which the data is reported, ranging from 2000 to 2020.
- **Access to electricity (% of population)**: The percentage of population with access to electricity.
- **Access to clean fuels for cooking (% of population)**: The percentage of the population with primary reliance on clean fuels.
- **Renewable-electricity-generating-capacity-per-capita**: Installed Renewable energy capacity per person
- **Financial flows to developing countries (US $)**: Aid and assistance from developed countries for clean energy projects.
- **Renewable energy share in total final energy consumption (%)**: Percentage of renewable energy in final energy consumption.
- **Electricity from fossil fuels (TWh)**: Electricity generated from fossil fuels (coal, oil, gas) in terawatt-hours.
- **Electricity from nuclear (TWh)**: Electricity generated from nuclear power in terawatt-hours.
- **Electricity from renewables (TWh)**: Electricity generated from renewable sources (hydro, solar, wind, etc.) in terawatt-hours.
- **Low-carbon electricity (% electricity)**: Percentage of electricity from low-carbon sources (nuclear and renewables).
- **Primary energy consumption per capita (kWh/person)**: Energy consumption per person in kilowatt-hours.
- **Energy intensity level of primary energy (MJ/$2011 PPP GDP)**: Energy use per unit of GDP at purchasing power parity.
- **Value\_co2\_emissions (metric tons per capita)**: Carbon dioxide emissions per person in metric tons.
- **Renewables (% equivalent primary energy)**: Equivalent primary energy that is derived from renewable sources.
- **GDP growth (annual %)**: Annual GDP growth rate based on constant local currency.
- **GDP per capita**: Gross domestic product per person.
- **Density (P/Km2)**: Population density in persons per square kilometer.
- **Land Area (Km2)**: Total land area in square kilometers.
- **Latitude**: Latitude of the country's centroid in decimal degrees.
- **Longitude**: Longitude of the country's centroid in decimal degrees.

This dataset is available on Kaggle

[https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy](https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy)

## Methodology

1. **Data Collection:** Gathered data on energy indicators, economic factors, and geographical details.
2. **Data Preprocessing:** Handled missing values, outliers, and standardized units.
3. **Exploratory Data Analysis (EDA):** Visualized trends, correlations, and geographical patterns.
4. **Feature Engineering:** Created new features to enhance predictive power.
5. **Model Development:** Employed Random Forest, Gradient Boosting, and XGBoost models.
6. **Model Evaluation:** Evaluated models using R² score and other performance metrics.

## Results

- Gradient Boosting and XGBoost provided the best predictions due to their ability to capture complex patterns and improve iteratively by learning from errors.
- XGBoost emerged as the most accurate model, with predictions closely aligning with actual values.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost
- **Tools:** Jupyter Notebook

## Project Flow

1. Data Collection and Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Development and Training
5. Model Evaluation and Comparison
6. Insights and Forecast Visualization

## How to Use

1. Clone the repository:

        git clone https://github.com/your-username/energy-co2-forecasting.git
2. Install dependencies:

        pip install -r requirements.txt
3. Run the Jupyter Notebook to explore the data and train models:

        jupyter notebook
4. View the results and visualizations in the notebook.

## Future Work

- Incorporate real-time data for more accurate forecasting.
- Experiment with deep learning models for improved predictions.
- Extend analysis to regional and sector-specific trends.
