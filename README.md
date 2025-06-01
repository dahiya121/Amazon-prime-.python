# Amazon-prime-.python
# 🎬 Netflix Data Analysis Project (EDA)

This project explores and analyzes a dataset containing metadata of Netflix content, including titles, ratings, genres, popularity, release years, and cast/crew information. The goal is to uncover insights that can help streaming platforms make better business decisions using **Exploratory Data Analysis (EDA)** techniques.

---

## 📁 Dataset Files

- `titles.csv`: Contains details like title name, type (Movie/Show), genres, release year, etc.
- `credits.csv`: Contains information about the cast and crew of each title.

---

## 🧰 Libraries Used

- **Pandas** – for data cleaning and manipulation  
- **NumPy** – for numerical operations  
- **Seaborn** – for data visualization  
- **Matplotlib** – for plotting charts  
- *(Optional: sklearn, datetime if extended analysis is performed)*

---

## 📊 Key Steps in the Project

1. **Data Loading**: Read both CSV files using `pandas.read_csv()`
2. **Data Merging**: Merge both datasets using the common `id` column
3. **Data Cleaning**:
   - Handled null values
   - Fixed inconsistent formatting (e.g., replacing 'UNKNOWN' or empty strings)
   - Removed duplicates
4. **Data Wrangling**:
   - Converted data types where needed
   - Extracted useful features (e.g., number of cast members, release decade, etc.)
5. **Visualization & Insights**: 
   - Created 15 different visualizations to explore content trends, ratings, popularity, and more
   - Used count plots, bar plots, boxplots, heatmaps, pair plots, and more

---

## 📈 Visualizations Included

1. Count of Movies vs Shows  
2. Top 10 Genres  
3. IMDb Rating Distribution  
4. Boxplot: IMDb Rating vs Age Certification  
5. Number of Titles per Year  
6. Top 10 Most Popular Titles (TMDb)  
7. TMDb Score Distribution  
8. Runtime Distribution  
9. Top Countries by Number of Titles  
10. Number of Seasons (Shows Only)  
11. Content Type vs Average Rating  
12. Top 10 Directors with Most Titles  
13. Age Certification Distribution  
14. Correlation Heatmap  
15. Pair Plot (Ratings vs Popularity)

---

## 📌 Insights & Recommendations

- Drama, Comedy, and Action dominate in terms of quantity and popularity
- Movies tend to be more popular and higher rated than shows
- Age certifications like TV-MA and R tend to get better ratings
- Some low-rated titles are still highly popular — possibly driven by hype
- Clean metadata is essential for improving recommendation systems

**Final Suggestion**: Use insights to guide content acquisition, marketing strategy, and user targeting to enhance viewer experience and maximize business growth.

---

## ✅ Conclusion

This project proves the power of data in guiding content platforms toward smarter decisions. With just basic Python tools and good storytelling through data, we can unlock meaningful patterns that drive both engagement and growth.

> _Better content starts with better data._

---

## ▶️ How to Run

1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
