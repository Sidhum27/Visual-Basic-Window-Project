# Crud MVP WinForms

Basic system with CRUD operations made in .Net Framework 4.5 and SQL Server.

## What is this application about? 

This project consists of a small desktop application for Windows systems. The 
which allows the registration and update of Articles and their grouping by Categories. In addition
has a report section where you can visualize the data in a clear way and export them to other formats.
to other formats.

## How to run the application?

In order to run the program you need to have the following components installed.

* [Runtime of .Net Framework 4.5](https://www.microsoft.com/es-ar/download/details.aspx?id=42642)
* [SQL Server 2018/2019](https://www.microsoft.com/es-ar/download/details.aspx?id=101064)
* Microsoft SQL Server Management Studio (SSMS) *(optional)*.

Once installed, follow the steps below to test the application.

 
1. Open the `db_squema_and_data.min.sql` script from SSMS and run it to create the database.
to create the database.
2. Open the `crud-mvp-winforms.exe.config` file and set up the `crud-mvp-winforms.exe.config` string to point to your database.
connection string to point to your local database.
3. Run the `crud-mvp-winforms.exe` file and interact, that's all.

 

 
## Application architecture

This application has a Model-View-Presenter (MVP) type structure 
in which the presenters

Translated with DeepL.com (free version)