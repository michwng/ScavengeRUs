Sprint Backlog

Setup for this Project
-	Visual Studio 2022 was used for this project.
-	Pull down this project from GitHub and run it.
-	The local database is located under ScavengeRUS>ScavengeRUS.db

-	You will need SQLite to open this database. You can download it at: https://sqlitebrowser.org/dl/ 


Team Members of Team B.O.B.
-	Caleb Rains		Product Owner
-	Michael Ng		Scrum Master
-	Charles Kinser	Developer
-	Jacob Klucher	Developer
-	Steven Errett	Developer
-	Kincaid Young	Developer



Planned Sprint Goals
- Sprint 1
	o Get the previous semester’s code working on everyone’s Visual Studio.
	o Attempt deployment to a Virtual Machine.
- Sprint 2
	o Add player functionality. 
	o Complete hunts, with tasks being completable.
- Sprint 3 
	o QR code API
	o Geolocation API
- Sprint 4
	o …



Structure
- This project is based off of the ASP.NET MVC (Model-View-Controller). 
- You can learn this in Advanced Web Development – a required class for IT Concentrations.
- The following technologies are used:
	o Coding
		 C#
		 .NET 6
		 SQLite (SQL)
		 CSHTML
		 CSS
		 JavaScript
	o Organization
		 Trello	(Free)
		 Discord
		 GitHub 	(Version Control)
	o IDE
		 Visual Studio 2022
		 SQLite Browser




Coding Standards
- C#
	o Standard C# documentation.
	o https://www.geeksforgeeks.org/c-sharp-coding-standards/# 
- CSHTML
	o (There’s no documentation from my research, so here’s a resource)
	o Razor syntax reference for ASP.NET Core | Microsoft Learn


What Each Folder Has
BucHunt-Master
	//Folder
	ScavengeRUs
		//Folder
		ScavengeRUS.db-wal
		ScavengeRUS.db-shm
		ScavengRUS
			//Data Base file
		appsetting.Development
			//JSON
		appsettings
			//JSON containing keys and database pathing
			
		Program.cs
			//C# Source file
			Libraries:
				Microsoft.AspNetCore.Identity
				Microsoft.EntityFrameworkCore
				ScavengeRUs.Data
				ScavengeRUs.Models.Entities
				ScavengeRUs.Services
		Readme
			//Text Document
		ScavengeRUs.csproj
			//VS file
		obj
			//Folder
			staticwebassets.pack.sentinel
				//Sentinel File
			project.assets
				//JSON
			project.nuget.cache
				//CACHE file
			ScavengeRUs.csproj.nuget.dgspec
				//JSON
			ScavengeRUs.csproj.nuget.g.props
				//Project Property file
			ScavengeRUs.scproj.nuget.g.targets
				//Project Targets file
			Debug
				//Folder
				net6.0
					//Folder
					ScavengeRUs.csproj.BuildWithSkipAnalyzers
						//Build file
					_IsIncrementalBuild
						//File
					ScavengeRUs.csproj.CopyComplete
						//Copy Complete file
					ScavengeRUs.csproj.FileListAbsolute
						//Text document
					ScavengeRUs.genruntimeconfig.cache
						//CACHE file
					apphost
						//Application
					ScavengeRUs.dll
						//Application extension
					ScavengeRUs.pdb
						//Program Debug Document
					staticwebassets.build
						//JSON
					staticwebassets.development
						//JSON
					ScavengeRUs.csproj.CoreCompileInputs.cache
						//CACHE file
					
		bin
			//Folder
		wwwroot
			//Folder
		Services
			//Folder
			Functions.cs
				//C# source file
				Contains useful functions, including email sending
			IUserRepository.cs
				//C# source file
				Libraries:
					Microsoft.AspNetCore.Mvc
					ScavengeRUs.Models.Entities
			UserRepository.cs
				//C# source file
				Libraries:
					Microsoft.AspNetCore.Identity
					Microsoft.AspNetCore.Mvc
					Microsoft.EntityFrameworkCore
					Microsoft.EntityFrameworkCore.Metadata.Conventions
					ScavengeRUs.Data
					ScavendeRUs.Models.Entities
					System.Security.Claims
			ApplicationDbContext.cs
				//C# source file
				Libraries: 
					Microsoft.AspNetCore.Identity
					Microsoft.AspNetCore.Identity.EntityFrameworkCore
					Microsoft.EntityFrameworkCore
					ScavengeRUs.Models.Entities
			HuntRepository.cs
				//C# source file
				Libraries:
					Microsoft.AspNetCore.Mvc
					Microsoft.EntityFrameworkCore
					ScavengeRUs.Data
					ScavengeRUs.Model.Entities
					System.Runtime.InteropServices
			IHuntRepository.cs
				//C# source file
				Libraries:
					ScavengeRUs.Models.Entities
		Views
			//Folder
		Controllers
			//Folder
			HomeController.cs
				//C# source file
			HuntController.cs
				//C# source file
			LocationsController.cs
				//C# source file
			QuestionsController.cs
				//C# source file
			UserController.cs
				//C# source file
				Libraries: 
					Microsoft.AspNetCore.Authorization
					Microsoft.AspNetCore.Identity
					Microsoft.AspNetCore.Mvc
					ScavengeRUs.Models.Entities
					ScavengeRUs.Services	
					System
					System.Security.Claims
				Admin only controller, handles admin portal functions
		Data
			//Folder
			Migrations
				//Folder
		Models
			//Folder
			ErrorViewModel.cs
				//C# source file
			Entities
				//Folder
				AccessCode.cs
					//C# source file
				ApplicationUser.cs
					//C# source file
				Hunt.cs
					//C# source file
				HuntLocation.cs
					//C# source file
				Location.cs
					//C# source file
			Enums
				//Folder
				Roles.cs
					//C# source file
		Properties
			//Folder
		.config
			//Folder
			Hold the config file for .NET
			dotnet-tools.json
				//JSON
				Short file that lists some configurations for .NET
		Areas
			//Folder
			Identity
				//Folder
				Pages
					//Folder
					Account
						//Folder
						Login.cshtml.cs
							//C# source file
						Register.cshtml.cs
							//C# source file
					_ValidationScriptsPartial.cshtml
					_ViewImports.cshtml
					_ViewStart.cshtml
	.gitattributes
	.gitignore
	azurepipeline.yml
	database.md
		//md file
		Contains somewhat out of date information about the database. It was done before us
	Planning
		//Text document
	Problems I Have Faced in the Buc Hunt Project
	README
	ScavengeRUs.sln
	Documentation
		//Folder
		Server_Documentationupdated
		databaseimage
		Publishing_the_project

What Each Library Is:
 -	AspNetCore.Authorization: https://learn.microsoft.com/en-us/aspnet/core/security/authorization/introduction?view=aspnetcore-7.0
 -	AspNetCore.Identity: https://learn.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-7.0&tabs=visual-studio 
 -	AspNetCore.Identity.EntityFrameworkCore: See above
 -	AspNetCore.Mvc: https://learn.microsoft.com/en-us/aspnet/core/mvc/overview?view=aspnetcore-7.0
 -	EntityFrameworkCore: https://learn.microsoft.com/en-us/ef/core/
 -	EntityFrameworkCore.Metadata.Conventions: https://learn.microsoft.com/en-us/dotnet/api/microsoft.entityframeworkcore.metadata.conventions?view=efcore-6.0
 -	System: https://learn.microsoft.com/en-us/dotnet/api/system?view=net-8.0
 -	System.Runtime.InteropServices: https://learn.microsoft.com/en-us/dotnet/api/system.runtime.interopservices?view=net-7.0
 -	System.Security.Claims: https://learn.microsoft.com/en-us/dotnet/api/system.security.claims?view=net-7.0 













