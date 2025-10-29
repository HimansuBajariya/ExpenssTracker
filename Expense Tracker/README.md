# Expense Tracker Application

A comprehensive web-based expense tracking application built with ASP.NET Core MVC that helps users manage their income and expenses effectively.

## Features

- **Dashboard**: 
  - Visual representation of expenses and income
  - Last 7 days transaction summary
  - Total Income/Expense statistics
  - Category-wise expense breakdown

- **Category Management**:
  - Create, Edit, and Delete expense/income categories
  - Category icons for visual identification
  - Support for both Expense and Income type categories

- **Transaction Management**:
  - Add, Edit, and Delete transactions
  - Categorize transactions
  - Add notes to transactions
  - Date-based transaction tracking

## Technology Stack

- **Framework**: ASP.NET Core MVC (.NET 9.0)
- **Database**: Microsoft SQL Server with Entity Framework Core
- **UI Components**: Syncfusion EJ2 ASP.NET Core
- **Frontend**: 
  - Bootstrap
  - jQuery
  - CSS3
  - HTML5

## Project Structure

```
├── Controllers/
│   ├── CategoryController.cs
│   ├── DashboardController.cs
│   ├── HomeController.cs
│   └── TransactionController.cs
├── Models/
│   ├── ApplicationDbContext.cs
│   ├── Category.cs
│   ├── Transaction.cs
│   └── ErrorViewModel.cs
├── Views/
│   ├── Category/
│   ├── Dashboard/
│   ├── Transaction/
│   └── Shared/
└── wwwroot/
    ├── css/
    ├── js/
    └── lib/
```

## Prerequisites

- .NET 9.0 SDK
- Microsoft SQL Server
- Visual Studio 2022 or later (recommended)

## Setup Instructions

1. Clone the repository
2. Update the connection string in `appsettings.json`
3. Open Package Manager Console and run:
   ```
   Update-Database
   ```
4. Build and run the application

## Key Features Implementation

### Categories
- Support for both expense and income categories
- Icon-based visual identification
- Data validation and error handling

### Transactions
- Amount validation
- Category-based organization
- Date tracking
- Note-taking capability

### Dashboard
- Recent transactions view
- Income vs Expense analysis
- Category-wise spending breakdown
- Date range based filtering

## Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.