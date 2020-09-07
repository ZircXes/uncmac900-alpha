# Analytics Maturity Model


### Learning Objectives
```
1. Understand that the level of sophistication for analytics differ across organizations
2. Understand what these levels entail
```

## Analytics Pipeline (repeat from Analytics Pipeline)
[DIAGRAM]
Events --> Captured Events --> Storage --> Monitoring --> Processing --> Reporting and Visualization

## Maturity

### Level 0

Data is maintained in relational (SQL Server, Postgres, Oracle, Access) databases within business departments.  Analytics pipelines are often built using "glue code" with Visual Basic scripts and Excel workbooks, typically by someone in the business department that owns the database.  There is no version control of the data or the code.  Code development and execution is performed on the same machine, typically by a single individual.  There is no monitoring.

### Level 1

Data is maintained in relational databases, but is also sourced into a central data environment for analytics.  Code for the pipelines are written in languages such as Java or Python, and is version controlled. Code execution occurs in a computational environment suited for data manipulation (eg, Spark or GPUs).  There is basic (ad-hoc) monitoring for data quality.  IT controls are minimally applied, and many analysts have write access to production systems.  

### Level 2

Code is encapsulated into "jobs" and is orchestrated via a job runner such as Airflow or Argo.  Data governance and IT standards exist and are manually applied.  Analysts partner with IT resources to make changes to production pipelines.  

### Level 3

Job orchestration is configured as code and versioned.  All code moves through an automated continuous integration/continuous delivery pipeline.  IT controls are automatically enforced at through this promotion pipeline.  Data governance standards are materialized into code libraries that allow the data pipelines to communicate their compliance with a central data quality server at run time.  

## Typical Organizational Maturity

Most large organizations have pockets of Level 0 maturity, but also have capabilities for level 1 or 2 maturity.  If you find yourself in a level 0 organization, it is an opportunity to mature the analytics capabilities.  If you find yourself in a level 2 or level 3, you can deliver analytics faster and with better controls.  
