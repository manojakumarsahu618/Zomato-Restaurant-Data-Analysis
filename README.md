# 🍽️ Zomato Restaurant Data Analysis | Python EDA

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a Zomato restaurant dataset using Python. The objective is to analyze restaurant categories, customer ratings, votes, online ordering, table booking availability, and approximate dining costs.

Using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn, this project explores restaurant-level data, identifies patterns, and derives meaningful business insights through statistical analysis and visualizations.

## 🎯 Project Objectives

- Understand the structure and characteristics of the dataset.
- Perform data cleaning and preprocessing.
- Analyze restaurant categories and customer voting patterns.
- Identify the most popular restaurants based on customer votes.
- Explore the relationship between restaurant ratings and votes.
- Compare average ratings across restaurant categories.
- Analyze table booking and online ordering availability.
- Compare approximate restaurant costs across categories.
- Generate meaningful business insights through visualizations.

## 📂 Dataset Information

The dataset contains **148 records and 7 columns**.

| Column | Description |
|---|---|
| Restaurant Name | Name of the restaurant |
| Online_Order | Online ordering availability |
| Book_Table | Table booking availability |
| Rate | Restaurant rating out of 5 |
| Votes | Number of customer votes |
| Approx_Cost(For Two People) | Estimated cost for two people |
| Listed_In(Type) | Restaurant category |

## 🛠️ Technologies & Tools

- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Version Control:** Git & GitHub

## ⚙️ Project Workflow

1. Dataset Loading
2. Data Inspection and Understanding
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis
5. Statistical Analysis
6. Data Visualization
7. Business Insights and Conclusion

## 🧹 Data Cleaning

The following data-cleaning operations were performed:

- Converted restaurant ratings from text format (e.g., 4.1/5) into numerical values.
- Standardized column names into lowercase.
- Renamed the approximate cost column for easier analysis.
- Checked missing values.
- Identified duplicate records.
- Verified dataset structure and data types.

**Data Quality Results:**
- Total records: 148
- Total columns: 7
- Missing values: 0
- Duplicate records: 0

## 📊 Exploratory Data Analysis

The project answers the following ten analytical questions:

1. How many customer votes has each restaurant type received?
2. How many restaurants offer table booking?
3. Which five restaurants have the highest number of votes?
4. Is there a relationship between restaurant ratings and customer votes?
5. What is the average rating for each restaurant type?
6. Which restaurant type is most common in the dataset?
7. What ratings do restaurants most commonly receive?
8. Which restaurant type has the highest average cost for two people?
9. Do restaurants offering online ordering have higher ratings?
10. Which restaurant types have more records without online ordering?

## 🔍 Key Business Insights

1. **Most Common Restaurant Type:** Dining accounts for 110 records (74.3%) of the dataset.

2. **Highest Customer Votes:** Dining restaurants received the highest total votes, with 20,363 votes.

3. **Table Booking:** Only 8 records (5.4%) offer table booking, while 140 records (94.6%) do not.

4. **Most Voted Restaurant:** Empire Restaurant leads with 4,884 votes, followed by Meghana Foods with 4,401 votes.

5. **Rating and Votes Relationship:** Restaurant ratings and customer votes show a moderate positive correlation of approximately 0.49.

6. **Highest Average Rating:** The Other category has the highest average rating of approximately 3.91/5.

7. **Overall Rating Pattern:** The average rating is approximately 3.63, while 3.8 is the most frequently occurring rating.

8. **Highest Average Cost:** Buffet restaurants have the highest average approximate cost for two people at ₹671.43.

9. **Online Ordering and Ratings:** Restaurants accepting online orders have a higher average rating (3.86) compared with those without online ordering (3.49).

10. **Online Ordering Gap:** Dining has the highest number of records without online ordering, with 77 records.

## 📈 Visualizations

The analysis includes the following visualizations:

- Total votes by restaurant category
- Table booking availability pie chart
- Top five restaurants by customer votes
- Restaurant ratings vs. customer votes scatter plot
- Average ratings by restaurant category
- Restaurant category distribution
- Restaurant rating distribution histogram
- Average cost comparison by restaurant category
- Online ordering vs. restaurant ratings box plot
- Online ordering availability heatmap

## 📁 Repository Structure

```text
zomato-restaurant-data-analysis/
│
├── dataset/
│   └── zomato_data.csv
│
├── notebooks/
│   └── Zomato_EDA_Project.ipynb
│
├── reports/
│   └── Zomato_EDA_Project_Report.pdf
│
├── visualizations/
│
├── README.md
└── requirements.txt
```

## 🚀 How to Run This Project

### 1. Clone the repository

```bash
git clone https://github.com/manojakumarsahu618/zomato-restaurant-data-analysis.git
```

### 2. Navigate to the project directory

```bash
cd zomato-restaurant-data-analysis
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

### 5. Run the analysis

Open `notebooks/Zomato_EDA_Project.ipynb` and execute the cells to reproduce the analysis.

## 💡 Conclusion

This project demonstrates how Python can be used to clean, explore, analyze, and visualize restaurant data to identify useful business patterns.

The analysis highlights the dominance of Dining restaurants, differences in customer ratings across categories, pricing variations, and the association between online ordering and restaurant ratings.

These findings can help demonstrate how data analysis supports business understanding and data-driven decision-making.

**Note:** All findings are based on the 148 records included in the supplied dataset. They should not be generalized to the entire Zomato restaurant population. The analysis identifies associations and descriptive patterns, not causal relationships.

## 👨‍💻 Author

**Manoja Kumar Sahu**

MCA Graduate | Aspiring Data Analyst

- GitHub: [manojakumarsahu618](https://github.com/manojakumarsahu618)
- LinkedIn: [Manoja Kumar Sahu](https://linkedin.com/in/manoja-kumar-sahu-7477642aa)

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback!
