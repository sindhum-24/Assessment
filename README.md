# Project - Automating Data Report Extraction for Self-Service Data Analysis

Data is essential for businesses to make decisions and run smoothly. Not just technical teams, but finance, accounting, and other non-technical teams also rely on it. This project demonstrates how automated reports enable non-technical teams to analyze data and identify patterns or insights without relying on technical support.

In the real world, businesses have databases that store all kinds of information - sales transactions, orders, payments, products, return and more—organized in multiple tables with proper infrastructure. To help non-technical teams analyze this data, data analysts extract the required information using SQL and provide them with reports.

For example, the Trust and Safety (TnS) team in an e-commerce company often needs to investigate orders or detect fraudulent activity. They may not have full access to technical tools or the database. Instead, data analysts extract the required information and provide it as CSV or Excel reports. Often this process is automated so that the reports are regularly delivered or stored in a shared folder or repository, making it easy for the teams to access and use them.

In this project, we demonstrate how this is achieved using SQL and Python by automating the execution of multiple SQL scripts and uploading the resulting data files to a repository. We are replicating this using a SQLite database, as it does not require setting up servers. In the real world, however, data analysts would connect to a database using drivers and set up data connections with host details, usernames, passwords, and other credentials. Some databases or applications also allow connecting Python via APIs to extract data directly.

In the Python script, we will also provide alternatives and explain how the same process is implemented in real-world scenarios. This includes connecting to actual databases using drivers, setting up data connections with host details and credentials, or using APIs to extract data directly.
