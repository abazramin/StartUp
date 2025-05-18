# ASP.NET Core Clean Start Up Template

🚀 **A ready-to-use, clean architecture starter template for ASP.NET Core projects — designed to save time and boost productivity.**

---

## 🎯 Project Purpose

This repository aims to minimize setup time when starting a new ASP.NET Core project by providing a well-structured, scalable foundation based on best practices such as N-Tier Architecture, Dependency Injection, and Unit of Work. It’s ideal for developers who want a clean and maintainable codebase from the beginning.

---

## 🧱 Project Structure

The solution follows a multi-layered architecture:

##Solution
###│
###├── Presentation --> Web Layer (API Controllers)
###├── Business --> Business Logic Layer (Interfaces & Services)
###├── DataAccess --> Database Layer (DbContext, Repositories)
###├── Entities --> Domain Models
###├── Utilities --> Common Helpers & Utility Classes
###├── Core --> Shared Interfaces & Abstractions
###└── Application.sln --> Solution File


---

## ⚙️ Key Features

✅ **N-Tier Architecture** – Clean separation of concerns  
✅ **Dependency Injection (DI)** – Loosely coupled components for better testability  
✅ **Unit of Work + Repository Pattern** – Organized data access logic  
✅ **Pre-configured DbContext** – Located in the `DataAccess` layer  
✅ **Program.cs Ready** – Includes all essential service and middleware configurations  
✅ **Pre-set `appsettings.json`** – Includes ready-to-use connection string setup

---

## 🚀 Getting Started

1. **Clone the repository:**

```bash
git clone 'Link of Repo'
```
## Open the solution in Visual Studio or VS Code and Update application.json

"ConnectionStrings": {
  "DefaultConnection": "Server=.;Database=YourDbName;Trusted_Connection=True;"
}

## Apply EF Core migrations (if needed):

dotnet ef migrations add InitialCreate
dotnet ef database update

## Run the project

dotnet run


🧰 Requirements
.NET SDK 8.0 or later
Microsoft.AspNetCore.Identity.EntityFrameworkCore
Microsoft.AspNetCore.Identity.UI => if you want
Microsoft.EntityFrameworkCore.SqlServer
Microsoft.EntityFrameworkCore.Tools


🤝 Contributions are welcome and appreciated!

Fork the repository

Create a feature branch: git checkout -b feature/your-feature-name

Commit your changes

Open a Pull Request

👨‍💻 Author
[Abazr Amin]
Passionate .NET Developer focused on clean, scalable software design




