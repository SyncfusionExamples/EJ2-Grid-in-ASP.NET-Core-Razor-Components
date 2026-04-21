# Syncfusion DataGrid in ASP.NET Core Razor Components

## Repository Description

This repository contains a sample ASP.NET Core Razor Components application that demonstrates how to integrate and use the Syncfusion EJ2 DataGrid with server-side data binding and basic grid features.

## Project Overview

This sample application showcases the implementation of the Syncfusion UI DataGrid in an ASP.NET Core Razor Components (Blazor Server) environment. The Grid is configured using the `Syncfusion.EJ2.RazorComponents.Grids` namespace and is bound to data provided by a service class. The example is designed to help developers understand the basic setup, configuration, and rendering of the Syncfusion DataGrid component.

## Features

- Syncfusion EJ2 DataGrid integration in Razor Components
- Server-side data binding using `WeatherForecastService`
- Built-in paging and sorting support
- Strongly typed column definitions using `nameof`
- Clean and minimal configuration for learning purposes

## Prerequisites

- .NET SDK compatible with ASP.NET Core Razor Components
- Syncfusion EJ2 Razor Components NuGet packages
- Valid Syncfusion license or community license

## Running the Application

Follow the steps below to clone the repository, restore dependencies, build, and run the application.

1. Clone the repository and navigate to the project directory:

   ```bash
   git clone https://github.com/SyncfusionExamples/EJ2-Grid-in-ASP.NET-Core-Razor-Components.git
   cd EJ2-Grid-in-ASP.NET-Core-Razor-Components
   ```

2. Restore the required NuGet packages:

   ```bash
   dotnet restore
   ```

3. Run the application using the .NET CLI or Visual Studio:

   ```bash
   dotnet run
   ```

4. Navigate to `<localhost>/Grid/Default` and the Grid component will render in the browser.

## Additional Resources

- [Getting Started with ASP.NET Core using Razor pages in Visual Studio](https://ej2.syncfusion.com/aspnetcore/documentation/getting-started/razor-pages)
- [Syncfusion ASP.NET Core Grid Documentation](https://ej2.syncfusion.com/aspnetcore/documentation/grid)
- [Syncfusion ASP.NET Core Demos](https://ej2.syncfusion.com/aspnetcore)
