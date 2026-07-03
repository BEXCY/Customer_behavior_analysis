# Customer Shopping Behavior Analysis

## 📌 Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across various product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.

The workflow covers the full analytics lifecycle — from data cleaning and exploratory analysis in Python, to querying with MySQL, building an interactive Power BI dashboard, and summarizing findings in a business-ready report and presentation.

---

## 🗂 Dataset
- **Source:** Retail transaction dataset (customer purchases)
- **Size:** 3,900 records
- **Key fields:** Customer ID, Age, Gender, Location, Product Category, Purchase Amount, Payment Method, Subscription Status, Discount Applied, Review Rating, Season, Frequency of Purchase

---

## 🛠 Tools & Technologies
| Category            | Tools Used                     |
|----------------------|---------------------------------|
| Data Loading & EDA   | Python (Pandas, NumPy)          |
| Data Querying        | MySQL                           |
| Dashboarding         | Power BI                        |
| Reporting            | Microsoft Word                  |
| Presentation         | Microsoft PowerPoint            |

---

## 🔍 Project Workflow

1. **Data Loading**
   - Imported the raw dataset into Python using Pandas for initial inspection.

2. **Data Cleaning**
   - Handled missing values, duplicate records, and inconsistent formatting.
   - Standardized categorical fields (e.g., product categories, payment methods).

3. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions of spending, age groups, and product categories.
   - Identified trends in purchase frequency and subscription behavior.

4. **SQL Analysis**
   - Loaded cleaned data into MySQL.
   - Wrote SQL queries to answer business questions such as top-spending customer segments, category-wise revenue, and subscription trends.

5. **Dashboard Development**
   - Built an interactive Power BI dashboard to visualize KPIs, customer segments, and product performance.

6. **Reporting**
   - Summarized key findings and business recommendations in a written report.

7. **Presentation**
   - Created a PowerPoint deck to communicate insights to a non-technical/business audience.

---

## 📊 Dashboard
The Power BI dashboard highlights:
- Total revenue and average purchase value
- Customer segmentation by age, gender, and location
- Top-performing product categories
- Subscription vs. non-subscription spending behavior
- Seasonal purchase trends

*(Add a screenshot or GIF of the dashboard here)*

```
📁 dashboard/
   └── shopping_behavior_dashboard.pbix
   └── dashboard_screenshot.png
```

---

## 📈 Key Results & Insights
- Identified the top product categories driving the majority of revenue.
- Compared average purchase value between subscribed and non-subscribed customers.
- Uncovered seasonal spending patterns useful for planning promotions.
- Segmented customers by demographics to support targeted marketing strategies.

*(Update this section with your actual findings once your analysis is finalized)*

---

## ▶️ How to Run This Project

**1. Clone the repository**
```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

**2. Set up the Python environment**
```bash
pip install -r requirements.txt
```

**3. Run the data cleaning & EDA notebook**
```bash
jupyter notebook notebooks/eda_and_cleaning.ipynb
```

**4. Load data into MySQL**
- Import `data/cleaned_shopping_data.csv` into your MySQL instance.
- Run the queries in `sql/analysis_queries.sql`.

**5. Open the Power BI dashboard**
- Open `dashboard/shopping_behavior_dashboard.pbix` in Power BI Desktop.

**6. View the report and presentation**
- Report: `report/shopping_behavior_report.docx`
- Presentation: `presentation/shopping_behavior_summary.pptx`


## 🙋 Author
**Bexcy**
Data Analyst | Business Analyst
📧 bexcybiju352@gmail.com |
