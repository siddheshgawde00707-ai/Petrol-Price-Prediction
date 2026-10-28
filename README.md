<img width="476" height="287" alt="Petrol_price_prediction" src="https://github.com/user-attachments/assets/29ad0b20-4002-48b1-a66d-5bab73181d66" />

Here is a 10-point summary of the project based on the provided data:

* **Project Focus**: It explores the macroeconomic factors, tax structures, and state-wise variations influencing petrol prices in India.


* **Dataset Scale**: The dataset contains 10,345 records distributed across 8 distinct columns.


* **Target Variable**: The primary target variable being analyzed is `Petrol_Price_INR_per_Litre`.


* **Key Features**: The dataset includes variables such as Date, State, Crude Oil Price, Exchange Rate, Central/State Taxes, and Refining/Transport costs.


* **Data Inspection**: Initial inspection utilized `pandas` to review data types, non-null counts, and statistical summaries (`df.info()` and `df.describe()`).


* **Data Cleaning**: Data cleaning involved checking for duplicate rows and imputing missing values with the median for crude oil prices and state taxes.


* **Correlation Analysis**: Exploratory Data Analysis (EDA) evaluated feature relationships using numeric-only correlation matrices.


* **Data Visualization**: Data distributions were visualized effectively using multi-plot histograms (`plt.hist`).


* **Outlier Detection**: Outliers and data spreads were identified and analyzed using box plots via `matplotlib` and `seaborn`.


* **Tech Stack**: The project is built using Python alongside data science libraries like Pandas, NumPy, Matplotlib, and Seaborn.
