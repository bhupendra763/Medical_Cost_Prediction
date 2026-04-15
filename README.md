<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/c63ab991-a91f-49a2-8b43-4575e439a007" />


# Medical_Cost_Prediction
Medical Insurance Cost Prediction project using machine learning to estimate insurance charges based on age, BMI, smoking status, and other health factors. Built with Python, data preprocessing, feature engineering, and Linear Regression with ~88% accuracy.
# Medical Insurance Cost Prediction using Machine Learning

This project predicts medical insurance charges based on personal and health-related information such as age, BMI, smoking status, gender, number of children, and region.

## Project Objective

To build a machine learning model that can accurately predict medical insurance costs and help understand the factors affecting charges.

## Dataset

* Dataset Name: Insurance Dataset
* Features:

  * Age
  * Sex
  * BMI
  * Children
  * Smoker
  * Region
* Target:

  * Charges (Insurance Cost)

## Technologies Used

* Python
* Jupyter Notebook
* pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn

## Machine Learning Workflow

1. Data collection and loading
2. Data cleaning and preprocessing
3. Handling missing values and duplicates
4. Encoding categorical features
5. Feature engineering
6. Train-test split
7. Model training using Linear Regression
8. Model evaluation using:

   * R² Score
   * Mean Absolute Error (MAE)
   * Root Mean Squared Error (RMSE)

## Model Performance

* R² Score: ~0.88
* MAE: ~2831

This means the model predicts insurance charges with good accuracy and low average error.

## Key Insights

* Smoking significantly increases insurance charges.
* Higher BMI can increase charges.
* Age also impacts insurance cost.

## Project Files

* `insurance_data.ipynb` – complete notebook
* `insurance.csv` – dataset
* `README.md` – project documentation

## How to Run

1. Clone the repository:

   ```bash
   git clone <your-repo-link>
   ```

2. Open the notebook:

   ```bash
   jupyter notebook insurance_data.ipynb
   ```

3. Run all cells.

## Future Improvements

* Try advanced models like Random Forest Regressor
* Hyperparameter tuning
* Deploy as web app
* Create Deep Learning Model 

## Author

Bhupendra Singh Gour
