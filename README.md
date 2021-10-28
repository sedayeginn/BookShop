# BookShop

## Web

## Infrastructure
Install-Package Microsoft.EntityframeworkCore
Install-Package Microsoft.Entityframeworkcore.sqlserver
Install-package Ardalis.Specification.Entityframeworkcore
Install-package Microsoft.AspNetCore.Identity.EntityFrameworkCore


Package Manager Console
-------------------------
Add-Migration Identity -Context AppIdentityDbContext -OutputDir "Identity/Migrations"
update-database -Context AppIdentityDbContext
Add-Migration App -Context ApplicationDbContext -OutputDir "Data/Migrations"
update-database -Context ApplicationDbContext

## ApplicationCore
Install-Package Ardalis.Specification

