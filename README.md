# Preprocessing & Imputations Practice

This project contains a Jupyter notebook for practicing data preprocessing techniques using the [OpenML Airlines Dataset (ID: 42721)](https://www.openml.org/d/42721).

The focus is on:

- Cleaning data
- Handling missing values
- Converting time formats (HHMM to minutes)
- Feature engineering (rush hour, weekend, seasons)
- Label encoding of categorical variables
- Outlier removal
- Training a Random Forest regression model to predict flight departure delays

## 📁 File Structure

- `imputations_tutorials.ipynb`: Main notebook with all preprocessing and modeling steps
- `rf_depdelay_model.joblib`: (Optional) saved trained model for reuse

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/imputations-practice.git
   cd imputations-practice
