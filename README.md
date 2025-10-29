# Expense Tracker - ASP.NET Core MVC

A comprehensive expense tracking application built with ASP.NET Core MVC that helps users manage their personal finances by tracking income and expenses.

## Features

- **Category Management**: Create, edit, and manage expense/income categories
- **Transaction Tracking**: Record and manage financial transactions
- **Dashboard**: Visual representation of financial data
- **Responsive Design**: Built with Bootstrap for a mobile-friendly experience

## Technology Stack

- **Framework**: ASP.NET Core MVC (.NET 9.0)
- **Database**: Entity Framework Core
- **Front-end**: 
  - Bootstrap
  - jQuery
  - JavaScript
- **Design Pattern**: MVC (Model-View-Controller)

## Project Structure

```
Expense Tracker/
├── Controllers/              # Contains MVC controllers
├── Models/                   # Data models and DbContext
├── Views/                    # MVC views
│   ├── Category/            # Category management views
│   ├── Dashboard/           # Dashboard views
│   ├── Transaction/         # Transaction management views
│   └── Shared/             # Shared layouts and partials
└── wwwroot/                 # Static files (CSS, JS, lib)
```

## Core Components

1. **Models**
   - Category: Represents expense/income categories
   - Transaction: Represents financial transactions
   - ApplicationDbContext: EF Core database context

2. **Controllers**
   - CategoryController: Manages category operations
   - TransactionController: Handles transaction operations
   - DashboardController: Handles dashboard view and data

3. **Views**
   - Category views for CRUD operations
   - Transaction views for financial entries
   - Dashboard view for data visualization
   - Shared layouts and partial views

## Getting Started

1. **Prerequisites**
   - .NET 9.0 SDK
   - Visual Studio 2022 or VS Code
   - SQL Server (LocalDB or higher)

2. **Setup**
   ```bash
   # Clone the repository
   git clone https://github.com/HimansuBajariya/ExpenssTracker.git

   # Navigate to project directory
   cd ExpenseTracker

   # Restore dependencies
   dotnet restore

   # Update database
   dotnet ef database update

   # Run the application
   dotnet run
   ```

3. **Database Migrations**
   - Initial migration is included
   - Use `dotnet ef migrations add [MigrationName]` for new changes
   - Apply migrations with `dotnet ef database update`

## Features in Detail

1. **Category Management**
   - Add/Edit/Delete categories
   - Categorize as Income or Expense
   - Title and icon selection for categories

2. **Transaction Management**
   - Record income and expenses
   - Date-based transaction entry
   - Category selection
   - Note/description for each transaction

3. **Dashboard**
   - Income vs Expense visualization
   - Recent transactions
   - Category-wise expense breakdown

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Bootstrap for responsive design
- Entity Framework Core for data access
- ASP.NET Core team for the amazing framework
