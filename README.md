# Menu-Catalog

Menu-Catalog is an ASP.NET Core web project (targeting .NET 10) that manages a menu/catalog for items. This repository contains the application source, views, and configuration used during development.

## Contents
- Source code (C#)
- Views (Razor)
- Configuration files

## Prerequisites
- .NET 10 SDK: https://dotnet.microsoft.com/
- Visual Studio 2026 or later (recommended) or any compatible IDE

## Build and run
From the repository root:

dotnet build
dotnet run --project <path-to-startup-project>

Or open the solution in Visual Studio and run using IIS Express or the Project run configuration.

## Commit & push to GitHub
Replace USER/REPO with your values (example below uses MariosAdamou/Menu-Catalog).

git remote add origin https://github.com/MariosAdamou/Menu-Catalog.git
git branch -M main
git add -A
git commit -m "Initial commit with project files and README"
git push -u origin main

If the remote rejects the push due to branch conflicts and you want to force your local state to remote (warning: this will overwrite remote history):

git push -u origin main --force

## Notes
- Ensure you have permission to push to https://github.com/MariosAdamou/Menu-Catalog.git and that any required credentials (PAT or SSH key) are configured.
- Use force push only if you understand it will overwrite remote history.

## License
Add a license file if you want to make the project open source.

---
Created by the project maintainer.
