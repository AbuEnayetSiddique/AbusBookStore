2023-03-02
1505
Started Assignment 02 in-class on the lab computer
Set up the ASP.NET MVC w/ core 3.1 
HTTPS enabled, individual account autheutication.. on Razor
Reviewed the Areas folder, Controller, Model and Views.
And..
1505...in startup.cs on the line 33
removed options for default identify
options => options.SignIn.RequireConfirmedAccount = true

1510
Tested the the App.. ran it good...tested links
Action items:
	-Modify the Navigation
	-Update the copyright...from static to dynamic date


1516
Modified the default welcome message...tested.
review the route in Startup.cs

1539
Tried to make Github Repository but did not work
Reboot

1551
The Application ran
The wired thing is got 61 cahanges while commiting to Github

2023-03-03
1516
confirmed the repo is created ... and tested the app

1525
Created the README.md file and pulled that

1626
Modified the welcome page

2023-03-09
1416
pulled project from Github and ran

1425
downloaded Journal theme- bootstrap.css file from bootswatch.com website
added to the wwwroot->lib->bootstrap->dist->css folder
ran the program, nothging changed

1450
modified _Layout.cshtml file
ran the application and changed the outlook.
modified the _LoginPartial.cshtml

2023-03-10
1015
Started working on Adding and Modifing part
ran the application...working

1021
Added three new Projects, named-
	AbusBoos.DataAccess
	AbusBooks.Models
	AbusBooks.Utility

1042
Shift the Data folder to AbusBooks.DataAccess

Installed-
	Microsoft.EntityFrameworkCore.Relational version: 3.1.32
	Microsoft.EntityFrameworkCore.SqlServer version:3.1.32

Deleted the Migration Folder.

Installed Nuget Packege: 
	Identity.EntityFrameworkCore Version: 1.2.7

Modified the namespace in ApplicationDbContext.cs to AbusBookStore.DataAccess.Data
Deleted Startup.cs files from new projects
Moved Model folder to AbusBooks.Moldels folder
Modified ErrorViewModel.cs
Added the Project Reference
Renamed Model folder to ViedModels
Changed the namespace to AbusBookStore.Models.ViewModels
Built the project and got 13 error.