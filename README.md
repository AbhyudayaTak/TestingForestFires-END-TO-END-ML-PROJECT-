# Algerian Forest Fires Prediction - End-to-End ML Project

## Overview
This project is an end-to-end machine learning solution for predicting the likelihood of forest fires in Algeria. It covers the complete ML workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, model training, and deployment using a web application.

## Project Structure
```
application.py                # Main Flask application
requirements.txt              # Python dependencies
README.md                     # Project documentation
models/
    ridge_model.pkl           # Trained Ridge Regression model
    scaler.pkl                # Scaler used for preprocessing
notebooks/
    EDA&FE.ipynb   # EDA & Feature Engineering
    ModelTraining.ipynb                     # Model Training
    Algerian_forest_fires_cleaned_dataset.csv    # Cleaned dataset
    Algerian_forest_fires_dataset_UPDATE.csv     # Raw/updated dataset
templates/
    home.html                 # Home page template
    index.html                # Main page template
```

## Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation (Ridge Regression)
- Model serialization (pickle)
- Web application for predictions (Flask)

## Setup Instructions
1. **Clone the repository**
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the application**
   ```bash
   python application.py
   ```
4. **Access the web app**
   Open your browser and go to `http://localhost:5000`

## Usage
- Use the web interface to input environmental features and get fire risk predictions.
- Explore the notebooks in the `notebooks/` folder for EDA and model training details.

## Data
- The dataset is sourced from the Algerian Forest Fires dataset, available in the `notebooks/` folder.

## Model
- The trained model (`ridge_model.pkl`) and scaler (`scaler.pkl`) are stored in the `models/` directory.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is for educational purposes.
