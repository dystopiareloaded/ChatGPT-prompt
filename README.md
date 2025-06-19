# ChatGPT-prompt - SQL

## 🧠 Prompt: Generate SQL Questions for Kaggle Dataset with Business Insights & Varying Complexity

I’m working on a Kaggle dataset and I want to generate real-world SQL questions to practice and analyze the data effectively. Act like a data analyst or BI developer. Based on the column names or sample data I provide, generate SQL questions in the following structure:

---

### 📊 Business Insights Questions  
- Focused on sales performance, user engagement, trends, top/bottom items, growth, etc.  
- *Example:* “List the top 5 best-selling products by total revenue.”

### 📐 Aggregations and Filtering  
- Use SQL functions like SUM, AVG, COUNT, MIN, MAX, GROUP BY, and HAVING.  
- *Example:* “What is the average purchase amount per customer?”

### 🔁 Subqueries and CTEs (WITH Clause)  
- Use nested queries or common table expressions to break down complex logic.  
- *Example:* “Use a WITH clause to find the monthly growth in new users.”

### 📆 Date & Time Based Analysis  
- Use SQL DATE, MONTH(), YEAR(), DATEDIFF(), WEEKDAY(), etc.  
- *Example:* “Calculate total orders placed on weekends vs weekdays.”

### 🪟 Window Functions  
- Use functions like ROW_NUMBER(), RANK(), DENSE_RANK(), LAG(), LEAD(), and NTILE().  
- *Example:* “Rank each movie by rating within its genre.”

---

✅ Include a mix of questions from Easy, Medium, to Advanced level, suitable for SQL learners aiming for job interviews and projects.

✅ For each question, return:
- A clear business-style problem statement  
- The SQL query  
- A short 🎯 objective or insight gained from the query

---

# ChatGPT - SQl small prompt

Act as a data analyst or BI developer. I am working on the "Movie Dataset: Budgets, Genres, Insights" from Kaggle.
Dataset link: ""
Please generate 20 SQL questions with solutions based on this dataset, ranging from easy to advanced levels. The questions should be framed in a business context and aim to uncover key business insights and analytics.

---

Act as a data analyst or BI developer.
I am working on the "Movie Dataset: Budgets, Genres, Insights" from Kaggle.
Dataset link: ""
Please generate 20 SQL questions with solutions for this dataset, each framed in a business context. The questions should range from easy to advanced levels and cover topics such as subqueries, window functions, CTEs, etc., with a strong focus on business insights and analytics.

---

# Chatgpt-prompt - Pandas (small)

## 🧠 Prompt: Act as a Data Analyst or BI Developer

I am working on the **"Movie Dataset: Budgets, Genres, Insights"** from Kaggle.  
**Dataset link**: ''

Please generate **20 Python (Pandas) data analysis questions with solutions** based on this dataset.  
Each question should be framed in a **business context** and range from **easy to advanced levels**.  
The questions should be organized into the following categories:

---

### 📊 Business Insights Questions
Explore real-world, decision-making insights such as:
- Revenue trends
- Genre performance
- Budgeting efficiency
- Director success rates
- Seasonal patterns

---

### 📈 Statistical Analysis Questions
Include tasks involving:
- Descriptive statistics (`mean`, `median`, `mode`, `std`, etc.)
- Distribution analysis
- Correlation between features (e.g., `budget` vs `revenue`)
- Confidence interval estimation (e.g., 95% CI for average revenue by genre or year)
- Outlier detection

---

### 🔬 Detailed Research / Evaluation Questions
Focus on deeper analytical breakdowns such as:
- Budget-to-revenue ratios
- Performance over decades
- Long-tail movie success
- Cross-analysis of genres, directors, and runtimes

---

### 📊 Visual-Driven EDA Questions
Use **Matplotlib** and/or **Seaborn** to visualize:
- Top genres, budgets, and revenues
- Distributions, trends over time
- Box plots, histograms, count plots, pair plots
- Correlation heatmaps

---

### ✅ For each question, please provide:
- A clear **business-style problem statement**
- The **Python (Pandas) code solution**
- A short 🎯 **objective or insight** derived from the analysis

---

# ChatGPT-prompt - Pandas

## ✅ Prompt: Generate Business Insight & Statistical Questions from a Kaggle Dataset in Pandas

> I am working on a Kaggle dataset using Python and Pandas. I want you to act like a data analyst and business consultant. Based on the dataset (I will share a few sample rows or column names), generate a comprehensive list of data analysis questions that fall into the following categories:

---

### 1. 📊 Business Insights Questions  
- Questions that a business team or decision-maker might ask.  
- Examples:  
  - What are the current sales trends over the last 6 months?  
  - Which are the top-performing categories by revenue?  
  - How does seasonal variation affect product sales?

---

### 2. 📈 Statistical Analysis Questions  
- Questions involving concepts like confidence intervals, standard deviation, hypothesis testing (t-test, ANOVA), correlation, etc.  
- Example:  
  - Can we be 95% confident that average monthly revenue exceeds $10,000?  
  - Is there a statistically significant difference in customer satisfaction scores across regions?

---

### 3. 🧠 Detailed Research/Evaluation Questions  
- In-depth queries that explore relationships between variables, distributional patterns, data drift, outliers, and missing values.  
- Example:  
  - How does customer retention differ by region and over time?  
  - Are there outliers in spending patterns that suggest fraudulent activity?

---

### 4. 🔎 Visual-Driven EDA Questions  
- Suggestions for visualizations to explore the data, including:  
  - Bar charts, heatmaps, box plots, violin plots, time series, KDE plots.  
- Example:  
  - Create a box plot to examine price distribution across product categories.  
  - Use a heatmap to explore correlations between numeric features.

---

## Another Prompt

## ✅ Prompt: Generate Business Insight & Statistical Questions from a Kaggle Dataset in Pandas

> I am working on a Kaggle dataset using Python and Pandas. I want you to act like a data analyst and business consultant. Based on the dataset (I will share a few sample rows or column names), generate a comprehensive list of data analysis questions that fall into the following categories:

---

### 1. 📊 Business Insights Questions  
Questions that a business team or decision-maker might ask.  
Examples:  
- What are the sales trends over time?  
- Which categories are top-performing in terms of revenue?  
- Provide a revenue breakdown by region or product.  
- Identify seasonal patterns in sales or user activity.

---

### 2. 📈 Statistical Analysis Questions  
Questions involving statistical concepts like confidence intervals, standard deviation, hypothesis testing (t-test, ANOVA), correlation, etc.  
Example:  
- Can we be 95% confident that the average monthly revenue exceeds $10,000?  
- What is the correlation between advertising spend and product sales?  
- Is there a significant difference in average spend between customer age groups?

---

### 3. 🧠 Detailed Research/Evaluation Questions  
In-depth queries that explore relationships between variables, distributional patterns, data drift, outliers, and missing values.  
Example:  
- How does customer retention differ by region and over time?  
- Are there anomalies or outliers in transaction data?  
- Has product preference shifted over the past 12 months?

---

### 4. 🔎 Visual-Driven EDA Questions  
Suggestions for visualizations to explore insights using charts and plots.  
Types of visualizations: bar chart, heatmap, box plot, violin plot, time series, KDE.  
Example:  
- Create a box plot to examine price distribution across product categories.  
- Use a heatmap to visualize correlation between numerical variables.  
- Plot a time series to detect monthly trends in user signups.

---

### ✅ Include:
- A mix of questions ranging from easy to advanced level complexity, suitable for beginner to expert data analysts.

### 📌 Return:
- 5–7 questions per category  
- Frame questions like real-world problems or business tasks  
- Avoid vague or overly simplistic queries (e.g., *“show all rows”*)

---

## Corrected Prompt for markdown

✅ Standard & Clear Version (Best for general use):
Can you give me the SQL queries along with their objectives in a README.md format, shared here in the chat—just like the previous SQL projects you remember from GitHub that I’ve done earlier?

💼 Professional Version (Best for formal or documentation requests):
Could you please provide the SQL queries along with their respective objectives in a README.md format here in the chat, similar to the previous SQL projects you recall from GitHub that I have completed?

---
