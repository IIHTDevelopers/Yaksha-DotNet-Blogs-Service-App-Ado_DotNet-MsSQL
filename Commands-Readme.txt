* On command prompt, cd into your project folder (cd <Your-Project-folder>).

* To connect SQL  server from terminal:
	( BlogSApp / sqlcmd -S localhost -U sa -P pass@word1)
		
* To create database from terminal - 
	1> Create Database BlogsApp_Db
	2> Go

* To create table from terminal - 
	1> Create Table Blog(BlogId int,Title varchar(250),Content varchar(250));
	2> Go
	1> Select * From Blog
	2>Go

* To build your project use command:
	
	( BlogsApp / dotnet build )

* To launch your application, Run the following command to run the application:
	
	( Blogs / dotnet run )

* To run the test cases in CMD, Run the following command to test the application:

	( BlogsApp.Tests / dotnet test --logger "console;verbosity=detailed")
  (You can run this command multiple times to identify the test case status,and refactor code  to make maximum test cases passed before final submission)

* To ensure your code is saved and available for later use, remember to use the CTRL+Shift+B command on your code IDE.
   This will push or save the updated contents in the internal git/repository.
   It is also important to use CTRL+Shift+B before the final submission to evaluate the code quality.