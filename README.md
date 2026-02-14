# Bengaluru House Price Prediction

This project is a machine learning notebook that analyzes and predicts house prices in Bengaluru, India. It takes raw housing data, performs extensive data cleaning and exploratory data analysis (EDA), and builds a predictive model to estimate property prices based on various features.

## 📌 Project Overview

The real estate market in Bengaluru is dynamic, with prices influenced by location, square footage, number of bedrooms (BHK), and other amenities. This project aims to:
1.  **Clean and Preprocess Data**: Handle missing values and remove irrelevant columns (e.g., area type, society).
2.  **Exploratory Data Analysis (EDA)**: Visualize price distributions and identify popular locations.
3.  **Feature Engineering**: Extract practical features like BHK (Bedrooms, Hall, Kitchen) from raw text.
4.  **Model Building**: Train a Linear Regression model to predict house prices.

## 🔧 Technologies Used

* **Python 3.x**
* **Pandas**: Data manipulation and analysis.
* **NumPy**: Numerical computing.
* **Matplotlib & Seaborn**: Data visualization.
* **Scikit-Learn**: Machine learning (Linear Regression, Train-Test Split, Cross-validation).

## 📂 Dataset

The project uses the **Bengaluru House Data** (typically available on Kaggle).
* **Input features included**: Location, Size (BHK), Total Square Footage, Bathrooms, etc.
* **Target variable**: Price (in Lakhs).

## 📊 Key Analysis Steps

1.  **Data Cleaning**:
    * Dropped columns with high cardinality or low relevance: `area_type`, `society`, `balcony`, `availability`.
    * Handled missing values by dropping null rows.
2.  **Feature Engineering**:
    * Converted the `size` column (e.g., "2 BHK", "4 Bedroom") into a numeric `bhk` column.
3.  **Visualizations**:
    * **Top 10 Locations**: Bar chart showing areas with the most listings.
    * **Price Distribution**: Histogram showing the spread of property prices.
    * **BHK vs Price**: Boxplot analysis to see price outliers across different room configurations.

## 🚀 How to Run

1.  Ensure you have Python installed.
2.  Install the required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  Download the `Bengaluru_House_Data.csv` file.
4.  Open `benaglore-house-prices.ipynb` in Jupyter Notebook or VS Code.
5.  Run the cells sequentially to see the analysis and predictions.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
