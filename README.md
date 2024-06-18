Welcome to your new dbt project!

### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Steps:
- Create a Big Query project.
- Create a dataset in that project.
- The customer orders data to create 3 tables.
- Creating a DBT project.
- Adding project service account JSON key to DBT project.
- Connecting Github repository with the project.
- Creating multiple models and executing it.
- Creating views and executing it by inline configuration. {{ config('materialized= view') }}
- Creating Macros for date partition.
- Testing for no orders at the beginning of the day.
- Creating snapshot for address change and utilizing it.

![project overview](https://github.com/karan8891/dbt-bq/blob/karan8891-patch-1/images/Project%20arch.jpg)
