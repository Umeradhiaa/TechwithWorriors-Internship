# Data Analysis and Forecasting - Tasks Overview

## Introduction

This repository contains Python scripts and Jupyter notebook code for various data analysis, visualization, and forecasting tasks. These tasks were completed as part of an educational initiative to develop hands-on experience with data manipulation, statistical analysis, and predictive modeling.

---

## Tasks Breakdown

### Task 1: Data Cleaning and Preprocessing

#### Description:
Performed essential data cleaning operations on the `tested.csv` dataset to ensure its readiness for further analysis.

#### Highlights:
- Identified and imputed missing values for features like `Age` and `Fare`.
- Removed irrelevant columns (e.g., `Cabin`) to streamline analysis.
- Verified dataset consistency with descriptive statistics and value counts.
- Exported the cleaned dataset to `cleaned_tested.csv` for downstream tasks.

#### Tools and Libraries:
- `pandas`

---

### Task 2: Data Visualization and Exploratory Analysis

#### Description:
Visualized demographic distributions and survival rates using the `tested.csv` dataset.

#### Highlights:
- Created pie charts for gender distribution and survival rates.
- Analyzed passenger embarkation and class distributions with bar charts.
- Used seaborn and matplotlib for insightful visualizations.

#### Tools and Libraries:
- `pandas`, `matplotlib`, `seaborn`

---

### Task 3: Time Series Analysis and Forecasting

#### Description:
Analyzed sales data (`mock_kaggle.csv`) to identify trends and forecast future values using ARIMA.

#### Highlights:
- Preprocessed sales data to handle missing values and sort by date.
- Split data into training and testing sets for model evaluation.
- Built and trained an ARIMA model for forecasting.
- Evaluated model performance using Mean Squared Error (MSE).
- Visualized trends, residuals, and ACF/PACF plots for model diagnostics.

#### Tools and Libraries:
- `pandas`, `matplotlib`, `statsmodels`, `sklearn`

---

## Repository Structure

- **Task_1_Cleaning_Preprocessing.py**: Script for data cleaning and preprocessing.
- **Task_2_Visualization.py**: Script for generating visualizations and exploratory analysis.
- **Task_3_ARIMA_Forecasting.py**: Script for time series analysis and forecasting.
- **Data**: Folder containing datasets (`tested.csv`, `mock_kaggle.csv`).

---

## Key Learnings

1. Effective handling of missing and inconsistent data.
2. Use of visualization tools to uncover insights from raw data.
3. Application of ARIMA models for time series forecasting.
4. Evaluation and diagnostics of predictive models using statistical methods.

---

## Future Enhancements

- Explore alternative forecasting models (e.g., Prophet, LSTM).
- Automate data cleaning and preprocessing pipelines.
- Develop an interactive dashboard for visualization and forecasting results.

---

## Getting Started

### Prerequisites
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `sklearn`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repo-name.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
Run the desired script using Python:
```bash
python Task_1_Cleaning_Preprocessing.py
```

---

## Acknowledgments

Special thanks to mentors and peers for their guidance and support in completing these tasks.

