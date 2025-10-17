# **SSIS Data Warehouse ETL Pipeline**

This project shows how to build a **Data Warehouse ETL pipeline** using **SQL Server Integration Services (SSIS)**.  
It extracts data from different sources, transforms it, and loads it into a **Data Warehouse** for reporting and analysis.

---

## 🧭 **Overview**

The goal of this project is to demonstrate the full **ETL (Extract, Transform, Load)** process used in data warehousing.  
Data is loaded from multiple sources, cleaned and transformed in SSIS, and stored in **Fact** and **Dimension** tables following the **Star Schema** model.

---

## 🏗️ **Architecture**

The solution follows four main layers:

1. **Source Layer** – Raw data from files or databases  
2. **Staging Layer** – Temporary area for initial data load and cleanup  
3. **Data Warehouse Layer** – Transformed data organized into facts and dimensions  
4. **Presentation Layer** – Ready for visualization in Power BI  

---

## ⚙️ **ETL Process**

1. **Extract:** Load data from flat files and databases  
2. **Transform:** Apply cleaning, lookups, and business rules  
3. **Load:** Insert data into warehouse tables (dimensions and facts)  

---

## 📂 **Project Structure**

SSIS-Data-Warehouse-ETL-Pipeline/

│

├── DataSources/ # Input data files

├── SSISPackages/ # SSIS project and .dtsx files

├── SQLScripts/ # SQL scripts for tables and schema

├── Reporting/ # Power Bi reports

└── README.md # Project documentation

---

## 🧰 **Tools & Technologies**

| **Category** | **Tools** |
|---------------|-----------|
| ETL | SQL Server Integration Services (SSIS) |
| Database | Microsoft SQL Server |
| Language | T-SQL |
| Modeling | Star Schema |
| Visualization | Power BI |
| IDE | Visual Studio |

---

## 👨‍💻 Author

### Mohamed Abdelsalam
Aspiring Data Engineer
