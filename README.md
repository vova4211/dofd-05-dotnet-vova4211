[![CI Workflow](https://github.com/vova4211/dofd-05-dotnet-vova4211/actions/workflows/dotnet-desktop.yml/badge.svg)](https://github.com/vova4211/dofd-05-dotnet-vova4211/actions/workflows/dotnet-desktop.yml)
# Description
This project is the .Net backend part of an educational  project. It provides connection to DB, implements CRUD operations and sends responses to requests. 

## The DataBase
The database is managed by MS SQL Server.
The content can be created by script
```
  INSERT INTO [dbo].[Products] ([Name], [Price])
  VALUES ('Sugar',  32.0),
       ('Sault', 19.0),
       ('Bread', 20.0),
       ('Butter', 62.0),
       ('Milk', 32.0);
```
it ensures that five products are inserted with the original prices.
Connection string to DB should be provided in appsettings.json in ConnectionStrings section, under Default name.
