# AtliQ Sales Insights Tableau Dashboard

This is a project I replicated from Codebasics PowerBI YouTube playlist, but instead of using PowerBI,  
I created the dashboard in **Tableau Public**. You can find the original playlist link below for reference:

[Codebasics Youtube Playlist](https://youtube.com/playlist?list=PLeo1K3hjS3uva8pk1FI3iK9kCOKQdz1I9)

[Live Dashboard Link](https://public.tableau.com/views/SalesInsightsProject_17556326312940/Dashboard-RevenueAnalysis?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Problem Statement

AtliQ Hardware is a company that delivers computer hardware & peripheral products to its clients and has several branches across India.  
The Sales Director of the company is facing challenges in understanding the overall performance of the business.  
Sales are not meeting expectations and are gradually declining.  

When he reaches out to regional managers for updates, they often sugarcoat the reality and send large Excel files,  
making it hard to extract insights. Humans are not comfortable consuming raw numbers in spreadsheets,  
which leads to further frustration.  

---

## Solution

To overcome this, the Sales Director decided to build a **dashboard** for converting raw data into interactive visuals,  
allowing him to make **data-driven decisions**.  

In my project, instead of PowerBI, I built this solution in **Tableau Public** using the same dataset and methodology.

---

### AIMS Grid

Using the AIMS grid project management tool, we defined the purpose, stakeholders, end results,  
and success criteria of the project.

<img src="https://github.com/sayed-m-shah/Sales-Insight-Tableau-Project/blob/main/DATASET/AIMS.jpg" width="550" class="center">

---

## Steps Followed in this Project

1. Performed a high-level analysis of the dataset in **MySQL Workbench** to understand the data better.  
2. Used **Python** to extract data from MySQL and export it into a single Excel `.xlsx` file,  
   where each table was stored in a **separate sheet** with its table name.  
3. Imported the Excel file into **Tableau Public**.  
4. Performed ETL and data cleaning within Tableau (handling null values, formatting fields, etc.).  
5. Ensured consistency in transaction currency by applying conversion where necessary.  
6. Created required **calculated fields and measures** in Tableau for KPI metrics.  
7. Designed multiple visuals and combined them into an interactive Tableau Dashboard.  
8. Shared the dashboard on Tableau Public for interactive exploration.  

---

## Final Results

#### 🔎 Dashboard Navigation Demo (Tableau Public)

<img src="https://github.com/sayed-m-shah/Sales-Insight-Tableau-Project/blob/main/DATASET/Sales%20Insight%20Dashboard%20Gif.gif" width="1000" class="center">

#### Data Model

<img src="https://github.com/sayed-m-shah/Sales-Insight-Tableau-Project/blob/main/DATASET/Sales%20Insight%20Data%20Model.png" width="600" class="center">

#### Revenue Analysis Dashboard

<img src="https://github.com/sayed-m-shah/Sales-Insight-Tableau-Project/blob/main/DATASET/Revenue%20Analysis.png" width="550" class="center">

#### Profit Analysis Dashboard

<img src="https://github.com/sayed-m-shah/Sales-Insight-Tableau-Project/blob/main/DATASET/Profit%20Analysis.png" width="550" class="center">


---

## Tools & Technologies Used

- **MySQL Workbench** – for SQL queries and database handling  
- **Python (Pandas, SQLAlchemy, OpenPyXL)** – to export SQL tables into Excel file  
- **Excel** – intermediate data storage (one file, multiple sheets)  
- **Tableau Public** – for visualization and dashboarding  

---

## Key Learnings

- Learned how to integrate **SQL + Python + Excel + Tableau** workflow.  
- Practiced ETL (Extract, Transform, Load) process and data cleaning.  
- Improved dashboard design skills in Tableau.  
- Understood how business problems can be translated into **data-driven insights**.  

---
