# Taxi Tip Prediction

This project aims to predict the **tip amount** for New York City taxi rides using a **Decision Tree Regressor**. The dataset is sourced from the **Yellow Taxi Trip Records** and contains detailed information on trip characteristics.

## Project Overview

The goal of this project is to:

- Perform **data preprocessing** and **feature engineering** on the taxi dataset.
- Analyze key variables and their relationship with **tip amount**.
- Build and evaluate a **Decision Tree Regressor** model to predict the tip amount.

## Dataset

The dataset is sourced from IBM's open data repository and contains the following columns:

- **fare_amount**: The amount paid for the trip.
- **tip_amount**: The gratuity given to the driver (target variable).
- **tpep_pickup_datetime**: The pickup timestamp.
- **tpep_dropoff_datetime**: The dropoff timestamp.
- **VendorID**: ID of the taxi service provider.
- **RatecodeID**: Rate category for the trip.
- **payment_type**: Payment method (e.g., cash or card).
- **PULocationID** and **DOLocationID**: Pickup and drop-off zones.
- Additional fields related to trip metrics.

## Requirements

Ensure you have the following packages installed in your Python environment:

```bash
numpy
pandas
matplotlib
seaborn
scikit-learn
```

To install missing packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Project Structure

```
Machine-Learning-Projects/
├── Taxi-Tip-Prediction/
    ├── taxi_tip_prediction.py  # Main script for model training and evaluation
    └── README.md               # Project documentation (this file)
```

## Code Walkthrough

1. **Import Libraries**
   - Core libraries: `numpy`, `pandas`
   - Visualization: `matplotlib`, `seaborn`
   - Machine Learning: `scikit-learn`

2. **Load and Sample Data**
   - Data is loaded from an external source and limited to 100,000 rows for efficiency.

3. **Data Exploration & Cleaning**
   - Handle outliers by filtering unreasonable `fare_amount` and `tip_amount` values.
   - Remove rows where `tip_amount` is zero or greater than the `fare_amount`.

4. **Feature Engineering**
   - Extract temporal features (hour and day of the week) from datetime columns.
   - Create dummy variables for categorical columns (e.g., `payment_type`, `RatecodeID`).

5. **Normalize & Split Data**
   - Normalize features using **L1 normalization**.
   - Split the dataset into training (70%) and testing (30%).

6. **Model Training**
   - Use a **Decision Tree Regressor** with a maximum depth of 8.
   - Measure model training time.

7. **Model Evaluation**
   - Evaluate model performance using **Mean Squared Error (MSE)** and **R-squared (R2)**.

## How to Run the Project

Ensure your working directory is `Taxi-Tip-Prediction` and execute the script:

```bash
python taxi_tip_prediction.py
```

## Outputs

The script prints:

- Model training time
- Mean Squared Error (MSE)
- R-squared (R2) score

## Example Output

```
Model training time: 8.42 seconds
Mean Squared Error: 1.25
R2 Score: 0.72
```

## Future Improvements

- **Model Optimization**: Fine-tune hyperparameters using `GridSearchCV`.
- **Feature Engineering**: Incorporate geographic data (e.g., distance calculation).
- **Advanced Models**: Explore Gradient Boosting or Random Forest for better performance.

## License

This project is licensed under the **MIT License**.

## Author

[Danial Hosseinpour]  
Feel free to reach out if you have questions or suggestions!
