# YouTube Trending Video Analytics

## 📌 Project Overview

This project analyzes **YouTube trending video data in the United States** to identify patterns in content popularity, audience engagement, and platform dynamics. Using Python and a relational SQLite database, raw social media data is transformed into structured insights through analytical queries and visualizations.

The project demonstrates applied **data analytics, data engineering, and database design** concepts using a real-world dataset.

---

## 🎯 Objectives

* Process and clean large-scale YouTube trending data using Python and Pandas
* Design and populate a relational SQLite database
* Create reusable SQL views for analytical insights
* Analyze video performance across categories, channels, and time
* Visualize engagement metrics to support data-driven conclusions

---

## 📊 Dataset

* **Source:** Kaggle – YouTube Trending Video Dataset
* **Region:** United States
* **Time Period:** August 2020 – April 2024
* **Size:** 550,000+ records
* **Formats:** CSV (video data), JSON (category metadata)

The dataset includes video metadata, view counts, likes, comments, categories, and trending dates.

---

## 🛠 Tools & Technologies

* **Python**
* **Pandas & NumPy**
* **SQLite**
* **SQL**
* **Google Colab / Jupyter Notebook**
* **Matplotlib / Seaborn**

---

## 🔄 Project Workflow

1. Data acquisition using Kaggle API
2. Data cleaning and preprocessing with Pandas
3. Normalization and merging of JSON category metadata
4. Relational database design and population using SQLite
5. Creation of analytical SQL views
6. Query-based analysis and visualization

---

## 📈 Key Analysis & Insights

* Entertainment and Music categories dominate YouTube’s trending page
* Videos typically require hundreds of thousands of views to trend
* Engagement metrics (likes, comments) strongly correlate with view count
* A small percentage of videos generate a majority of total engagement
* Established channels trend more frequently than newer creators

---

## ▶️ How to Run the Project

1. Clone this repository
2. Open the Jupyter Notebook in Google Colab or locally
3. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Run all cells to reproduce data processing, database creation, and analysis

---

## 📁 Project Structure

```
├── notebook.ipynb        # Data ingestion, cleaning, analysis, visualization
├── youtube_trending.db  # SQLite database
├── README.md             # Project documentation
```

---

## 🚀 Future Improvements

* Time-series analysis of video performance before and after trending
* NLP analysis on video titles and descriptions
* Sentiment analysis on user comments
* Machine learning models to predict trending videos
* Cross-country trend comparison

---


