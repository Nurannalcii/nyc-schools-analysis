## Day 4 – Database Population (SAT Results Integration)

Integrated and cleaned the NYC SAT Results dataset using Python before appending it to the PostgreSQL database.  
The task focused on data quality checks, schema alignment, and connection setup via SQLAlchemy.

### 🧹 Data Cleaning Process
- Removed unrelated and empty fields (`internal_school_id`, `contact_extension`)  
- Converted SAT scores to numeric  
- Dropped invalid values (outside 200–800 range)  
- Normalized headers and dropped duplicates  

### 🧱 Schema Design
- Selected columns for database upload:  
  `dbn`, `school_name`, `sat_math_avg_score`, `sat_reading_avg_score`, `sat_writing_avg_score`  
- Ensured relational key consistency with `high_school_directory.dbn`  

### ⚙️ Tools Used
- Python (pandas, sqlalchemy, psycopg2)  
- PostgreSQL Database  
- Jupyter Notebook  

### 🗂 Deliverables
- `cleaned_sat_results.csv`  – cleaned dataset ready for upload  
- `sat_modeling.ipynb`  – Python script for data cleaning and database insertion  
- `schema_notes.md`  – documentation of schema and integration strategy  
