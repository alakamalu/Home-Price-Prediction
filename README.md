# Home Price Prediction

## Overview
This project predicts house prices using machine learning techniques. It utilizes various features such as location, size, number of rooms, and other relevant factors to estimate the price of a house.

## Dataset
- **Source:** Kaggle
- **Features:**
  - Square Footage
  - Number of Bedrooms
  - Number of Bathrooms
  - Location
  - Year Built
  - Other relevant factors
- **Target Variable:** House Price

## Machine Learning Model
- **Algorithm Used:** Linear Regression
- **Preprocessing Steps:**
  - Handling missing values
  - Feature scaling
  - Encoding categorical variables

## Installation & Usage
### Prerequisites
Ensure you have Python and the required libraries installed

### Running the Project
Run the Jupyter Notebook to train the model:

```bash
jupyter notebook HOME_PRICE_PREDICTION.ipynb
```

### Example Prediction
```python
# Example usage
model.predict(['1st Phase JP Nagar',1000,2,2])  
```

## 📈 Results
- **Feature Importance:** location, sqft, bath, bhk


## 🤝 Contributing
Feel free to fork the repo, create a new branch, and submit a pull request.

