#PokemonReviewApp with WebApi

#packages
Microsoft.EntityFrameworkCore.SqlServer
Microsoft.EntityFrameworkCore.Tools
Microsoft.EntityFrameworkCore.Design
//AutoMapper
AutoMapper.Extensions.Microsoft.DependencyInjection

already Swashbuckle.AspNetCore

#Database *create dabase in SSMS, copy connettion string from SQL Server Object Explorer -? propoeries of DB and in the right down corner connection string...

##PM Add-Migration InitialCreate Update-Database


##PowerShell dotnet tool cd .\ReviewAppWebApi
dotnet ef migrations add init dotnet ef database update

#Developer PowerShell ##in search Developer PowerShell PS C:\Projects\RunGroopWebApp> cd .\ReviewAppWebApi
PS C:\Projects\RunGroopWebApp\RunGroopWebApp> dotnet run seeddata

#or https://marketplace.visualstudio.com/items?itemName=AdamRDriscoll.PowerShellToolsVS2022 download and install, and VIEW -> Terminal, i jest!

#install dotnet tool dotnet tool install --global dotnet-ef .NET 6 dotnet tool install --global dotnet-ef --version 6.*