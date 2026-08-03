# 🎬 IMDB & OTT Platform Analytics using Power BI, MySQL & Python

<p align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)

</p>

---

# 📌 Project Overview

This project demonstrates an end-to-end Business Intelligence workflow by combining **Python**, **MySQL**, and **Power BI** to analyze IMDb movie data and OTT platform user behavior.

The project covers every stage of the analytics lifecycle:

- Data Collection
- Data Cleaning
- Data Preprocessing
- Database Management
- SQL Analysis
- Data Modeling
- Dashboard Development
- Business Insights
- Decision Making

The objective is to transform raw entertainment data into meaningful business insights that help understand movie performance, user engagement, and platform growth.

---

# 🎯 Business Problem

Streaming platforms generate enormous amounts of data every day.

Business teams need answers to questions like:

- Which genres perform the best?
- Which movies receive the highest ratings?
- What content keeps users engaged?
- Which users are the most active?
- What factors influence movie popularity?
- How can recommendations improve user retention?

This project answers these questions using Business Intelligence techniques.

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Data Cleaning & Preprocessing |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| MySQL | Data Storage |
| SQL | Business Queries |
| SQLAlchemy | Database Connection |
| Jupyter Notebook | Analysis |
| Power BI | Dashboard Creation |
| Excel | Intermediate Dataset |
| GitHub | Version Control |

---

# 📂 Project Structure

```
IMDB-OTT-Analysis/

│
├── Dataset/
│     ├── movies.csv
│     ├── users.csv
│     ├── watch_history.csv
│
├── Notebook/
│     ├── IMDB_Movie_Analysis_With_Power_BI.ipynb
│     ├── OTT_file.ipynb
│
├── Power BI/
│     └── OTT_Analysis.pbix
│
├── Images/
│
├── README.md
│
└── LICENSE
```

---

# 📊 Dataset Description

The project uses three primary datasets.

## 1. Movies Dataset

Contains movie-related information such as

- Movie Title
- Genre
- Director
- Duration
- Language
- Budget
- Gross Collection
- IMDb Score
- Facebook Likes
- Reviews
- Release Year

---

## 2. Users Dataset

Contains information about OTT users.

Examples include

- User ID
- User Name
- Country
- Gender
- Subscription Details

---

## 3. Watch History

Stores user viewing activity.

Includes

- User ID
- Movie ID
- Watch Duration
- Watch Date
- Ratings

---

# 🧹 Data Preprocessing

Python was used for preprocessing before visualization.

Major preprocessing steps include

✔ Missing Value Handling

✔ Duplicate Removal

✔ Data Type Conversion

✔ Null Value Treatment

✔ Feature Cleaning

✔ Dataset Validation

✔ Data Consistency Checks

---

# 🐍 Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import sqlalchemy
import pymysql
```

---

# 🗄 Database Design

The cleaned datasets were imported into **MySQL**.

Tables

- users
- movies
- watch_history

Relationships were created using primary and foreign keys to enable efficient SQL analysis.

---

# 📈 SQL Analysis

Business questions answered using SQL include:

- Total Users
- Total Movies
- Most Popular Movies
- Top Rated Movies
- Most Active Users
- Watch Frequency
- Genre Popularity
- Monthly Activity
- Average Ratings
- Movie Performance

---

# 📊 Power BI Dashboard

The Power BI dashboard transforms raw data into interactive visualizations.

Dashboard includes:

### Executive Summary

- Total Movies
- Total Users
- Total Watch Records
- Average IMDb Rating

---

### Movie Analysis

- Genre Distribution
- Top Rated Movies
- Revenue Analysis
- Budget Analysis
- Runtime Analysis

---

### User Analysis

- User Growth
- Active Users
- Country Distribution
- Gender Distribution

---

### Watch History

- Viewing Trends
- Most Watched Movies
- Monthly Activity
- Daily Engagement

---

### Interactive Filters

Users can filter dashboard using

- Genre
- Year
- Country
- Rating
- Language

---

# 📊 Key Performance Indicators (KPIs)

The dashboard tracks

- Total Movies
- Total Users
- Average IMDb Rating
- Total Watch Records
- Average Watch Time
- Highest Rated Movie
- Most Popular Genre
- Top User
- Revenue
- User Growth

---

# 📌 Business Insights

Some business insights generated include:

- High-rated movies generally receive greater audience engagement.
- User watch behavior varies significantly across genres.
- Popular genres attract more consistent viewing activity.
- User engagement trends help identify retention opportunities.
- Dashboard filters enable detailed performance comparisons.

---

# 📉 Analytics Workflow

```text
Raw Dataset
      │
      ▼
Python Data Cleaning
      │
      ▼
Data Preprocessing
      │
      ▼
MySQL Database
      │
      ▼
SQL Analysis
      │
      ▼
Power BI Data Modeling
      │
      ▼
Dashboard Development
      │
      ▼
Business Insights
```

---

# 🎯 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Data Visualization
- SQL Query Writing
- Database Management
- Dashboard Design
- Business Intelligence
- ETL Process
- Power BI
- Python Programming

---

# 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/yourrepository.git
```

---

### Install Libraries

```bash
pip install pandas numpy matplotlib sqlalchemy pymysql
```

---

### Open Notebook

```bash
jupyter notebook
```

---

### Import Dataset

Place datasets inside the Dataset folder.

---

### Execute Notebook

Run all notebook cells.

---

### Open Power BI Dashboard

Open the `.pbix` file in Power BI Desktop.

Refresh the data source if required.

---

# 📷 Dashboard Preview

> Add screenshots inside the Images folder.

Example

```
Images/

Dashboard1.png

Dashboard2.png

Dashboard3.png
```

Then display them

```markdown
## Dashboard

![Dashboard](Images/Dashboard1.png)
```

---

# 📚 Learning Outcomes

This project demonstrates practical knowledge of

- Python
- SQL
- MySQL
- Power BI
- ETL
- Data Analytics
- Dashboard Design
- Business Intelligence
- Data Visualization
- Data Cleaning

---

# 🔮 Future Improvements

- Recommendation System
- Machine Learning Models
- Sentiment Analysis
- Forecasting
- Real-time Dashboard
- Azure SQL Integration
- Power BI Service Deployment

---

# 👨‍💻 Author

**Vannu Bhai**

Data Analyst | Power BI | SQL | Python

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

# ⭐ If you found this project useful

Please consider giving it a ⭐ on GitHub.

---

# 📄 License

This project is licensed under the MIT License.

---

## 🙌 Thank You

Thank you for visiting this repository!

Feel free to fork, star, or contribute to improve the project.
