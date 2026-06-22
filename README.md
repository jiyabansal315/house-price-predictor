# house-price-predictor
Machine Learning model for predicting house prices using Python and Scikit-Learn
# House Price Predictor

A Machine Learning project that predicts house prices using Linear Regression and housing features such as area, bedrooms, bathrooms, parking, furnishing status, and amenities.

## Dataset
The dataset contains 545 housing records with features including:
- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road Access
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

Target variable:
- Price

## Project Workflow
1. Load and clean housing data
2. Split data into training and testing sets
3. Encode categorical features
4. Train a Linear Regression model
5. Evaluate performance using:
   - Mean Squared Error (MSE)
   - R² Score

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn

## Repository Structure

house-price-predictor/
│
├── Housing Data.csv
├── house_price.ipynb
├── README.md
├── requirements.txt
└── .gitignore

## How to Run

1. Clone the repository
2. Install dependencies

pip install -r requirements.txt

3. Open the notebook

jupyter notebook house_price.ipynb

## Future Improvements
- Add feature scaling
- Compare multiple ML algorithms
- Build a Streamlit web app
- Deploy the model online

## Author
Jiya Bansal

