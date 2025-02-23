# Customer_Churn_Prediction

## Overview
This project focuses on predicting customer churn using machine learning techniques. The goal is to identify customers who are likely to leave a service, enabling proactive retention strategies.

## Dataset
- **Source**: `churn_modelling.csv`
- **Features**: Various customer attributes such as demographics, account activity, and transaction details.
- **Target**: Churn (1 = Customer left, 0 = Customer stayed)

## Model
- **Approach**: Artificial Neural Network (ANN)
- **Performance**:
  - Accuracy: **85.60%**
  - Additional Metrics: Precision, Recall, F1-score (to be analyzed further)

## How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```sh
   python train_model.py
   ```

## Future Improvements
- Hyperparameter tuning for better accuracy.
- Experimenting with additional models (e.g., Random Forest, XGBoost).
- Feature engineering to enhance predictive power.
- Deploying the model using Flask or FastAPI.

## Contributing
Feel free to fork this repository and submit pull requests if you'd like to improve the model or add new features!

## License
This project is licensed under the MIT License.

---
_If you find this project useful, give it a ⭐ on GitHub!_

