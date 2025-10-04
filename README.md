# Razor101 - ASP.NET Core Razor Pages Sample Project

This project serves as a template demonstration of ASP.NET Core Razor Pages, showcasing the fundamental concepts and best practices of Razor Pages development. It's built using .NET 9.0 and follows modern web development patterns.

## 🚀 Features

- Clean and organized Razor Pages project structure
- Bootstrap-based responsive design
- jQuery integration for client-side functionality
- Built-in error handling and privacy pages
- Static file serving (CSS, JavaScript, images)
- Preconfigured development and production settings

## 🛠️ Prerequisites

- [.NET 9.0 SDK](https://dotnet.microsoft.com/download) or later
- Any code editor (recommended: Visual Studio 2022 or Visual Studio Code)

## 📦 Project Structure

```
Razor101/
├── Pages/                     # Razor Pages and their code-behind files
│   ├── Shared/               # Shared layouts and partial views
│   ├── _ViewImports.cshtml   # Common imports and tag helpers
│   ├── _ViewStart.cshtml     # Common view configurations
│   ├── Error.cshtml          # Error handling page
│   ├── Index.cshtml          # Home page
│   └── Privacy.cshtml        # Privacy policy page
├── wwwroot/                   # Static files (CSS, JS, images)
│   ├── css/                  # Stylesheet files
│   ├── js/                   # JavaScript files
│   └── lib/                  # Third-party libraries
├── Properties/                # Project properties and launch settings
├── appsettings.json          # Application settings
└── Program.cs                # Application entry point and configuration
```

## 🚀 Getting Started

1. Clone the repository:
   ```powershell
   git clone [repository-url]
   cd Razor101
   ```

2. Restore dependencies:
   ```powershell
   dotnet restore
   ```

3. Run the application:
   ```powershell
   dotnet run
   ```

4. Open your browser and navigate to:
   ```
   https://localhost:5001
   ```

## 🔧 Configuration

The project includes two configuration files:
- `appsettings.json`: Main configuration file
- `appsettings.Development.json`: Development-specific settings

## 🧪 Features Demonstrated

1. **Razor Pages**: Model-View-ViewModel pattern with code-behind files
2. **Layouts**: Shared layout using `_Layout.cshtml`
3. **Static Files**: Serving static content from wwwroot
4. **Error Handling**: Custom error page implementation
5. **Configuration**: Environment-based settings management
6. **Tag Helpers**: Built-in ASP.NET Core tag helpers usage

## 🔒 Security

- Built-in security features of ASP.NET Core
- HTTPS configuration
- Anti-forgery token validation
- Secure cookie handling

## 🎯 Best Practices Implemented

- Clean separation of concerns
- Proper use of layouts and partial views
- Environment-specific configurations
- Built-in dependency injection
- Proper static file organization

## 📚 Learning Resources

- [Official ASP.NET Core Documentation](https://docs.microsoft.com/en-us/aspnet/core/)
- [Razor Pages Documentation](https://docs.microsoft.com/en-us/aspnet/core/razor-pages/)
- [ASP.NET Core Tutorials](https://docs.microsoft.com/en-us/aspnet/core/tutorials/)

## License
[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This project is licensed under the MIT License. See the [`LICENSE`](LICENSE) file for details.
