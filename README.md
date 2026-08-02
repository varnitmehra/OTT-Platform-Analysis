# 🎬 OTT Platform Data Analysis using MySQL & Python

## 📌 Project Overview

This project analyzes an **OTT (Over-the-Top) streaming platform** dataset using **MySQL** and **Python** to uncover valuable business insights about user behavior, movie performance, and viewing patterns.

The project demonstrates how SQL queries and Python-based data analysis can be combined to transform raw data into actionable insights through data visualization and exploratory analysis.

---

## 🎯 Objectives

* Analyze OTT platform user behavior.
* Perform Exploratory Data Analysis (EDA) on users, movies, and watch history.
* Execute SQL queries to solve real-world business problems.
* Visualize insights using Python libraries.
* Understand customer engagement and content performance.

---

## 📂 Dataset

The project uses three datasets:

| Dataset               | Description                                                                        |
| --------------------- | ---------------------------------------------------------------------------------- |
| **Users.csv**         | Contains user information such as age, gender, country, and subscription plan.     |
| **Movies.csv**        | Contains movie details including title, genre, language, IMDb rating, and revenue. |
| **Watch_History.csv** | Stores user watch history, including watched movies and watch time.                |

---

## 🛠️ Technologies Used

* Python
* MySQL 8.0
* Jupyter Notebook / JupyterLab
* Pandas
* NumPy
* SQLAlchemy
* PyMySQL
* Matplotlib

---

## 📊 Project Workflow

### 1. Database Connection

* Connected Python with MySQL using SQLAlchemy.
* Retrieved data directly from the MySQL database.

### 2. Data Loading

* Imported Users, Movies, and Watch History tables into Pandas DataFrames.

### 3. Data Exploration

Performed:

* Dataset overview
* Data inspection
* Missing value analysis
* Data quality checks

### 4. Exploratory Data Analysis (EDA)

Visualized and analyzed:

* Gender Distribution
* Age Distribution
* Country-wise User Distribution
* Subscription Plan Distribution
* Movie Genre Distribution
* Language Distribution
* IMDb Rating Distribution
* Revenue Distribution

### 5. Business Insights using SQL & Python

The project answers several business questions, including:

* Which movie genres are watched the most?
* Which subscription plan has the highest average watch time?
* Which countries have the highest average watch time?
* What are the Top 10 most watched movies?
* Do higher IMDb ratings lead to higher revenue?

---

## 📈 Key Features

* MySQL database integration
* SQL JOIN operations
* Aggregate SQL queries
* Exploratory Data Analysis (EDA)
* Business intelligence reporting
* Data visualization using Matplotlib
* Clean and well-structured Jupyter Notebook workflow

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/OTT-Platform-Data-Analysis.git
cd OTT-Platform-Data-Analysis
```

Install the required libraries:

```bash
pip install pandas numpy sqlalchemy pymysql matplotlib
```

Configure your MySQL credentials in the notebook before running the project.

---

## ▶️ How to Run

1. Create the MySQL database.
2. Import the CSV files into MySQL.
3. Update the database connection details in the notebook.
4. Open the notebook in Jupyter Notebook or JupyterLab.
5. Run all cells sequentially.

---

## 📁 Repository Structure

```text
OTT-Platform-Data-Analysis/
│
├── OTT_file.ipynb
├── Users.csv
├── Movies.csv
├── Watch_History.csv
├── README.md
└── requirements.txt
```

---

## 📊 Skills Demonstrated

* SQL
* Database Management
* Python Programming
* Data Cleaning
* Data Analysis
* Exploratory Data Analysis
* Business Analytics
* Data Visualization
* Pandas
* MySQL Integration

---

## 🔮 Future Improvements

* Build an interactive dashboard using Power BI or Tableau.
* Develop predictive models for user engagement.
* Recommend movies using machine learning.
* Deploy the analysis as a web application using Streamlit.

---

## 👨‍💻 Author

**Varnit Mehra**

If you found this project helpful, consider giving the repository a ⭐ on GitHub.
