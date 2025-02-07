# loan-db-Preprocessing
This project demonstrates how to preprocess loan data, focusing on cleaning, transforming, and preparing the data for further analysis or modelling.
We performed preprocessing on a loan dataset containing various columns such as loan type, loan amount, and loan date.



Step 1: Initial Data Exploration



First, we examined the entire dataset, identifying its columns, the number of records, and the data types of each column.



Step 2: Handling Missing Data



Next, we checked for missing values and handled them accordingly.



Step 3: Encoding Categorical Data



We identified columns containing categorical data and selected the best method for encoding them. In this case, we used one-hot encoding to convert categorical variables into numerical format.



Step 4: Processing Date Columns



For date-related columns, instead of using a single timestamp, we split them into multiple features (e.g., year, month, day) to extract more numerical information.



Step 5: Handling Outliers in Numerical Data



We detected outliers in numerical columns using Z-score and Box Plot (IQR method) and replaced the extreme values accordingly.



Step 6: Normalizing Interest Rate Data



For numerical data related to interest rates, we applied normalization techniques to transform the distribution. Specifically, we used log transformation (log-scaling) and square root (SQRT) transformation to achieve a more normalized distribution.


