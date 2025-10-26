# 📱 Google Play Store Data Analysis

This project explores and analyzes the **Google Play Store dataset** obtained from Kaggle.  
The goal is to uncover patterns and insights about app categories, user ratings, installs, and pricing trends.

---

## 📂 Dataset Information

**Dataset Source:** [Kaggle – Google Play Store Apps](https://www.kaggle.com/lava18/google-play-store-apps)

The dataset contains detailed information about applications available on the Google Play Store.

| Column | Description |
|---------|-------------|
| App | Name of the application |
| Category | Type of app (GAME, TOOLS, BUSINESS, etc.) |
| Rating | Average user rating (out of 5) |
| Reviews | Total number of user reviews |
| Size | App size (in MB) |
| Installs | Number of installs |
| Type | Free or Paid |
| Price | Price of the app |
| Content Rating | Age group for the app |
| Genres | Sub-category |
| Last Updated | Last update date |
| Current Ver | Current version |
| Android Ver | Minimum Android version required |

---

## 🎯 Project Objectives

- To identify the most popular app categories.  
- To analyze the relationship between **rating**, **installs**, and **price**.  
- To find whether **free or paid** apps get higher ratings.  
- To study how **app size** affects the number of installs.

---

## 🧰 Tools and Libraries Used

- **Python** 🐍  
- **Pandas** → Data cleaning and analysis  
- **NumPy** → Numerical operations  
- **Matplotlib** & **Seaborn** → Data visualization  
- **Jupyter Notebook** → Interactive analysis

---

## 🧹 Data Cleaning

Performed several preprocessing steps:
- Removed duplicates and irrelevant entries  
- Filled or removed missing values (especially in Rating and Size)  
- Converted columns like `Installs` and `Price` to numeric format  
- Filtered out invalid data (e.g., Rating > 5)

---

## 📊 Exploratory Data Analysis (EDA)

Key visualizations and findings:

- **Top 5 App Categories:** Tools, Entertainment, Education, Business, and Lifestyle  
- **Average Rating:** 4.17  
- **Free vs Paid:** Free apps receive more installs but slightly lower average ratings  
- **App Size Impact:** Smaller apps tend to get more downloads  
- **Price vs Installs:** Paid apps rarely cross 1M installs  

---

## 📈 Key Insights

✅ Educational and Entertainment apps dominate the Play Store  
✅ Free apps are more popular but not always higher-rated  
✅ Users prefer smaller-sized apps  
✅ Price has an inverse relationship with installs  

---

## 🧩 Conclusion

The analysis reveals how category, price, and size influence app performance on the Play Store.  
App developers can use these insights to improve app design, marketing strategy, and user engagement.

---

## 🚀 Future Work

- Perform **sentiment analysis** on user reviews  
- Build a **machine learning model** to predict app success  
- Explore **time-based trends** in app updates and installs  

---

## 👤 Author

**Muhammad Waqas**  
📧 [waqasgurmani364@gmail.com](mailto:waqasgurmani364@gmail.com)  
💻 [GitHub Profile](https://github.com/WaqasGurmani)  
🎓 Data Analyst | Machine Learning Enthusiast  

---

## 🏁 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/WaqasGurmani/google-playstore-analysis.git
   ```
2. Open the notebook:
   ```bash
   jupyter notebook Google_PlayStore.ipynb
   ```
3. Run all cells to see the visualizations and results.

---

## 🗂 Files in This Repository

| File | Description |
|------|-------------|
| `Google_PlayStore.ipynb` | Jupyter notebook with complete data analysis |
| `googleplaystore.csv` | Dataset used for analysis |
| `README.md` | Project documentation |

---

**📊 Insightful Data Analysis Project by Muhammad Waqas**
