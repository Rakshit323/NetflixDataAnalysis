# 📊 Netflix Data Analysis & Visualization  

This project analyzes the **Netflix Movies and TV Shows dataset** using **Python (pandas + matplotlib)**.  
It explores trends in Netflix content, including **type distribution, ratings, durations, release years, and country contributions**, and visualizes them with various charts.  

---

## 📂 Dataset  
The dataset used in this project is:  
**`netflix_titles.csv`**  
It contains metadata about Netflix titles, including:  
- Title  
- Type (Movie/TV Show)  
- Director, Cast  
- Country  
- Date Added  
- Release Year  
- Rating  
- Duration  
- Genre (Listed In)  

---

## 🛠️ Technologies Used  
- **Python 3**  
- **Pandas** – Data cleaning & manipulation  
- **Matplotlib** – Data visualization  

---

## 📑 Steps Performed  

1. **Data Cleaning**  
   - Removed missing values in key columns (`type`, `release_year`, `rating`, `country`, `duration`).  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of Movies vs TV Shows  
   - Content ratings breakdown  
   - Movie duration distribution  
   - Release year vs number of shows  
   - Top 10 countries by content count  
   - Movies vs TV Shows trend over time  

3. **Visualizations**  
   - 📊 **Bar Chart:** Movies vs TV Shows  
   - 🥧 **Pie Chart:** Percentage of content ratings  
   - 📈 **Histogram:** Movie duration distribution  
   - 🔴 **Scatter Plot:** Release year vs number of shows  
   - 📊 **Horizontal Bar Chart:** Top 10 countries  
   - 📈 **Line Charts:** Movies vs TV Shows released per year  

---

## 📸 Sample Visualizations  

### 1️⃣ Movies vs TV Shows  
Shows the total number of Movies and TV Shows available.  

### 2️⃣ Content Ratings Pie Chart  
Displays the percentage share of each rating category (e.g., TV-MA, PG, R).  

### 3️⃣ Movie Duration Histogram  
Distribution of movie durations in minutes.  

### 4️⃣ Release Year Scatter Plot  
Number of shows/movies released per year.  

### 5️⃣ Top 10 Countries  
Top contributing countries by number of titles on Netflix.  

### 6️⃣ Movies vs TV Shows Over Time  
Comparison of content trends across years.  

---

## 📂 Project Structure  

```
📁 Netflix-Data-Analysis
│── 📄 netflix_analysis.py      # Python analysis & visualization script
│── 📄 netflix_titles.csv       # Dataset (not included if large)
│── 📄 Movies vs TVshows.png    # Generated visualization
│── 📄 content_ratings_pie.png
│── 📄 Movies Duration histogram.png
│── 📄 release_year_scatter.png
│── 📄 top10_countries.png
│── 📄 movies_tv_shows_comparision.png
│── 📄 README.md                # Project documentation
```

---

## 🚀 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/netflix-data-analysis.git
   cd netflix-data-analysis
   ```

2. Install dependencies:  
   ```bash
   pip install pandas matplotlib
   ```

3. Run the script:  
   ```bash
   python netflix_analysis.py
   ```

4. Check the `png` files for generated visualizations.  

---

## 📌 Future Improvements  
- Add **Seaborn/Plotly** for interactive visualizations  
- Perform **Genre-wise analysis**  
- Use **WordClouds** for cast & director insights  
- Deploy via **Streamlit/Dash** for interactive dashboards  

---

## 📜 License  
This project is licensed under the MIT License – feel free to use and modify.  
