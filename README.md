# AnimalClient.Solution

A web application that consumes a home-made API. The app should have the following features:
CRUD functionality for animals model.
Exploration of Pagination
Search functionality
By Thomas McDowell
Technologies Used:
C#
.NET 6.0
MySql
ASP.NET Core
Entity Framework Core
Pomelo Entity Framework Core
HTML Helpers
Swashbuckle API visualizer
Description:
This is a web application that consumes and serves as the front end of a home-brew API built with VS Code for the 12th Independent Code Review for Epicodus Coding program. This application pairs with Animal_Shelter_API.Solution in my repositories. It features a database popluated with famous test-subject animals. A user should be able to see the animals in the database by using the various buttons to return views. Views are populated by sending GET, POST, PUT, or DELETE (and SEARCH, but that's really just GET again) to the API and database to pull information.

Setup/Installation Req's:
Set Up and Run Project
Clone this repo.
Open the terminal and navigate to this project's production directory called "AnimalShelterClient".
Within the production directory "AnimalShelterClient", create a new file called appsettings.json.
Within appsettings.json, put in the following code
{
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning"
    }
  },
  "AllowedHosts": "*"
}
Open Animal_Shelter_API by repeating steps 1-4 in that program's README, then run dotnet run in that program's production directory, "AnimalShelterApi".

Run dotnet watch run to view the project in your web browser. Enter your computer password when prompted.
