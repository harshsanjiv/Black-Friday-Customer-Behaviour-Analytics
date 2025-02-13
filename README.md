# Black Friday Customer Behavior Analytics

## **Project Overview**
This project analyzes Black Friday sales data to evaluate customer behavior, promotional effectiveness, and demographic influences. By utilizing statistical methodologies like A/B testing, ANOVA, and Difference-in-Differences (DiD), it provides actionable insights to optimize marketing strategies.

---

## **Key Objectives**
1. Understand customer purchasing behavior across demographics.
2. Evaluate the effectiveness of Black Friday promotions.
3. Provide insights for targeted marketing campaigns.

---

## **Key Steps**
1. **Data Cleaning and Feature Engineering**:
   - Handled missing data.
   - Created a new feature for total customer purchase.

2. **Statistical Analysis**:
   - **A/B Testing**: Compared male and female purchasing behavior.
   - **DiD Analysis**: Assessed promotion impact between city categories.
   - **ANOVA**: Examined age group influence on purchase behavior.

3. **Data Visualization**:
   - Boxplots and barplots to visualize key trends.

---

## **Statistical Insights**
1. **A/B Testing**:
   - T-statistic and p-value indicate if there's a statistically significant difference between male and female purchase behavior.

2. **Difference-in-Differences (DiD)**:
   - Estimated the effect of promotions by comparing city categories A and B.

3. **ANOVA**:
   - Confirmed whether average purchase behavior differs across age groups.

---

## **Visualizations**
- Boxplots for purchases by gender and age.
- Barplot for average purchases by city category.

---

## **Technologies Used**
- **Python**: pandas, numpy, scipy, statsmodels, matplotlib, seaborn
- **Statistical Methods**: A/B Testing, ANOVA, Difference-in-Differences
- **Data**: [Black Friday Sales Dataset](https://www.kaggle.com/sdolezel/black-friday)

---

## **How to Run the Code**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/black-friday-analytics.git
2. pip install -r requirements.txt
3. python analysis.py
4. Replace train.csv with the dataset file if needed.

