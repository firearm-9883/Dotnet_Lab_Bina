#lab 1: Setup Environment

Activities: Setup Environment

• Open the integrated terminal. • Change directories (cd) to the folder that will contain the project folder. • Run the following commands: .NET Core CLI dotnet new webapi -o TodoApi cd TodoApi dotnet add package Microsoft.EntityFrameworkCore.SqlServer dotnet add package Microsoft.EntityFrameworkCore.InMemory code -r ../TodoApi • When a dialog box asks if you want to add required assets to the project, select Yes. The preceding commands: o Creates a new web API project and opens it in Visual Studio Code. o Adds the NuGet packages which are required in the next section.

URL: (http://localhost:5178/WeatherForecast/)

[{"date":"2024-02-05","temperatureC":11,"summary":"Balmy","temperatureF":51},{"date":"2024-02-06","temperatureC":31,"summary":"Balmy","temperatureF":87},{"date":"2024-02-07","temperatureC":14,"summary":"Chilly","temperatureF":57},{"date":"2024-02-08","temperatureC":-17,"summary":"Scorching","temperatureF":2},{"date":"2024-02-09","temperatureC":23,"summary":"Hot","temperatureF":73}]
