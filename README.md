# SQL queries

Scenario

You are a security professional at a large organization. Part of your job is to investigate security issues to help keep the system secure. You recently discovered some potential security issues that involve login attempts and employee machines.

Your task is to examine the organization’s data in their employees and log_in_attempts tables. You’ll need to use SQL filters to retrieve records from different datasets and investigate the potential security issues.

Apply filters to SQL queries

Project description:
In this project, we are leveraging SQL to probe various tables in an organization's database, with a specific focus on analyzing suspicious login activity and collecting data regarding employees from certain departments. This investigation aims to mitigate security vulnerabilities and streamline targeted system updates.

Retrieve after hours failed login attempts:
![image](https://github.com/aperezgomez/SQL_queries/assets/120771676/2ade6ed4-8fb7-4218-9cf5-0426885976b3)



This query selects all records from the log_in_attempts table where the login_time is after 18:00 and the login attempt was not successful.

Retrieve login attempts on specific dates:
![image](https://github.com/aperezgomez/SQL_queries/assets/120771676/15b62f14-d2d8-4722-8d11-c74570838302)


The query gathers all records from the log_in_attempts table where the login_date matches either 2022-05-08 or 2022-05-09.

Retrieve login attempts outside of Mexico:
![image](https://github.com/aperezgomez/SQL_queries/assets/120771676/fc79efdf-eeac-4979-979f-6caa9034d267)


This SQL statement retrieves all login attempts from countries other than Mexico. Using the LIKE operator with wildcards ensures that both "MEX" and "MEXICO" are excluded from the results.

Retrieve employees in Marketing:
![image](https://github.com/aperezgomez/SQL_queries/assets/120771676/19fc092e-74d4-4fbd-993a-c7bd90b9b622)


This query identifies employees in the Marketing department and further narrows the results to those whose office starts with "East".

Retrieve employees in Finance or Sales:
![image](https://github.com/aperezgomez/SQL_queries/assets/120771676/71773ec1-01dc-4d8c-bcef-e11760402c1c)


This command fetches details of employees from the Finance and Sales departments.

Retrieve all employees not in IT:
![image](https://github.com/aperezgomez/SQL_queries/assets/120771676/97e53fa8-5b64-402e-a0fb-0c3ba37dd834)


The query lists employees who do not belong to the Information Technology department by using the NOT LIKE operator.

Summary:
SQL is a powerful tool that provides the ability to extract precise data based on various conditions. In this project, we utilized SQL to filter out crucial data concerning potential security threats, and identify employees for targeted system updates. Efficiently using SQL can aid in the proactive handling of cybersecurity threats, ensuring the integrity and safety of organizational systems.




