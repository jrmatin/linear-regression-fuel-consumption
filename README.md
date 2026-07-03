# Linear Regression - Fuel Consumption CO2 Prediction

## Project Overview
This project implements a simple **Linear Regression** model to predict CO2 emissions of vehicles based on their engine size. The dataset used is `FuelConsumption.csv`.

## Dataset
- **Features:** ENGINESIZE, CYLINDERS, FUELCONSUMPTION_COMB
- **Target:** CO2EMISSIONS

## Technologies Used
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## Model Performance
The model evaluates performance using:
- **MAE** (Mean Absolute Error)
- **MSE** (Mean Squared Error)
- **R2-score** (Coefficient of Determination)

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/jrmatin/linear-regression-fuel-consumption.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python linear-regression.py
   ```

## Sample Output
After running the script, you should see output similar to this:
```
Coefficients: [[9.78]]
Intercept: [125.34]
MAE: 24.56
MSE: 987.34
R2-score: 0.76
```
*(Note: Actual values may vary slightly due to random data splitting.)*

## Visualization
The script displays a scatter plot showing the relationship between engine size and CO2 emissions, along with the fitted regression line.

## Project Structure
```
├── linear-regression.py    # Main script
├── FuelConsumption.csv     # Dataset
├── requirements.txt        # Python dependencies
└── README.md              # Project documentation
```
