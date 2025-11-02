# 🏫 NYC Schools Data Analysis

**NYC Schools Data Analysis** – A Python-driven data pipeline for cleaning, transforming, and integrating NYC school datasets into a PostgreSQL database.

This project is part of the **Webeet.io Data Onboarding Program**.  
It demonstrates a complete **data pipeline** — from raw datasets to analysis and database integration using **Python and PostgreSQL**.

---

## 📅 Project Structure Overview

| Task | Folder | Description |
|------|---------|-------------|
| **Day 1** | `incident_analysis/` | Google Sheets analysis of school incidents |
| **Day 2** | `school_directory_exploration/` | Data cleaning and demographic exploration |
| **Day 3** | `database_queries/` | SQL + Python integration for data exploration |
| **Day 4** | `database_population/` | SAT results integration and database population |
| **Day 5** | — | Final wrap-up and GitHub publishing |

✅ **All stages are completed** — from raw data to structured analysis and database integration.  
📊 This repository represents a full data pipeline project using Python, SQL, and PostgreSQL.

---

## 🚀 Project Overview

- Cleaned, analyzed, and integrated NYC school datasets using Python and SQL  
- Built clear and consistent data structures aligned with PostgreSQL schema  
- Documented findings, key insights, and workflows in Markdown for each task  
- Organized project by **task-based structure** (not by days)

---

## 📂 Repository Structure

nyc-schools-analysis/
├── incident_analysis/ # Day 1: School incident analysis (Google Sheets)
│ ├── README.md # Findings, cleaning steps, insights
│ └── school-safety-report.csv # Source dataset used in analysis
│
├── school_directory_exploration/ # Day 2: School directory exploration
│ └── README.md # Data cleaning, Brooklyn filter, borough summaries
│
├── database_queries/ # Day 3: SQL exploration via Python
│ └── README.md # Queries, borough-level insights, ELL rates, etc.
│
├── database_population/ # Day 4: SAT results cleaning & DB integration
│ ├── README.md # Schema design + load plan
│ ├── cleaned_sat_results.csv # Cleaned SAT dataset
│ ├── sat_modeling.ipynb # Cleaning + append-to-database logic (Python)
│ └── schema_notes.md # Table structure / FK notes
│
├── requirements.txt # Python environment (pandas, SQLAlchemy, etc.)
└── README.md # Project overview (this file)

---

## 🧠 Tools & Technologies

| Library | Purpose / Why It Was Used |
|----------|----------------------------|
| **pandas** | To read CSV files, manipulate datasets as DataFrames, and execute SQL queries with `pd.read_sql()` |
| **numpy** | Provides numerical operations and supports Pandas in handling large numeric datasets |
| **sqlalchemy** | Enables Python-to-PostgreSQL connection via `create_engine` and allows SQL queries within Python |
| **psycopg2-binary** | PostgreSQL adapter used by SQLAlchemy to connect and execute queries |
| **matplotlib** | Used for data visualization — creating bar charts, line charts, and other plots (`plt.bar()`, `plt.plot()`) |
| **jupyter** | Required to run `.ipynb` notebooks and manage interactive data analysis workflows |
| **notebook** | Supports the Jupyter interface; ensures compatibility with JupyterLab and local notebook execution |

---

### 💾 Installation  

To install all required dependencies, run:

```bash
pip install -r requirements.txt

---

🧾 Key Deliverables
Clean and consistent datasets
SQL queries executed via Python
Data visualizations and insights
Final structured project ready for portfolio presentation


🌐 Author
Nuran Nalci
📎 GitHub Repository
