# Simple Clean Architecture skeleton template for .Net Core Web Applications.


Contains Visual Studio project template as zip and source code aswell.

To use the template in VS, copy the Template.zip to Users\{user}\Documents\Visual Studio 2019\Templates\ProjectTemplates and in VS19 click on File -> New -> Project -> Clean Architecture Backend Template
and give your project a name and select a location.

The new sln will contain a *Documentation* and a *src* folders. The *src* folder will contain your application's code organised in Clean Architecture in the following structure:
```
-ApplicationCore
--Application.csproj
--Domain.csproj
-Infrastructure
--Infrastructure.csproj
--Persistance.csporj
-Presentaion
--Api.csproj
```

Swagger included by default with basic setup.
