Created to practice on .NET 8 and SQL Server Management Studio 

More specifically this project is showcasing CRUD on an API level and using Entity Framework 

Some noteable aspects of this project: 
1. DTOs to cut down on what the user Gets from the database upon request and what the user can Post to the database
2. Connecting to SQL Server and creating database tables from code using the "dotnet ef migrations add init" command and "dotnet ef database update"
3. Using OOP and MVC principles for project folder structure and code organization
4. HttpGet and HttpPost using the [ApiController] attribute and [Route] attribute 
5. IActionResult for returning status codes and messages to the user
6. Mappers to map DTOs to Models and vice versa
