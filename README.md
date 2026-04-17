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

## Running the application

1. Clone the application and open the command prompt from the downloaded location.

2. Run the below command line to Navigate the application folder.

   ```cmd
   cd EJ2Application
   ```

3. Run the below command line to restore the pacakges.

   ```cmd
   dotnet restore
   ```

4. Run the below commandline to build the application and it will open in the unique localhost port.

   ```cmd
   dotnet run
   ```

5. Navigate to `<localhost>/Grid/Default` and the Grid component will render in the browser.
