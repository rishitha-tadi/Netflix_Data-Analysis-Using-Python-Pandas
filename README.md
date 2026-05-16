# 🎬 Netflix Data Analysis Using Python & Pandas

## 📌 Project Overview

This project focuses on analyzing Netflix datasets using Python and Pandas in Jupyter Notebook. The project includes data cleaning, preprocessing, filtering, grouping, and visualization to gain meaningful insights from Netflix movies and TV shows data.

The analysis helps in understanding content trends, genres, ratings, release years, countries, and other important information using Exploratory Data Analysis (EDA) techniques.

---

# 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

# 📚 Libraries Used

## 🔹 Pandas

```python id="u2n4je"
import pandas as pd
```

Used for data manipulation, filtering, cleaning, and analysis.

---

## 🔹 NumPy

```python id="e5j7xp"
import numpy as np
```

Used for numerical operations and handling arrays.

---

## 🔹 Matplotlib

```python id="z3p9xt"
import matplotlib.pyplot as plt
```

Used for creating charts and visualizations.

---

## 🔹 Seaborn

```python id="h8f4qc"
import seaborn as sns
```

Used for advanced data visualization and graphical analysis.

---

# 📂 Dataset Information

The dataset contains information related to Netflix movies and TV shows, including:

- Title  
- Genre  
- Type (Movie/TV Show)  
- Release Year  
- Rating  
- Duration  
- Country  
- Cast & Director Information  

The dataset helps in analyzing Netflix content trends and entertainment data.

---

# 📊 Key Operations Performed

- Data Cleaning and Preprocessing  
- Handling Missing Values  
- Filtering and Sorting Data  
- Grouping Data using `groupby()`  
- Statistical Analysis  
- Genre-based Analysis  
- Country-wise Analysis  
- Data Visualization using Charts and Graphs  

---

# 🔍 Analysis Performed

## ✅ Checking Missing Values

```python id="4o2qtf"
df.isnull().sum()
```

Used to identify missing values in the dataset.

---

## ✅ Filtering Records

```python id="3m8bwu"
df[df['type'] == 'Movie']
```

Used to filter movies or TV shows based on conditions.

---

## ✅ Grouping Data

```python id="j4q2yx"
df.groupby('country').count()
```

Used to summarize Netflix content country-wise.

---

## ✅ Sorting Values

```python id="a6v7pk"
df.sort_values(by='release_year', ascending=False)
```

Used to sort records based on release year.

---

## ✅ Data Visualization

```python id="7n9vte"
plt.plot()
```

Used to visualize trends and patterns in Netflix data.

---

# 📈 Project Objectives

- Analyze Netflix movies and TV shows datasets  
- Understand content trends and viewer patterns  
- Perform exploratory data analysis using Python  
- Visualize genres, ratings, and release trends  
- Improve practical knowledge of Pandas and data analytics  

---

# 📊 Sample Analysis Tasks

- Finding the number of Movies and TV Shows  
- Analyzing content released each year  
- Identifying most common genres  
- Comparing ratings and durations  
- Country-wise Netflix content analysis  
- Filtering records based on categories  

---

# 🎯 Learning Outcomes

Through this project, I improved my understanding of:

- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Pandas Operations  
- Data Filtering and Grouping  
- Data Visualization  
- Working with Real-World Datasets  
- Statistical Analysis using Python  

---

# 📁 Project Structure

```bash id="1f5mrc"
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb
├── netflix_dataset.csv
├── README.md
```

# 📚 Conclusion

This project demonstrates how Python and Pandas can be used to analyze real-world Netflix datasets effectively. It showcases practical data analysis techniques including data cleaning, filtering, grouping, visualization, and trend analysis.

The project also improved practical skills in exploratory data analysis and helped in understanding entertainment content patterns using Python.

---

# ⭐ Author

**Tadi Rishitha**  
Aspiring Data Analyst | Python | Pandas | SQL | Power BI | Excel
