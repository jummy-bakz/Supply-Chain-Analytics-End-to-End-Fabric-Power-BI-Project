# Supply-Chain-Analytics-End-to-End-Fabric-Power-BI-Project

This project demonstrates a complete end-to-end data solution using Microsoft Fabric, SQL, PySpark Notebooks, and Power BI.
It covers ingestion, transformation, modeling, and storytelling through dashboards.

🔹 Project Summary

Built a Medallion Architecture (Bronze → Silver → Gold).

Used MySQL for schema design, parsing, and incremental logic.

Used Fabric Notebooks (PySpark) for data cleansing, transformation, enrichment, and modeling.

Created a Gold semantic model in Fabric.

Delivered a 3-page executive dashboard in Power BI with drill-through, tooltips, KPIs, and trend analysis.

🛠️ Tech Stack


SQL (MySQL) – schema, views, incremental stored procedure


Microsoft Fabric – Lakehouse, Pipelines, Notebooks


PySpark – data cleansing & transformations


Power BI – semantic model, DAX, dashboard design


Data modeling – Fact/Dimension schema



📂 What’s Included in This Repo


README documentation (full architecture + explanations)


Dashboard screenshots (Executive, Product, Region)


SQL scripts (schema, view, incremental stored procedure)


Data validation examples


End-to-end pipeline explanation


Medallion model breakdown (Bronze, Silver, Gold)


Power BI insights summary



🧱 Data Engineering Highlights


Built MySQL view to parse raw CSV fields into typed columns


Created an incremental stored procedure to fetch new rows only


Implemented Bronze → Silver → Gold transformations


Added date breakdowns (OrderDate, Month, Revenue, etc.)


Cleaned duplicates, enforced schema, standardized values


Built dimensional model:


factSales


dimProduct


dimGeo


dimDate





📊 Dashboard Features
Page 1: Executive Overview


KPI cards


Monthly revenue trend


Top products & states


Matrix with bar-in-matrix for quick scanning


Page 2: Product Details (Drill-Through)


Revenue trend


Revenue share gauge


City/state matrix


Page 3: Region Details (Drill-Through)


State-level drill down


Product performance


City matrix



✔️ Skills Demonstrated


Data modeling & transformation


SQL engineering (views, procedures, incremental logic)


Fabric notebooks & PySpark


Analytics engineering (Gold semantic model)


Power BI storytelling


Data validation & quality checks



📥 Files

All files are packaged inside the ZIP folder:


