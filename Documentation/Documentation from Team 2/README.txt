Sprint Backlog

Setup for this Project
-	Visual Studio 2022 was used for this project.
-	Pull down this project from GitHub and run it.
-	The local database is located under ScavengeRUS>ScavengeRUS.db
-	You will need SQLite to open this database. You can download it at: https://sqlitebrowser.org/dl/ 


Test Admin Account:
UN: waltonca@etsu.edu
PW: YMXH@9J!72kM6Em


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
		 Discord	(Communication outside of class)
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


Team Members of Bobbums
-	Caleb (Steven) Rains	Product Owner
-	Michael Ng			Scrum Master
-	Charles Kinser		Developer
-	Jacob Klucher		Developer
-	Steven Errett		Developer
-	Kincaid Young		Developer

-	Richard Cashion		Product Owner
-	Benjamin Smith		Scrum Master
-	Thomas Foreman		Developer
-	Caleb Hammond		Developer
-	Dionte Jones		Developer
-	Maxwell Key			Developer
- 	Matthew Lockard		Developer



Planned Sprint Goals from Team Bobbums.
- We included this here to help you get a feel of how our team adjusted and gradually sped up our pace for this project.
- Sprint 1
	o Get the previous semester’s code working on everyone’s Visual Studio.
	o Attempt deployment to a Virtual Machine.
	o Get the Github set up ✓
	o Get everyone connected to the Github ✓
	o Get test accounts and give out the logins for at least one admin account and at least one player account ✓
	o A.3.c Cannot change status or creation date (Can modify start time before it has started, status changes automatically)
	o Edit the start time ✓
	o Cannot edit creation date ✓

- Sprint 2
	o Add player functionality. 
	o Complete hunts, with tasks being completable.
	o Once an account is created, you only need access code to login. ✓
		o A secure email can send an email to the user containing the URL to the hunt. If SMS cannot be set up, it will also contain the access code. ✓
 		o If SMS can be set up, verify that the SMS sends the access code successfully to multiple carriers. (SMS could not be set up)
		o Get an idea on whether or not QR codes are doable. If they are doable, show how it works and how it integrates into the solution. ✓ (Unable to implement currently)
		o Admins can send players email/SMS automatically upon creating an account. ✓
Sprint 3 
	o Continue adding more player functionality
	o Create email to text functionality ✓
  	o Prevent multiple inputs on batch creation ✓
  		o Prevent duplicated users ✓
  	o Popup message on batch completion saying failure/success ✓
  		o Add details to the created batch popup on how many accounts were created ✓

- Sprint 4
	o Successfully merge both projects together to create a mega-project that combines the functionality of both teams. ✓













