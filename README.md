# 📚 Book Sales — Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a Book Sales dataset to understand sales patterns, customer preferences, book performance, and other factors that influence book sales.

The analysis uses **Python, Pandas, NumPy, Matplotlib, and Seaborn** to clean, explore, analyze, and visualize the data.

The main goal is to extract meaningful insights from the dataset and present them through clear visualizations and statistical analysis.

---

## 🎯 Objectives

The key objectives of this project are:

- 🔍 Understand the structure and characteristics of the dataset
- 🧹 Clean and preprocess the data
- 📊 Perform descriptive statistical analysis
- 📈 Identify sales trends and patterns
- 📚 Analyze the performance of books
- ⭐ Explore ratings and their relationship with sales
- 👤 Analyze authors and publishers
- 💰 Identify high-performing books/categories
- 📉 Detect missing values and potential outliers
- 📊 Create meaningful data visualizations
- 💡 Generate actionable insights from the data

---

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization

---

## 📂 Project Structure

```text
Book-Sales-EDA/
│
├── 📓 Book_Sales_EDA.ipynb
├── 📄 README.md
├── 📊 book_sales.csv
└── 📁 images/
    └── visualizations/
```
## 🔎 EDA Process
The project follows these major steps:
1. Data Loading
The dataset is imported using Pandas.

import pandas as pd

df = pd.read_csv("book_sales.csv")

2. Data Understanding
Initial exploration includes:
df.head()
df.tail()
df.shape
df.info()
df.describe()
df.columns

This helps understand the dataset's:
- Number of rows and columns
- Data types
- Numerical statistics
- Available variables

3. Data Cleaning
The dataset is checked for:
- Missing values
- Duplicate records
- Incorrect data types
- Inconsistent values
- Unnecessary columns
- Outliers
Example:

df.isnull().sum()

Check duplicate records:

df.duplicated().sum()

4. Exploratory Data Analysis
Different questions are explored through statistical analysis and visualization.
Examples include:
- Which books have the highest sales?
- Which authors have the highest sales?
- What are the most popular genres?
- How are book ratings distributed?
- Is there a relationship between ratings and sales?
- Which publishers have the most books?
- What factors appear to be associated with higher sales?

## 📊 Visualizations
The project includes different types of visualizations such as:
- 📊 Bar charts
- 📈 Line charts
- 🥧 Pie charts
- 📦 Box plots
- 🔵 Scatter plots
- 🔥 Heatmaps
- 📊 Histograms
Example:
import seaborn as sns
import matplotlib.pyplot as plt

sns.histplot(df["Sales"])
plt.title("Distribution of Book Sales")
plt.show()

##💡 Key Insights
The analysis aims to identify insights such as:
- Books with the highest sales volumes
- Top-performing authors
- Popular book categories/genres
- Distribution of book ratings
- Relationship between ratings and sales
- Publishers with significant representation
- Sales distribution and potential outliers
Note: The exact findings depend on the dataset used and are documented in the Jupyter Notebook.

## 📈 Skills Demonstrated
This project demonstrates practical knowledge of:
- Exploratory Data Analysis
- Data Cleaning
- Data Preprocessing
- Pandas
- NumPy
- Data Visualization
- Matplotlib
- Seaborn
- Statistical Analysis
- Data Interpretation
- Insight Generation

## 🚀 How to Run the Project

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/Book-Sales-EDA.git

2. Navigate to the project folder

cd Book-Sales-EDA

3. Install required libraries

pip install pandas numpy matplotlib seaborn jupyter

4. Launch Jupyter Notebook

jupyter notebook

5. Open

Book_Sales_EDA.ipynb

Run the notebook cells to reproduce the analysis.

## 📦 Dataset
The project uses a Book Sales dataset containing information related to books and their sales/performance.
The dataset may contain variables such as:
- Book Title
- Author
- Genre/Category
- Publisher
- Sales
- Rating
- Price
- Publication Year
The exact columns depend on the dataset used in this project.

## 📌 Future Improvements
Possible improvements include:
- Build an interactive dashboard using Power BI or Tableau
- Perform advanced statistical analysis
- Apply machine learning to predict book sales
- Build a book recommendation system
- Analyze sales trends over time
- Add more datasets for comparison
- Create an interactive Streamlit web application

## 👨‍💻 Author
ABDUL REHMAN KHAN
📌 Data Analytics / Data Science Project

## ⭐ If you found this project useful
Consider giving this repository a ⭐ on GitHub!


### Suggested GitHub repository name

**`book-sales-eda`**

### Suggested short GitHub description

> 📚 Exploratory Data Analysis of Book Sales using Python, Pandas, NumPy, Matplotlib, and Seaborn. Analyzing sales trends, ratings, authors, genres, and other factors affecting book performance.
