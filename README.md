# 📺 Netflix Data Analysis

This project presents an in-depth analysis of a Netflix titles dataset using Python. It explores various dimensions such as content type, directors, ratings, country of production, and genres. The central research question driving this analysis is:

> **Does the director of a production correlate with its rating?**

---

## 📌 Project Overview

Netflix is a global streaming platform with thousands of movies, TV shows, and documentaries. This project analyzes a publicly available Netflix dataset to:

- Understand the distribution of content across genres and countries.
- Examine rating patterns by directors.
- Identify the most frequent contributors to Netflix content.
- Visualize data insights using static and interactive plots.

---

## 📂 Dataset Description

The dataset contains over **8,000 records** of Netflix titles with the following features:

### Key Columns:
- `type`: Movie or TV Show
- `title`: Name of the content
- `director`: Name of the director
- `cast`: Main actors
- `country`: Production country
- `date_added`: Date added to Netflix
- `release_year`: Release year of the content
- `rating`: Content maturity rating (e.g., TV-MA, PG)
- `duration`: Duration in minutes or episodes
- `listed_in`: Genre(s)
- `description`: Brief summary

> After cleaning, **5,332 records** remained for analysis.

---

## 🧹 Data Cleaning Steps

- Removed rows with missing values in critical columns (`director`, `rating`, etc.).
- Verified data types and transformed necessary fields.
- Dropped duplicates and ensured data integrity.

---

## 📈 Analysis & Visualizations

All visualizations were created using:
- **Matplotlib** & **Seaborn** for static plots
- **Plotly** for interactive visualizations

### Highlights:
- **Bar charts** were used extensively due to their effectiveness in comparing categorical data.
- Horizontal bar charts (`barh`) were utilized for readability of long category names like director names.

### Visualizations Include:
- Movie vs TV Show Distribution
- Top Directors by Number of Titles
- Rating-wise Director Distribution
- Top Countries by Production Count
- Most Frequent Genres

---

## 🎯 Key Findings

- **Movies** significantly outnumber **TV Shows** in the dataset.
- Directors like *Rajiv Chilaka*, *Marcus Raboy*, and *Steven Spielberg* are highly featured.
- The **United States**, **India**, and **UK** are the top-producing countries.
- Common genres include *Dramas*, *Comedies*, and *Documentaries*.
- Some directors are consistently associated with certain ratings, though:
  - **No strong universal correlation** was found between director and rating.
  - **Genre** appears to have a stronger influence on rating than director alone.

---

## 📚 Methodologies

- **pandas**: Data cleaning, filtering, aggregation
- **seaborn / matplotlib**: Statistical and categorical plotting
- **plotly**: Interactive charts for director-rating exploration
- Grouping by `director`, `type`, and `rating` for pattern discovery

---

## 📌 Conclusion

While patterns between certain directors and ratings exist, the dataset does not support a **strong or causal correlation** across the board. Limitations include:

- A large number of unique or one-time directors
- Missing metadata (especially for TV Shows)
- Genre overlap skewing rating associations

Future work can involve more controlled experiments by normalizing for genres and focusing on directors with more consistent output.

---

## 🧠 Author

**Muhammad Wasil** — *Data Science Enthusiast*  
🔗 [Rana Muhmammad Wasil](www.linkedin.com/in/rana-muhammad-wasil-b8a058259)  
📧 (mailto:iconicwasil@gmail.com)

---

## 📁 Project Structure

```
📦 Netflix-Data-Analysis
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── netflix_analysis.ipynb
├── README.md
└── assets/
    └── images/
```




