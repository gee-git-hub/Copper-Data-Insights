# Industrial Copper Modeling

Application Link: https://yabase-copper-modeling.streamlit.app/

## Introduction

The **Industrial Copper Modeling** project aims to predict both the selling price and transaction status (won or lost) in the industrial copper market using machine learning techniques. This involves exploring the dataset, performing data cleaning and preprocessing, and applying regression and classification algorithms to develop predictive models.

## Dataset

The dataset contains detailed information on industrial copper transactions, including:

- **id**: Unique identifier for each transaction or item.
- **item_date**: Date of the transaction or item recording.
- **quantity tons**: Quantity of the item in tons.
- **customer**: Name or identifier of the customer.
- **country**: Country associated with the customer.
- **status**: Status of the transaction (e.g., Draft, Won).
- **item type**: Category of the items sold or produced.
- **application**: Specific use or application of the items.
- **thickness**: Thickness of the items.
- **width**: Width of the items.
- **material_ref**: Reference for the material used.
- **product_ref**: Reference for the specific product.
- **delivery date**: Expected or actual delivery date.
- **selling_price**: Price at which the items are sold.

## Regression Model Details

The regression model predicts the selling price of copper items. Key considerations include:

- **Data Normalization**: Adjusting scales for consistency.
- **Outlier Detection**: Identifying and handling anomalies.
- **Tree-Based Models**: Utilizing decision trees and ensemble methods.

## Classification Model Details

The classification model predicts the transaction status (Won or Lost). Techniques include:

- **Logistic Regression**
- **Support Vector Machines (SVM)**
- **Random Forests**

## Learn from the Project

- **Exploring Skewness and Outliers**: Analyze variable distributions and identify data issues.
- **Data Transformation and Cleaning**: Prepare data by handling missing values, encoding categorical variables, and scaling features.
- **Machine Learning Regression Algorithms**: Evaluate algorithms like linear regression, decision trees, random forests, and gradient boosting.
- **Machine Learning Classification Algorithms**: Assess algorithms such as logistic regression, SVM, and random forests for status prediction.
- **Evaluation and Model Selection**: Use metrics such as Mean Squared Error (MSE), accuracy, precision, and recall to evaluate model performance and select the best models.

## Methodology

1. **Data Loading**: Import the dataset using pandas and explore its structure.
2. **Data Cleaning and Preprocessing**: Address missing values, remove outliers, and transform data for analysis.
3. **Exploratory Data Analysis (EDA)**: Use pandas, matplotlib, and seaborn for data exploration and visualization.
4. **Machine Learning Regression**: Train and evaluate regression models to predict selling prices.
5. **Machine Learning Classification**: Train and evaluate classification models to predict transaction status.
6. **Documentation**: Summarize the analysis, preprocessing steps, machine learning algorithms used, and their performance. Include visualizations and interpretations.

## Conclusion

The **Industrial Copper Modeling** project uses machine learning techniques to predict selling prices and transaction statuses in the copper market. This provides actionable insights and supports informed decision-making.
