# SCT_ML_1
🏠 House Price Prediction
This project predicts house prices using the Kaggle House Prices - Advanced Regression Techniques dataset.

📂 Files in this repository
house_price_prediction.ipynb → Jupyter/Colab notebook with all code and steps.
house_price_model.pkl → Trained Linear Regression model (ready to load and use).
README.md → Project description.
📊 Steps followed
Downloaded dataset from Kaggle.
Loaded data into Pandas.
Selected key features: GrLivArea, BedroomAbvGr, FullBath.
Split data into training (80%) and testing (20%).
Trained a Linear Regression model using scikit-learn.
Evaluated using R² Score and RMSE.
Visualized Actual vs Predicted prices.
Saved trained model using Joblib.
🚀 How to use
Clone/download this repository.
Install dependencies:
pip install pandas scikit-learn matplotlib joblib
How to Run
Open house_prices_linear_regression.ipynb in Google Colab.
Ensure house_price_model.pkl is in the same folder.
Run all cells to see predictions.
