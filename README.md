# BookAPI

A minimal ASP.NET Core Web API (BookAPI) demonstrating a simple book library project setup using .NET 10.

Prerequisites

- .NET 10 SDK installed: https://dotnet.microsoft.com/en-us/download
- (Optional) Visual Studio 2026 or later to open the solution file: BookAPI.slnx

Build and run

From the repository root:

- Build: dotnet build BookAPI.csproj
- Run: dotnet run --project BookAPI.csproj

Or open BookAPI.slnx in Visual Studio and start the project.

Default endpoints

- GET /  — returns "Hello World!"

Launch URLs (from Properties/launchSettings.json)

- http://localhost:5247
- https://localhost:7109

Quick test

- curl http://localhost:5247/

Project layout (important files)

- Program.cs — minimal API entry point
- Properties/launchSettings.json — local launch URLs
- BookAPI.csproj — project file
- README.md — this file

Notes

This repository contains a minimal starter Web API. Extend Program.cs with controllers or endpoints to implement book management features (CRUD) as needed.
