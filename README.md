Note; this may not run on first use.
For me to get this to build successfully after download from the website, I followed advice here https://docs.microsoft.com/en-us/nuget/consume-packages/package-restore-troubleshooting and went to Tools > NuGet Package Manager > Package Manager Settings menu command, setting both options under Package Restore, and selecting OK. This didn't work for me, but I tried the second (command prompt, running "dotnet restore" it still didn't work. Failing these I Right Clicked the Solution > Manage NuGet Packages and scrolled down until I found the file that seemed to be causing issue in the error - "Microsoft.Net.Compilers", and updated it. This led to another error with obj\xx\yy.dll (can't remember the exact text), but that was resolved through restarting visual studio.

---
topic: ASP.NET and SQL Database sample for Azure App Service
languages:
  - aspx-csharp
products:
  - Azure App Service
  - Azure Web Apps
---

# ASP.NET and SQL Database sample for Azure App Service

This is a sample application that you can use to follow along with the tutorial at 
[Create an ASP.NET app in Azure with SQL Database](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-web-tutorial-dotnet-sqldatabase/). 

## License

See [LICENSE](LICENSE).

## Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
  
