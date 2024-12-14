**Descriptive and Predictive analysis on a sales dataset**

**Database Fields:**

order id: Unique identifier for each order.

category: Product category (e.g., Electronics, Furniture).

sales: Total sales amount for the order.

profit: Net profit associated with the order.

region: Geographic region where the sale occurred.

**Libraries Used**:

Core Libraries:

pandas: For data manipulation and analysis.

numpy: For numerical computations.

matplotlib and seaborn: For creating insightful visualizations.

Machine Learning Libraries:

scikit-learn:

Model training and evaluation (Linear Regression, Random Forest Regressor).

Preprocessing tools like StandardScaler and train-test split.





**Project Overview**:

This project is divided into two main components:

1. Descriptive Analysis

The descriptive analysis focuses on exploring historical data to extract insights about sales and profit trends.

It answers critical business questions, such as

Which regions or categories perform the best?

What is the overall profit margin?

Visualization Techniques: Bar charts, scatter plots, and summary tables are used for data exploration.



3. Predictive Analysis

The predictive analysis uses machine learning models to forecast profit based on features like sales, category, and region.

This analysis involves:

Data Encoding: One-hot encoding for categorical variables.

Feature Scaling: StandardScaler to normalize numerical data for better model performance.

Modeling Techniques:

Linear Regression: Provides a baseline regression model.

Random Forest Regressor: Captures non-linear relationships and interactions between features.

Performance Metrics: Models are evaluated using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score



**Workflow**":

Data Exploration:

Analyzed dataset for structure, missing values, and summary statistics.

Visualized sales and profit distributions by category and region.


Feature Engineering:

Encoded category and region fields using one-hot encoding.

Scaled numerical fields (sales) using StandardScaler.


Model Training and Evaluation:

Split the dataset into training (80%) and testing (20%) subsets.

Trained models to predict profit.

Evaluated model performance using error metrics.


Visualizations:

Compared actual vs predicted values for profit.

Highlighted relationships between sales and profit.





