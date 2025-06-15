# car-price-prediction
Machine learning project to predict car prices based on features like brand, mileage, and engine power.

Dataset: car.csv

The dataset contains car specifications and the target variable 'price'.
It includes features like:
- fuel type
- aspiration
- car body
- engine size
- horsepower
- and more

Tools and Libraries:
- Python
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

Project Structure:
car-price-prediction/
- car.csv
- car_price_prediction.ipynb
- README.md
- requirements.txt

Models Compared:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors Regressor (Best)
- XGBoost Regressor

Evaluation Metrics:
- Mean Squared Error (MSE)
- R² Score

Final Model: K-Nearest Neighbors (KNN)
Performance:
- MSE: 1.802749e+07  
- R² Score: 0.771642

KNN gave the best performance out of all the models tested.

Final Plot:
A scatter plot was created to compare actual vs predicted prices using the best model (KNN).
![image](https://github.com/user-attachments/assets/1ea57d52-f030-4759-afba-bd7e71aacf2c)


How to Run:
1. Clone this repository
2. Make sure car.csv is in the same folder as the notebook
3. Open car_price_prediction.ipynb in Jupyter Notebook or Google Colab
4. Run all the cells in order

Author:
Talasila Navya Annapurna

GitHub: https://github.com/NavyaTalasila5

LinkedIn: https://www.linkedin.com/in/navya-talasila-3134a1325/
