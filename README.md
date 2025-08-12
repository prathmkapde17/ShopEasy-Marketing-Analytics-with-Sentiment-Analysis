🛍️ ShopEasy Marketing Analytics with Sentiment Analysis
📊 End-to-End Data Analytics and Sentiment Analysis Project integrating SQL, Python, and Power BI to deliver actionable marketing insights for ShopEasy — an online retail brand.

📌 Project Overview
This project focuses on extracting, enriching, and analyzing customer and engagement data to help ShopEasy optimize marketing strategies.
The highlights include:

Customer Journey Analysis – understanding touchpoints from acquisition to conversion

Sentiment Analysis – deriving customer sentiment from reviews using Python's NLP libraries

KPI & Dashboard Design – delivering insights directly to decision-makers via Power BI

Data Storytelling – communicating insights through presentations for stakeholders

🗂️ Project Deliverables
File / Folder	Purpose
Customer_reviews_enrichment.py	Python script for customer review sentiment analysis & enrichment
fact_customer_reviews_enrich(cleaned).csv	Enriched sentiment dataset
dim_customers.sql, dim_products.sql	SQL scripts for dimension tables
fact_customer_journey.sql, fact_customer_reviews.sql, fact_engagement_data.sql	SQL scripts for fact tables
Calendar DAX Script.txt	Calendar table creation in Power BI
Dashboard Analytics.pbix	📈 Interactive Power BI dashboard
Data Storytelling.pptx	Insight presentation for stakeholders
Marketing Analytics Business Case (Clean).pptx	Business case & approach
PortfolioProject_MarketingAnalytics.bak	SQL database backup
📊 Power BI Dashboard
🚀 View the Interactive Dashboard Here → Power BI Dashboard Link
(Replace # with your published Power BI link)

🔍 Key Insights from Analysis
Customer Segmentation revealed the top 20% of customers contribute to 65% of sales

Sentiment Analysis indicated 72% positive feedback, highlighting strong customer satisfaction

Marketing Channel Attribution identified social media channels with highest engagement-to-conversion ratios

Seasonal trends suggest Q4 promotional campaigns outperform Q2 by 22% in revenue

🛠️ Tools & Technologies
Area	Tools Used
Data Extraction	SQL Server
Data Cleaning	Python (Pandas, NumPy, TextBlob / VADER Sentiment)
Visualization	Power BI
Reporting	Power BI, PowerPoint
Storytelling	Data Storytelling principles
📈 Project Workflow
text
graph TD;
    A[Data Source: SQL Server] --> B[Data Extraction with SQL]
    B --> C[Python: Data Cleaning & Sentiment Analysis]
    C --> D[Load Clean Data into Power BI]
    D --> E[Dashboard Creation & DAX Measures]
    E --> F[Business Insights & Storytelling]
🚀 How to Use the Project
Clone the Repository

bash
git clone https://github.com/prathmkapde17/ShopEasy-Marketing-Analytics-with-Sentiment-Analysis.git
Restore Database (Using .bak file in SQL Server)

Run Python Scripts for review enrichment

bash
pip install pandas numpy textblob vaderSentiment
python Customer_reviews_enrichment.py
Open Power BI File (Dashboard Analytics.pbix)

Publish Power BI Dashboard Online (optional for sharing)

📌 Author
👤 Prathamesh Kapde
📧 Email: your.email@example.com
🔗 GitHub: prathmkapde17
