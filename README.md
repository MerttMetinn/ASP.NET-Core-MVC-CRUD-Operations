# ASP.NET Core MVC CRUD App

This project is an ASP.NET Core MVC CRUD application using Entity Framework Core and SQL Server. It demonstrates the Model-View-Controller (MVC) architectural pattern, which is widely used in software design and is especially popular when combined with the ASP.NET framework.

## Features

- **ASP.NET Core MVC**: Utilizing the .NET 8 MVC template in Visual Studio 2022.
- **Entity Framework Core**: Code-first approach to create and manage the SQL Server database.
- **Bootstrap 5**: Used for styling and creating responsive web pages.

## Getting Started

### Prerequisites

- Visual Studio 2022 with .NET 8 SDK installed.
- SQL Server (local or remote).
- Basic knowledge of C#, ASP.NET MVC, and Entity Framework Core.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MerttMetinn/ASP.NET-Core-MVC-CRUD-Operations.git
   ```
2. **Open the project** in Visual Studio 2022.
3. **Install the required EF Core packages**:
   ```bash
   Install-Package Microsoft.EntityFrameworkCore
   Install-Package Microsoft.EntityFrameworkCore.SqlServer
   Install-Package Microsoft.EntityFrameworkCore.Tools
   ```
4. **Update the database connection string** in `appsettings.json` to point to your SQL Server instance.

### Usage

1. **Run the application** using Visual Studio or the `dotnet run` command.
2. The CRUD operations can be performed on the model entity, allowing for Create, Read, Update, and Delete functionalities.

### Screenshots

- **Add Student Page:**
![Add Student Page:](https://github.com/user-attachments/assets/229bb16f-9d76-45d7-8999-04e4b88190bc)

- **Student List Page:**
![Student List Page:](https://github.com/user-attachments/assets/be899a0a-67e4-40b6-b19c-1cac99e64ca1)

### Contributing

Feel free to submit issues or pull requests. For significant changes, please open an issue first to discuss what you would like to change.

### Acknowledgments

- Thanks to all contributors and the ASP.NET community for their support and resources.
