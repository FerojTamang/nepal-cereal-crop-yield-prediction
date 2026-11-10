# Nepal Cereal Crop Yield Prediction

An academic machine learning project focused on analysing and predicting cereal crop yields across districts of Nepal using historical agricultural, climate, and fertilizer data.

## Project Overview

Agriculture plays an important role in Nepal's economy and food security. Crop production can be influenced by several factors, including cultivated land area, climate conditions, and fertilizer use.

This project explores the application of machine learning techniques to analyse historical agricultural data and predict the yields of three major cereal crops:

- Paddy
- Maize
- Wheat

The project uses historical agricultural records covering the 2013–2014 to 2023–2024 fiscal years, combined with district-level climate information and annual fertilizer data.

## Objectives

- Analyse historical cereal crop production and yield trends in Nepal.
- Explore relationships between agricultural, climate, and fertilizer-related features.
- Apply machine learning techniques to predict crop yields.
- Compare predicted and actual crop yields.
- Examine feature importance to understand the contribution of different input variables.
- Explore possible changes in crop yields through scenario analysis.
- Generate district-level crop yield predictions.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data processing and machine learning |
| Jupyter Notebook | Development and experimentation |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning and model evaluation |

## Dataset Description

The project uses three main categories of datasets.

### 1. Historical Agricultural Data

Annual agricultural datasets covering 11 fiscal years:

- 2013–2014
- 2014–2015
- 2015–2016
- 2016–2017
- 2017–2018
- 2018–2019
- 2019–2020
- 2020–2021
- 2021–2022
- 2022–2023
- 2023–2024

These datasets provide historical agricultural information used for analysing crop production and yield.

### 2. Climate Data

`Nepal_77districts_annual_climate.csv`

Contains annual climate-related information for Nepal's 77 districts.

### 3. Fertilizer Data

`fertilizer_annual_2013_2024.csv`

Contains annual fertilizer-related information used as an additional agricultural feature.

## Machine Learning Approach

The project follows a data analysis and machine learning workflow:

1. **Data Collection:** Load historical agricultural, climate, and fertilizer datasets.
2. **Data Preprocessing:** Clean, filter, transform, and prepare the datasets for analysis.
3. **Data Integration:** Combine relevant agricultural and environmental information.
4. **Exploratory Data Analysis:** Investigate crop yield distributions, trends, and feature relationships.
5. **Model Development:** Apply Random Forest Regression to predict crop yields.
6. **Model Evaluation:** Compare model predictions with actual yield values and examine prediction errors.
7. **Feature Importance:** Analyse the relative importance of input features.
8. **Scenario Analysis:** Explore potential yield changes under different input conditions.
9. **District-Level Prediction:** Generate crop yield predictions for individual districts.

## Visualizations and Outputs

The notebook generates several visual outputs and result files, including:

- Historical crop yield trends
- Correlation heatmaps
- Crop yield distribution plots
- Feature importance charts
- Predicted versus actual comparisons
- District-level yield predictions
- District-level prediction error visualizations
- Scenario analysis

## Project Structure

```text
nepal-cereal-crop-yield-prediction/
│
├── predictionmodel.ipynb
│
├── 2013-2014.csv
├── 2014-2015.csv
├── 2015-2016.csv
├── 2016-2017.csv
├── 2017-2018.csv
├── 2018-2019.csv
├── 2019-2020.csv
├── 2020-2021.csv
├── 2021-2022.csv
├── 2022-2023.csv
├── 2023-2024.csv
│
├── Nepal_77districts_annual_climate.csv
└── fertilizer_annual_2013_2024.csv
```

## Installation and Setup

### Prerequisites

- Python 3.9 or later
- Jupyter Notebook
- pip package manager

### 1. Clone the Repository

```bash
git clone https://github.com/FerojTamang/nepal-cereal-crop-yield-prediction.git
```

### 2. Navigate to the Project Directory

```bash
cd nepal-cereal-crop-yield-prediction
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the Project

Open `predictionmodel.ipynb` in Jupyter Notebook and execute the notebook cells in sequence.

**Note:** The notebook uses relative file paths for the input CSV datasets. Keep the notebook and its required datasets in the same project directory.

## Limitations

- Prediction quality depends on the completeness and reliability of the available historical datasets.
- Missing values, data filtering, and dataset integration may influence model results.
- Annual agricultural and climate records may not capture all local factors affecting crop production.
- Model predictions should be interpreted as estimates rather than guaranteed future crop yields.
- Further validation using independent and more recent agricultural data would be beneficial.

## Academic Context

This project was developed as part of an academic machine learning assignment for the Specialist module.

It provided practical experience in data preprocessing, exploratory data analysis, feature engineering, regression modelling, model evaluation, and agricultural data analysis.

## Author

**Feroj Tamang**

GitHub: [@FerojTamang](https://github.com/FerojTamang)

## Disclaimer

This project is intended for academic and educational purposes. Its predictions and analyses should not be treated as official agricultural forecasts or professional farming recommendations.
