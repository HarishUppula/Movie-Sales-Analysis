# 🎬 Movie Sales Analysis Dashboard (Power BI)

## 📌 Project Overview
The **Movie Sales Analysis Dashboard** is a data analytics project built using **Power BI** to analyze IMDb movie data and uncover insights related to movie performance, revenue trends, genres, ratings, votes, and director contributions.  
This dashboard supports **data-driven decision-making** for movie studios, distributors, and streaming platforms.

---

## ❓ Business Problem
Movie companies and streaming platforms handle large volumes of movie-related data such as:
- Revenue  
- Ratings  
- Genres  
- Votes  
- Directors  
- Runtime  

Manually analyzing this data makes it difficult to:
- Identify top-performing genres and years  
- Understand what drives box-office revenue  
- Analyze the impact of ratings, votes, and runtime  
- Identify high-revenue movies and directors  

A centralized analytical dashboard is required to convert raw data into meaningful insights.

---

## 🎯 Business Objective
The objectives of this project are:
- Analyze movie performance across different years  
- Compare revenue and audience engagement across genres  
- Identify top-grossing movies and directors  
- Understand how ratings, votes, and runtime influence revenue  
- Build an interactive Power BI dashboard for exploration  

---

## 📂 Dataset Overview
- **Source:** IMDb Movie Dataset  
- **Total Rows:** 1000  
- **Total Columns:** 12  

### 📌 Key Columns
| Column Name | Description |
|------------|------------|
| Rank | Movie ranking position |
| Title | Movie name |
| Genre | Movie genre(s) |
| Description | Short movie synopsis |
| Director | Movie director |
| Actors | Main actors |
| Year | Release year |
| Runtime (Minutes) | Movie duration |
| Rating | IMDb rating |
| Votes | Audience votes |
| Revenue (Millions) | Revenue in USD |
| Metascore | Critic score (0–100) |

---

## 🧹 Data Cleaning & Transformation
- Identified missing values in **Revenue** and **Metascore**
- Replaced null values with column averages
- Ensured correct data types for all columns
- Created calculated columns and DAX measures
- Validated data before building visuals

---

## 📊 DAX Measures Created
- Total Movies  
- Total Revenue  
- Average Rating  
- Average Revenue  
- Average Runtime  
- Average Votes  
- Highest Revenue Movie  
- Genre-wise Revenue  
- Director-wise Revenue  

---

## 📈 Dashboard Highlights
- Year-wise movie and revenue trends  
- Genre-wise revenue and movie count comparison  
- Top-grossing movies and directors  
- Impact of ratings, votes, and runtime on revenue  
- Interactive slicers for year, genre, and director  

---

## 🔍 Key Insights
- Higher IMDb ratings generally correlate with higher revenue  
- **Action** and **Drama** are the top-performing genres  
- A small number of directors contribute significantly to total revenue  
- Medium-runtime movies perform better in ratings and revenue  
- Audience engagement (votes) is a strong success indicator  

---

## ✅ Recommendations
- Focus production on high-performing genres like **Action** and **Drama**
- Collaborate more with top revenue-generating directors
- Target movies with optimal runtimes
- Use early ratings and votes to predict movie success

---

## ⚠️ Challenges Faced
- Missing and incomplete data
- Data type inconsistencies
- Complex correlations between metrics
- Selecting meaningful KPIs

---

## 🏁 Conclusion
The **Movie Sales Analysis Dashboard** successfully transforms raw IMDb data into actionable insights.  
It enables informed decisions in:
- Movie production  
- Marketing strategies  
- Budget planning  
- Content strategy  

This project demonstrates strong skills in **Power BI, DAX, data cleaning, and business analytics**.

---

## 🛠 Tools & Technologies
- Power BI  
- DAX  
- Excel  
- IMDb Dataset  

---

⭐ *If you found this project useful, feel free to star the repository!*
