# 🛒 Retail Store Trial Analysis (Quantium Virtual Experience) 

## 📌 Project Overview

This project analyzed customer purchasing behavior and evaluated the effectiveness of a new chips display layout introduced in three trial stores. The goal was to identify the retailer's most valuable customers, understand purchasing patterns, and determine whether the new store layout resulted in a measurable increase in sales.

The analysis was divided into two parts:

- Customer Purchase Analysis
- Store Trial Evaluation

---

# 📂 Project Resources

| Resource | Description |
|----------|-------------|
| 📓 [Jupyter Notebook](Quatium_DA.ipynb) | Complete Python analysis including data cleaning, exploratory data analysis, statistical testing, and visualizations. |
| 📊 [Project Presentation](Retail_Analytics_Presentation.pdf) | Business presentation summarizing the analysis, key findings, visualizations, and recommendations. |
| 🏆 [Completion  Certificate](Quantium_DA_certificate.pdf) |   Certificate of completion for the Quantium Data Analytics Virtual Experience Program. |

---

## 📂 Dataset

The analysis was performed on a retail transaction dataset containing **260,000+ customer transactions** across multiple stores.

The dataset includes:

- Customer information
- Transaction details
- Product information
- Store information
- Sales values
- Transaction dates

---

# 📊 Customer Purchase Analysis

I first explored more than **260,000 transaction records** to understand how customers purchase chips across different stores. The data was cleaned by converting transaction dates into monthly periods, extracting brand names and pack sizes from product descriptions, and removing inconsistencies in the product information.

To understand customer behavior, I grouped customers by **Life Stage** and **Premium Customer** categories and analyzed their spending patterns, purchasing frequency, and quantity purchased. This helped identify which customer groups contributed the most to sales.

I also analyzed sales by **brand** and **pack size** to understand customer preferences and identify the products driving the highest revenue.

## 📌 Key Insights

- **Young Singles/Couples (Mainstream)** generated the highest overall sales, making them the most valuable customer segment.
- **Kettle, Doritos, and Pringles** were the highest-performing brands across the dataset.
- **175g and 150g** pack sizes generated the highest sales, suggesting customers preferred medium-sized packs.
- Although premium customers paid slightly higher prices, purchasing behavior across customer segments was generally similar, indicating that product preference had a stronger influence on sales than pricing alone.

These findings provide useful insights for marketing campaigns, product placement, and inventory planning.

---

# 📈 Store Trial Analysis

The second part of the project evaluated whether the new store layout improved sales in **trial stores 77, 86, and 88**.

Instead of comparing the trial stores with random stores, I first identified **control stores** that had similar sales performance before the trial. I compared monthly sales trends and sales volumes during the seven-month pre-trial period and selected the stores with the highest overall similarity scores.

The final control stores were:

| Trial Store | Control Store |
|-------------|---------------|
| 77 | 233 |
| 86 | 155 |
| 88 | 125 |

After selecting the control stores, I adjusted the control store sales to match the trial stores' pre-trial sales levels. This allowed me to compare the stores on a consistent baseline rather than being influenced by natural differences in store size.

I then measured how much the trial store sales differed from the expected sales during the trial period and compared those differences with the normal variation observed before the trial. This made it possible to determine whether any increase in sales was likely due to the new layout rather than normal month-to-month fluctuations.

---

# 📈 Results

## 🟢 Store 77

Store 77 showed the strongest trial performance. Sales were significantly higher than expected during **March and April 2019**, indicating that the new store layout had a positive and sustained impact on sales.

## 🟡 Store 86

Store 86 showed a significant increase in **March 2019**, but sales during February and April remained within the normal range. This suggests the layout may have had a positive effect, although the improvement was not consistent throughout the trial.

## 🟠 Store 88

Store 88 experienced a significant increase during **February 2019**, but the improvement was not maintained in the following months. The results suggest that external factors or local customer behavior may have influenced sales more than the new layout itself.

---

# 💼 Business Recommendations

Based on the analysis, **Store 77** provides the strongest evidence that the new layout improved sales and would be the best reference for a wider rollout.

Since **Stores 86 and 88** produced mixed results, I recommend investigating store-specific factors such as customer demographics, location, or promotional activities before expanding the layout to all stores.

From the customer analysis, the retailer should continue targeting **Young Singles/Couples (Mainstream)** through marketing campaigns while prioritizing shelf space and promotions for **Kettle, Doritos, and Pringles**. Maintaining strong inventory levels for the most popular pack sizes, particularly **175g and 150g**, could also help maximize sales.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

---

# 📈 Project Workflow

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Customer Segmentation
- Brand Performance Analysis
- Pack Size Analysis
- Monthly Sales Aggregation
- Control Store Selection
- Statistical Trial Evaluation
- Data Visualization
- Business Recommendations
