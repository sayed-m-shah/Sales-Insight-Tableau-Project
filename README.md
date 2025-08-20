# AtliQ Sales Insights Tableau Dashboard

This is a project I replicated from Codebasics PowerBI YouTube playlist, but instead of using PowerBI,  
I created the dashboard in **Tableau Public**. You can find the original playlist link below for reference:

[Codebasics Youtube Playlist](https://youtube.com/playlist?list=PLeo1K3hjS3uva8pk1FI3iK9kCOKQdz1I9)

[Live Report Link](https://public.tableau.com/app/profile/your-link-here)

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

<img src="https://github.com/Naveen-S6/AtliQ_Sales_Insigths_PowerBi/blob/main/DATASET/AIMS.jpg" width="550" class="center">

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

#### Initial Dashboard

<img src="https://github.com/Naveen-S6/AtliQ_Sales_Insigths_PowerBi/blob/main/DATASET/Inital_report.png" width="550" class="center">

#### Updated Dashboard

<img src="https://github.com/Naveen-S6/AtliQ_Sales_Insigths_PowerBi/blob/main/DATASET/Final_report.png" width="550" class="center">

#### Interactive Dashboard (Tableau Public)

<img src="https://github.com/Naveen-S6/AtliQ_Sales_Insigths_PowerBi/blob/main/DATASET/GIF.gif" width="600" class="center">

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
