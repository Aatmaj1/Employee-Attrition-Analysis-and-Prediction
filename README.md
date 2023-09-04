# Employee-Attrition-Analysis-and-Prediction

#### Description
This project undertakes the critical task of analyzing and predicting employee attrition, offering insights into the factors that influence employee turnover. Utilizing a dataset sourced from Kaggle, the project encompasses extensive data analysis and predictive modeling, aimed at helping organizations retain talent and foster a positive work environment.

#### Table of Contents
1. [Project Title](#project-title)
2. [Description](#description)
3. [Objective](#objective)
4. [Data Processing](#data-processing)
5. [Machine Learning Algorithms](#machine-learning-algorithms)
6. [Evaluation Criteria](#evaluation-criteria)
7. [Installation](#installation)
8. [Usage](#usage)
9. [Contributing](#contributing)
10. [License](#license)

#### Objective
The primary objective of this project is to analyze patterns and trends in employee data to predict attrition. By identifying the key indicators of employee turnover, organizations can implement strategies to enhance employee retention and satisfaction.

#### Data Processing
The project initiates with data ingestion using pandas, followed by exploratory data analysis (EDA) to visualize various data aspects and glean surface-level insights. Data preparation involves cleaning and transforming the data to facilitate effective modeling.

Exploratory Data Analysis (EDA) encompasses the utilization of diverse visualizations in order to visually identify patterns within the data. Feature reduction was performed by creating a correlation matrix to identify and delete features that displayed either excessive correlation or insufficient diversity.The dataset was partitioned into a train set and a test set, with 25% of the data being reserved for testing purposes.

#### Machine Learning Algorithms
A significant part of the project is dedicated to developing predictive models using decision tree algorithms. These models are calibrated to pinpoint potential instances of employee attrition with high precision.

Three models were trained in this study, namely the Decision Tree, Random Forest, and XGBoost. To ensure robustness and minimize bias, a five-fold cross-validation technique was employed throughout the training process. Additionally, the hyperparameters of the models were fine-tuned using the Grid Search Cross-Validation method. Each model was assigned a different hyperparameter space. The performance of the models was assessed using the weighted F1 score. The XGBoost algorithm demonstrated superior performance, with an accuracy rate of 86%.

#### Evaluation Criteria
The project employs specific evaluation criteria to assess the performance of the machine learning models, ensuring their reliability and accuracy in predicting employee attrition.

### Conclusion
The XGBoost feature importance curve unveiled that compensation, raise, and job satisfaction are the primary factors contributing to employee churn. Consequently, human resources departments should prioritize these elements in their efforts to enhance employee retention.

#### Installation
- Python 3.x
- Libraries: pandas, numpy, seaborn, matplotlib
- Dataset: [Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)) (exact link to be added)

#### Usage
To use this project, clone the repository and run the Jupyter Notebook in a suitable Python environment. Follow the instructions in the notebook for data analysis and predictive modeling.
