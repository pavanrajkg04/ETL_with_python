# ETL_with_python
Learn Extract, transform, load (ETL) using Python with exercises 

Extract, transform, load (ETL) is the main process through which enterprises gather information from data sources and replicate it to destinations like data warehouses for use with business intelligence (BI) tools. ETL tools and services allow enterprises to quickly set up a data pipeline and begin ingesting data.

Analysts and engineers can alternatively use programming languages like Python to build their own ETL pipelines. This allows them to customize and control every aspect of the pipeline, but a handmade pipeline also requires more time and effort to create and maintain.

# Python tools and frameworks for ETL
Python is an elegant, versatile language with an ecosystem of powerful modules and code libraries. Writing Python for ETL starts with knowledge of the relevant frameworks and libraries, such as workflow management utilities, libraries for accessing and extracting data, and fully-featured ETL toolkits.

# Workflow management
Workflow management is the process of designing, modifying, and monitoring workflow applications, which perform business tasks in sequence automatically. In the context of ETL, workflow management organizes engineering and maintenance activities, and workflow applications can also automate ETL tasks themselves. Two of the most popular workflow management tools are Airflow and Luigi.

# Airflow
Apache Airflow uses directed acyclic graphs (DAG) to describe relationships between tasks. In a DAG, individual tasks have both dependencies and dependents — they are directed — but following any sequence never results in looping back or revisiting a previous task — they are not cyclic.

Airflow provides a command-line interface (CLI) for sophisticated task graph operations and a graphical user interface (GUI) for monitoring and visualizing workflows.
