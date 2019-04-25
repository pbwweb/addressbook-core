# Introduction 
AddressBook.Core is a Solution developed to show Clean Code Architecture, Asp.Net Core and CQRS Pattern, app is design to use dotnet core 2.2 and entity framework 2.1. WebUI Project and DAL can be switched with easy for any datastore provider, including MSSQL, Postgres and MySQL

# Requirements
1. .NET Core SDK 2.2.203 (download from: .NET Core SDK [**Download link**](https://dotnet.microsoft.com/download/dotnet-core/2.2)) If you are in VS2019
2. .NET Core SDK 2.2.106 (download from: .NET Core SDK [**Download link**](https://dotnet.microsoft.com/download/dotnet-core/2.2)) If you are in VS2017 or VS for Mac
3. Visual Studio IDE VS2017 or VS2019 or VS for Mac (latest update recommended), we we using latest C# features **or**,
4. Visual Studio Code
5. MSSQL Express ([**Download link**](hhttps://www.microsoft.com/en-us/sql-server/sql-server-editions-express))

# Getting Started
1. Clone the online repo using IDE or git CLI
2. Modify connection string in appsettings.json to reflect the correct datastore (this solution is running with MSSQL Express, you must point to your dev server/ mac/ pc)
3. if needed change your datastore provider to SQL Lite
3. Remove any migration folder in Persistance Project and run migration to populate Db
4. dotnet run to run AB.WebUI Project

# Clone with Git Bash

1. Download the git tool: [**Download link**](https://git-scm.com/downloads)
2. open bash in temp folder C:\Temp
3. git clone  
4. cd addressbook.core/src/ab.webui
5. dotnet restore
6. dotnet run
