## ETL Data Processing Project (Python + MySQL + Airflow)

A project implementing a basic Extract, Transform, Load (ETL) pipeline. The pipeline uses a Python script to perform the data processing logic, a Bash wrapper for execution, and an SQL file to define and populate the target database schema.

Every 5 min whatever the data is updated into the database that data is exceeds the restriction limit then push into the csv file.


## 🚀 Features

    🐍 ETL Logic: Uses a Python script (etl_script.py) to handle data extraction, transformation, and loading.

    🛢️ Database Setup: Provides SQL statements in database.txt to initialize the etl_example database and sample_data table.

    🐚 Wrapper Script: Utilizes wrapper_script.sh to execute the Python ETL script.

    ⚙️ Orchestration Ready: Includes etl_dag.py, suggesting readiness for deployment in an orchestrator like Apache Airflow.

## 🛠️ Tech Stack

    Core Logic: Python 3

    Database: MySQL

    Execution: Bash Shell Scripting

    Scheduler : Apache Airflow 

## 📦 Project Structure

etl-data-processor/

├── wrapper_script.sh # Bash wrapper to execute the ETL script

├── etl_script.py     # Main Python script for E-T-L logic

├── etl_dag.py        # DAG file (likely for Airflow Scheduler)

├── database.txt      # SQL DDL/DML for database setup and initial data

└── README.md         # Project documentation (this file)

