# PM2.5 Predictor

Welcome to the PM2.5 Predictor project's GitHub repository! This project offers a nifty web application that predicts PM2.5 (particulate matter 2.5 micrometers or smaller) concentrations based on environmental factors like temperature, pressure, rain, and wind speed. The magic behind the scenes comes from a cleverly trained Random Forest Regression model.

## Quick Start
Follow these steps to run the PM2.5 Predictor on your local machine:

1. Clone the Repository: Grab your copy of the project by running this command in your terminal:

```python
git clone https://github.com/your-username/pm25-predictor.git
```

2. Navigate to the Project Directory: Jump into the project folder using:

```python
cd pm25-predictor
```

3. Set Up the Environment: Create a virtual environment and install the required packages:

```python
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

4. Run the App: Fire up the Flask application with:

```python
python app.py
```

5. Access the App: Open your web browser and go to http://127.0.0.1:5000 to see the PM2.5 Predictor in action.

## How to Use
1. Input Parameters: Enter values for Temperature, Pressure, Rain, and Wind Speed in the designated fields.

2. Get the Prediction: Click the "Predict" button, and the app will dazzle you with its PM2.5 prediction prowess.

## Web Interface

Under the Hood: Model Explanation
The PM2.5 prediction magic is powered by a Random Forest Regressor—a fancy name for an ensemble of decision trees. Each tree chips in with its own prediction, and the final PM2.5 forecast is a smart blend of these individual insights. The model learns from historical data to make accurate predictions.

## Important Notes
The train.csv dataset provided is used for training purposes. For real-world applications, make sure your data is properly prepped and cleaned for optimal results.
This app serves as an educational showcase. Real-world PM2.5 predictions could require more sophisticated preprocessing and feature engineering.

## Get Involved
Contributions are more than welcome! If you spot issues or have ideas to make the project even cooler, feel free to open a pull request.
