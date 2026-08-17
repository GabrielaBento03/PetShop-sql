Petshop Database - SQL
Project developed for the Database Systems Fundamentals discipline, focusing on data modeling and manipulation within a relational environment.

📋 About the Project
This project simulates a petshop management system. The focus was to structure the database from table modeling to creating analytical queries for report extraction using MySQL.

🚀 Features
Relational Modeling: Complete table structure (cliente, produto, pedido, item_pedido) with referential integrity through Primary and Foreign Keys.

Advanced Queries: Use of JOINs (INNER and LEFT) for data cross-referencing.

Aggregations: Application of GROUP BY and HAVING for metric calculations.

Automated Reports: Creation of a VIEW (vw_relatorio_final) to facilitate the analysis of total spending per customer and purchase volume.

🛠️ Technologies Used
DBMS: MySQL

Tool: MySQL Workbench

📦 How to Run
Make sure you have MySQL installed on your machine.

Open MySQL Workbench and start a new connection.

Open the script_banco_petshop.sql file contained in this repository.

Select all the code and click the execute button (lightning bolt ⚡).

To view the final report, run: SELECT * FROM vw_relatorio_final;

👥 Authors
Project developed in partnership by:

Gabriela Bento de Oliveira

Eduarda Liz
