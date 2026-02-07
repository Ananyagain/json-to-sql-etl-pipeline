## JSON to SQL ETL Pipeline

This mini project demonstrates an end-to-end ETL (Extract, Transform, Load) pipeline using Python.

### 🔹 Data Entities
- Orders
- Customers
- Products

### 🔹 Project Workflow
1. Extract order, customer, and product data from JSON files
2. Normalize nested JSON into structured pandas DataFrames
3. Perform data cleaning and transformations
4. Truncate target SQL Server tables before loading
5. Load processed data into relational tables

### 🔹 Technologies Used
- Python
- Pandas
- SQL Server
- pyodbc / SQLAlchemy
- Jupyter Notebook

### 🔹 Key Features
- JSON parsing and normalization
- Data transformation using pandas
- SQL Server connectivity using pyodbc
- Table truncation before load to avoid duplicates
- Modular and reusable code structure

### 🔹 ETL Flow
1. Read JSON files into Python
2. Convert JSON to pandas DataFrames
3. Apply transformations and validations
4. Truncate target SQL tables if they exists
5. Load transformed data into SQL Server

### 🔹 Use Case
This project simulates a real-world data ingestion scenario where raw JSON data is transformed and stored in a relational database for further analytics and reporting.

### 🔹 Future Enhancements
- Add logging and exception handling
- Parameterize database connections
- Support multiple JSON schemas
- Automate the pipeline using scheduling tools

 pandas, and ingests the processed data into a SQL Server database.
