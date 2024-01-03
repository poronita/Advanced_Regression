# <span style="color: #1976D2;">Advanced Regression Analysis</span>

## <span style="color: #1E88E5;">Introduction</span>

Surprise Housing, a US-based real estate company, is venturing into the Australian market using data analytics to identify lucrative investment opportunities. This comprehensive dataset from Australian property sales is utilized to construct a robust regression model. The goal is to predict the true value of potential properties, aiding in decision-making for property acquisitions and understanding variables influencing house prices.

The key questions guiding this analysis include identifying influential predictive variables and determining optimal lambda values for ridge and lasso regression. This data-driven approach empowers Surprise Housing to make informed investment decisions in the Australian real estate market.

## <span style="color: #1E88E5;">Business Goal</span>

Develop a predictive model for house prices to provide insights into the relationship between prices and various factors. This model assists in strategic decision-making, optimizing investment strategy, and navigating the complexities of the real estate market.

## <span style="color: #1E88E5;">Downloads</span>

- [Dataset](https://ml-course3-upgrad.s3.amazonaws.com/Assignment_+Advanced+Regression/train.csv)

## <span style="color: #1E88E5;">Data Definition</span>

Details of variables are provided in the [data description file](https://cdn.upgrad.com/UpGrad/temp/87f67e28-c47e-4725-ae3c-111142c7eaba/data_description.txt).

## <span style="color: #1E88E5;">Analysis</span>

The exploration begins with doubling alpha values in ridge and lasso regression, investigating shifts in model dynamics and predictor variable importance. The decision-making process between ridge and lasso, optimal lambda values, constructing models without crucial predictors, and ensuring model robustness and generalizability are addressed.

### Technologies Used

- **Programming Languages:**
  - Python

- **Libraries and Frameworks:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn

- **Data Handling:**
  - Data loading using Pandas
  - Handling missing values with SimpleImputer
  - Scaling numerical features with StandardScaler

- **Data Visualization:**
  - Matplotlib and Seaborn for creating various plots and visualizations

- **Machine Learning Models:**
  - Ridge and Lasso regression models implemented using Scikit-learn

- **Model Evaluation:**
  - Metrics such as Mean Squared Error (MSE), R-squared (R²), and Mean Absolute Error (MAE) for evaluating model performance

- **Data Preprocessing:**
  - OneHotEncoder for handling categorical variables
  - GridSearchCV for hyperparameter tuning

- **Data Analysis:**
  - Exploratory Data Analysis (EDA) techniques, including correlation matrix heatmap and box plots

- **Data Pipeline:**
  - Utilization of Scikit-learn's Pipeline for streamlined and reproducible model building


Detailed analysis can be found [here](https://github.com/poronita/Advanced_Regression/blob/main/Assignment_Analyis%20.pdf). <br>
For the Python code, click [here](https://github.com/poronita/Advanced_Regression/blob/main/Assignment%20Regression%20Part%202.ipynb).

## <span style="color: #1E88E5;">Python Notebook</span>

Full Code for the Analysis - [Click Here](https://github.com/poronita/Advanced_Regression/blob/main/Advanced%20Regression%20Notebook.ipynb)

## <span style="color: #1E88E5;"> Acknowledgement </span>

The data used in this analysis was generously provided by Upgrade Academy. I extend my sincere gratitude to the dedicated faculty members at Upgrade Academy for their invaluable support and guidance throughout the analysis process. Their expertise and commitment significantly contributed to the success of this project.

