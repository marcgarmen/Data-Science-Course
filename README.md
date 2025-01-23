# Data-Science-Course
### Project Description: Data Handling and Predictive Modeling

This project focused on managing, exploring, and analyzing a dataset to understand its characteristics and build a predictive model. The process followed key data handling steps, utilizing Python as the primary programming language, supported by specialized libraries and tools. 

#### **Tools Used**
1. **Python Libraries:**
   - **Pandas**: For data manipulation, exploration, and cleaning.
   - **Scikit-learn**: For splitting datasets, building a linear regression model, and evaluating its performance.
   - **Matplotlib** and **NumPy**: For data visualization and creating scatter plots to compare real and predicted values.
2. **Development Environment**: Google Colab for collaborative coding and streamlined execution of Python scripts.
3. **Data Source**: An Excel file containing structured data, loaded into a Pandas DataFrame for analysis.

#### **Key Steps and Workflows**
1. **Data Loading and Exploration:**
   - Data was loaded from an Excel file into a Pandas DataFrame.
   - Functions like `head()`, `shape`, `columns`, and `info()` were used to explore the dataset's structure, including row and column counts, column names, and data types.

2. **Data Cleaning:**
   - Missing values were identified using `isnull().sum()` and removed with `dropna()`.
   - The final dataset was validated to ensure no null values remained.

3. **Feature Selection and Transformation:**
   - Relevant columns were selected using the `.iloc[]` method.
   - Independent (`x`) and dependent (`y`) variables were defined, with features like `Presupuesto`, `Tiempo invertido`, and `Tipo` included in the analysis.

4. **Dataset Splitting:**
   - The dataset was divided into training (80%) and testing (20%) sets using the `train_test_split` function from Scikit-learn.

5. **Modeling:**
   - A linear regression model was created using Scikit-learn's `LinearRegression` class.
   - The model was trained on the training set using the `fit()` method and coefficients were extracted to understand the impact of each feature on the output.

6. **Model Evaluation:**
   - Predictions were generated with the `predict()` method.
   - Residuals (differences between real and predicted values) were calculated, and a \(R^2\) score of 0.94 demonstrated a high level of accuracy.

7. **Visualization:**
   - Scatter plots compared real and predicted values, providing a visual assessment of the model’s performance.
   - Minimal distances between the points indicated reliable predictions for most observations.

#### **Automated Workflows**
- Automated steps included splitting the data, training the model, generating predictions, and calculating residuals with reusable functions and methods.
- The workflow also ensured seamless data cleaning, feature selection, and statistical validation with minimal manual intervention, leveraging built-in functionalities of Pandas and Scikit-learn.

#### **Key Outcomes**
- Successfully cleaned and prepared the dataset for analysis.
- Built a multiple linear regression model that explained **94% of the variance** in the target variable (`Costo`).
- Identified key features impacting the target variable, providing actionable insights.
- Delivered visualizations to communicate model accuracy and residual behavior effectively.

This project demonstrates a robust data handling pipeline with automated workflows, yielding accurate predictive capabilities and data-driven insights. It provides a scalable framework for similar data analysis tasks in the future.
