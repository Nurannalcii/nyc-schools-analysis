## Day 3 – Database Exploration (SQL via Python)

Analyzed NYC School data primarily using Python with embedded SQL queries.  
The focus was on exploring school distributions, English learners, and special education support using a PostgreSQL database connection.

### 🧠 Objectives
- Use Python to connect to the PostgreSQL database (`sqlalchemy`, `psycopg2`)
- Execute SQL queries directly in Jupyter Notebook  
- Load query results into pandas DataFrames for analysis  

### 🧹 Data Analysis Steps
- Counted total number of schools per borough  
- Calculated the average percentage of English Language Learners (ELL) per borough  
- Identified top 3 schools per borough with the highest percentage of special education students (`sped_percent`)  

### ⚙️ Tools Used
- Python (pandas, sqlalchemy, psycopg2)  
- SQL (PostgreSQL queries within Python cells)  
- Jupyter Notebook  

### 📊 Deliverables
- `day3_sql_analysis.ipynb` notebook (Python + SQL queries and outputs)  
- Short markdown summaries explaining each query result  

