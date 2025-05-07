# 🎬 Netflix EDA Project 📊

Welcome to the Netflix Exploratory Data Analysis (EDA) project!  
This project dives deep into the Netflix dataset to uncover patterns in content, top genres, popular directors/actors, release trends, and more.  

Let's explore how Netflix entertains the world! 🌍🍿

---

## 📁 Dataset Source

The dataset used is publicly available from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) and contains information about Netflix titles up to 2021.

---

## 🧹 Data Cleaning

Before diving into analysis, the dataset was cleaned and preprocessed:

- Converted `date_added` to datetime format
- Filled missing values in `rating`, `director`, `country`, and `cast`
- Dropped duplicate records
- Extracted duration type and number from `duration` column
- Extracted year and month from `date_added`

---

## 🔍 Key Exploratory Insights

### 🎥 Content Type Distribution
- Netflix has significantly more **Movies (69%)** compared to **TV Shows (31%)**.

### ⌛ Oldest vs Newest
- Content ranges from **1925 to 2021**, showing Netflix's diverse content library.

### 🎭 Top 10 Genres
- Most common genres include:
  - International Movies
  - Dramas
  - Comedies
  - International TV Shows

### 🌍 Top Countries Producing Content
- United States 🇺🇸 and India 🇮🇳 dominate the content catalog.

### 🎬 Top Directors
- Rajiv Chilaka and Suhas Kadav are among the top contributors, especially in animated content.

### 🌟 Top Actors/Actresses
- The most featured actors were visualized using a bar chart (e.g., Anupam Kher, Shah Rukh Khan, etc.).

---

## 📊 Visualizations

The project includes various charts to visualize insights:

- 📌 Bar Charts: Top genres, ratings, countries, directors, actors
- 📦 Box Plot: Duration distribution based on type (minutes vs seasons)
- 🔥 Heatmap: Content added per month and year
- 🇮🇳 Focused view: Indian content distribution
- 🧯 Genre-Release Heatmaps (WIP)

All visualizations are built using **Seaborn** and **Matplotlib**.

---

## 🛠️ Tools Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/pranav-builds/Netflix_EDA_Project

