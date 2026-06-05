# 🎬 Netflix Movies Data Analysis Project

## 📌 Project Overview

This Netflix Movies Data Analysis Project is a comprehensive end-to-end Data Analytics assignment designed to simulate a real-world technical interview case study for aspiring Data Analysts and Data Scientists.

The objective of this project is to transform raw and unstructured movie data into meaningful business insights through systematic data cleaning, preprocessing, exploratory data analysis (EDA), and visualization. The dataset contains approximately 9,000–10,000 movies, enabling large-scale analysis of movie trends, genres, popularity, and audience preferences.

---

## 🎯 Business Objective

The primary goal of this analysis is to understand movie characteristics, audience interests, and content trends that can help streaming platforms improve recommendation systems and content strategy.

By analyzing historical movie data, this project answers important business questions such as:

* Which genres dominate the platform?
* Which movies are the most and least popular?
* How have movie releases changed over time?
* What patterns exist in audience voting behavior?
* How can raw data be transformed into actionable insights?

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Development Environment

* Jupyter Notebook

### Libraries

* NumPy – Numerical computing and array operations
* Pandas – Data cleaning, transformation, and analysis
* Matplotlib – Data visualization
* Seaborn – Statistical visualization and trend analysis

---

## 🧹 Data Cleaning & Preprocessing

Data preprocessing was the most critical stage of the project. Several transformations were performed to improve data quality and prepare it for analysis.

### 1. Temporal Data Processing

* Converted the **Release Date** column from string format to datetime format.
* Extracted the release year for trend analysis.

### 2. Feature Engineering

Created a new categorical feature based on vote averages:

| Vote Average    | Category      |
| --------------- | ------------- |
| High Scores     | Popular       |
| Medium Scores   | Average       |
| Low Scores      | Below Average |
| Very Low Scores | Not Popular   |

This transformation made the dataset easier to interpret from a business perspective.

### 3. Genre Expansion

Many movies belonged to multiple genres such as:

Action, Adventure, Sci-Fi

To perform accurate genre-level analysis:

* Split genre combinations into individual genres.
* Applied data explosion techniques.
* Expanded the dataset from approximately 9,800 records to more than 25,000 genre-specific entries.

### 4. Dimensionality Reduction

Removed irrelevant columns including:

* Movie Overview
* Original Language
* Poster URL
* Other non-essential attributes

This improved analysis efficiency and reduced noise.

---

## 📊 Exploratory Data Analysis (EDA)

A combination of histograms, count plots, category plots, and distribution visualizations was used to identify hidden patterns and trends within the data.

### Visualizations Included

* Genre Distribution Analysis
* Popularity Distribution
* Movie Release Trends
* Vote Average Analysis
* Popularity Category Breakdown
* Top & Bottom Performing Movies

---

## 🔍 Key Findings

### 🎭 Most Dominant Genre

* Drama emerged as the most frequently occurring genre in the dataset.
* Western movies were the least represented genre.

### 🏆 Most Popular Movie

* Spider-Man: No Way Home achieved the highest popularity score in the dataset.

### 📉 Least Popular Movies

Movies identified with the lowest popularity scores include:

* The United States vs. Billie Holiday
* Threads

### 📅 Movie Release Trends

* 2020 recorded the highest number of movie releases.
* 1940 recorded the lowest number of releases.

### ⭐ Vote Category Distribution

The dataset displayed a relatively balanced distribution among popularity categories:

* Popular
* Average
* Below Average
* Not Popular

Both "Popular" and "Not Popular" categories contained approximately 2,400 movies each.

---

## 💡 Business Impact

This analysis demonstrates how raw entertainment data can be transformed into strategic insights that support:

* Recommendation Systems
* Audience Preference Analysis
* Content Planning
* Market Trend Identification
* Decision-Making for Streaming Platforms

---

## 🚀 Skills Demonstrated

This project showcases practical industry-level skills including:

✔ Data Cleaning & Preprocessing

✔ Exploratory Data Analysis (EDA)

✔ Feature Engineering

✔ Data Visualization

✔ Business Insight Generation

✔ Data Storytelling

✔ Problem Solving with Real-World Datasets

---
# 📌 Key Findings & Conclusion

After performing extensive data cleaning, feature engineering, and exploratory data analysis, several interesting insights were discovered from the Netflix movie dataset.

## 🎭 Q1: What is the Most Frequent Genre?

**Drama** emerged as the most dominant genre in the dataset.

* Drama accounts for more than **14%** of all genre occurrences.
* It appears significantly more often than the remaining 19 genres.
* This suggests that drama-based content remains one of the most preferred categories in the entertainment industry.

### Insight

Streaming platforms may prioritize drama content because of its broad audience appeal and consistent demand.

---

## ⭐ Q2: Which Genre Receives the Highest Votes?

Approximately **25.5%** of all movies in the dataset fall into the **Popular** category, representing over **6,500 movies**.

Among all genres:

🏆 **Drama receives the highest audience engagement and vote popularity.**

* More than **18.5%** of highly-rated and popular movies belong to the Drama genre.
* Drama not only dominates in quantity but also performs strongly in audience appreciation.

### Insight

Producing quality drama content can significantly improve audience engagement and platform retention.

---

## 🕷️ Q3: Which Movie Has the Highest Popularity?

The movie with the highest popularity score in the dataset is:

### 🏆 Spider-Man: No Way Home

#### Genres:

* Action
* Adventure
* Science Fiction

### Insight

The success of this movie highlights the strong audience preference for blockbuster franchises that combine action, adventure, and science-fiction elements.

---

## 📉 Q4: Which Movie Has the Lowest Popularity?

The movies with the lowest popularity scores identified in the dataset include:

### 🎬 The United States vs. Billie Holiday

### 🎬 Threads

#### Associated Genres:

* Music
* Drama
* War
* Science Fiction
* History

### Insight

Popularity can be influenced by factors beyond genre, such as marketing, audience reach, release timing, and competition.

---

## 📅 Q5: Which Year Had the Highest Number of Movie Releases?

### 🏆 2020 recorded the highest number of movie releases in the dataset.

This year showed a remarkable concentration of movie production and releases compared to previous years.

### Insight

The increasing availability of digital streaming platforms has significantly contributed to the growth of content production in recent years.

---

# 🎯 Final Conclusion

This project demonstrates the complete lifecycle of a real-world data analytics workflow—from raw data preprocessing to actionable business insights.

The analysis revealed that:

* 🎭 Drama is the most dominant and most popular genre.
* ⭐ More than one-fourth of movies fall into the Popular category.
* 🕷️ Spider-Man: No Way Home achieved the highest popularity score.
* 📉 The United States vs. Billie Holiday and Threads recorded the lowest popularity scores.
* 📅 2020 experienced the highest volume of movie releases.
* 📊 Effective preprocessing and feature engineering were essential in uncovering these insights.

Beyond visualization and coding, this project highlights the importance of data cleaning, transformation, and analytical thinking—the core skills that distinguish successful Data Analysts and Data Scientists in industry environments.

**This project serves as a strong portfolio piece showcasing proficiency in Python, Pandas, NumPy, Data Visualization, Exploratory Data Analysis (EDA), and Business Insight Generation.**


### ⭐ If you found this project helpful, consider giving it a star on GitHub!

