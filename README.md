# 🍴 Python Mini Project: Restaurant Data EDA

This is a **Python mini-project** where we explore and analyze a restaurant dataset using **Exploratory Data Analysis (EDA)**.  
The goal is to identify **best-rated**, **cost-effective**, and **region-specific** dining options.

---

## 📌 Project Tasks
1. **Import Libraries**  
2. **Set Options** (customize pandas/plot display)  
3. **Read Data** (load CSV file)  
4. **Understand and Prepare the Data** (check data types, clean up)  
5. **Understand the Variables** (explore features: city, cuisines, cost, rating, etc.)  
6. **Check for Missing Values** (fill/drop where needed)  
7. **Study Correlation** (relation between cost, rating, votes, etc.)  
8. **Detect Outliers** (identify unusual values via boxplots/IQR)  
9. **Create a new variable `region`** (group cities into North, South, East, West, etc.)  

---

## 📊 Key Insights
- **Cost vs Price Range**: Very strong positive correlation → they measure similar things.  
- **Ratings vs Cost**: Weak correlation → being expensive doesn’t always mean better ratings.  
- **Votes vs Photos**: Strong correlation → popular restaurants have more photos uploaded.  
- **Outliers**: Found in `average_cost_for_two`, `votes`, and `photo_count` (extreme values).  
- **Region Feature**: Helps compare restaurant trends across India’s regions.  

---

## 📂 Files in Repository
- `Python1_mini_project_1757002582.pdf` → Full project solution (step-by-step).  
- *(Optional)* `mini_project.ipynb` → Jupyter Notebook version of the project.  

---

## 🚀 Tools & Libraries Used
- **Python 3**  
- **pandas**  
- **numpy**  
- **matplotlib**  
- **seaborn**  

---

## 📌 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/restaurant-eda-mini-project.git
