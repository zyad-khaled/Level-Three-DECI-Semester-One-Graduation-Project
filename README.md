# Level-Three-DECI-Semester-One-Graduation-Project
# 🎬 TMDB Movie Data Analysis

## 📌 Overview

This project performs an Exploratory Data Analysis (EDA) on the TMDB Movie Dataset to discover trends in the film industry. The analysis focuses on identifying the most active filmmakers, factors influencing movie revenue, and how release timing impacts financial success.

---

## 🎯 Project Objectives

* Identify the directors, actors, production companies, and genres that produced the most movies since 2000.
* Analyze the highest-grossing movies and the teams behind their success.
* Investigate how release month and release year affect movie revenue.
* Explore the relationship between movie characteristics and box office performance.

---

## 📂 Dataset

* **Source:** TMDB Movie Dataset
* **Original Size:** ~10,000 movies
* **Final Size after Cleaning:** ~3,000 movies

The dataset includes information such as:

* Movie title
* Release date
* Budget
* Revenue
* Runtime
* Genres
* Cast
* Director
* Production companies
* Popularity
* Vote average

---

## 🧹 Data Preprocessing

* Removed duplicate records.
* Removed rows with invalid or missing budget/revenue values.
* Handled missing values.
* Converted release dates into month and year.
* Filtered movies released from **2000 onwards** for selected analyses.

---

## ❓ Research Questions

### 1. Which staff worked on the most movies since 2000?

The analysis identified the most active:

* Directors
* Cast members
* Production companies
* Movie genres

**Top Directors**

* Steven Soderbergh
* Ridley Scott
* Steven Spielberg

**Top Production Companies**

* New Line Cinema
* Paramount Pictures
* DreamWorks Animation

---

### 2. Who worked on the highest-grossing movies?

The highest-revenue movies include:

* Avatar
* Star Wars: The Force Awakens
* The Avengers
* Jurassic World
* Furious 7

The project also identifies:

* Directors
* Cast
* Genres
* Production companies
  behind these blockbuster films.

---

### 3. How does time affect movie success?

Key findings:

* **June** is the most profitable month for movie releases.
* **September** generates the lowest overall revenue.
* Median movie revenue has generally increased over the years.

---

### 4. Which movie characteristics are associated with high revenue?

The analysis found positive relationships between revenue and:

* Higher production budgets
* Higher audience ratings
* Greater popularity
* Runtime (up to an optimal point)

---

## 📊 Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📈 Key Insights

* Large-budget movies tend to generate higher revenue.
* Popular and highly rated movies generally perform better financially.
* June is the best month for movie releases.
* Certain directors and production companies consistently produce successful films.

---

## ⚠️ Limitations

* Extensive data cleaning reduced the dataset from approximately **10,000** to **3,000** records.
* Many records contained missing or zero values for budget and revenue.
* Some dataset columns were unclear or lacked useful information.
* Additional variables (such as awards or marketing budget) could improve future analyses.

---

## 🚀 Future Improvements

* Include award information and critic scores.
* Apply machine learning models to predict movie revenue.
* Build an interactive dashboard using Power BI or Tableau.
* Perform genre-specific and country-specific analyses.

---

## 📄 License

This project is intended for educational and portfolio purposes.
