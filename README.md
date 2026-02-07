## JSON to SQL ETL Pipeline

This mini project demonstrates an end-to-end ETL (Extract, Transform, Load) pipeline using Python.

### 🔹 Project Overview
- Extracts data from JSON files
- Transforms JSON data into structured pandas DataFrames
- Performs data cleaning and transformations
- Loads the transformed data into SQL Server tables

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
