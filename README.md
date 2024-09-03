# Event Registration App

## Overview

This Event Registration App is a simple CRUD application developed using ASP.NET Core Blazor with .NET 8. The application allows users to view available events, manage events, and register for events. Authentication and role-based authorization ensure that only authorized users can perform certain actions, such as creating or deleting events.

## Features

- **Landing Page**: Displays a list of available events.
- **Event Management**: Admins can create, read, update, and delete events.
- **User Registration**: Users can register for events, with each registration generating a unique reference number.
- **Role-Based Authorization**: Admins have full control over event management, while regular users can only view and register for events.
- **Validation**: Implemented using Blazored.FluentValidation for robust form validation.

## Technology Stack

- **ASP.NET Core Blazor (Server-Side)**: Provides a rich, interactive UI.
- **SQLite**: A lightweight, file-based database.
- **Entity Framework Core (EFCore)**: Manages database access and ORM.
- **Bootstrap**: Ensures a responsive and modern UI design.
- **ASP.NET Identity**: Handles authentication and authorization.
- **Blazored.FluentValidation**: Manages validation logic within Blazor forms.

## Installation

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or any other IDE supporting .NET 8

### Steps

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
