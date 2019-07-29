# OdeToFood
A repo for the ASP.NET Core Pluralsight Project.

The following are additional notes and FAQs about the course. 

## Module 1

### Clip 2 - Creating the Project

To create, build, and run a project like we do in Visual Studio, you can use the command line:

```text
dotnet new razor
dotnet build
dotnet run
```

Some environments, like Visul Stuio Code, can also detect .NET Core projects and automatically add support to build and run from the VS Code menus. 

### Clip 3 - Saving changes and refreshing

VS uses some magic to automatically retart the web server when you make changes to source code files. If you are using command line tools, you can do the same using:

`dotnet watch run`

... instead of ...

`dotnet run`

### Clip 7 - Adding the OdeToFood.Core project

You can use `dotnet` to create the class library. Place this at the same folder level as the OdeToFood project. 

```
dotnet new classlib
```

## Module 2

### Clip 3 

Bootstrap 4 does not include glyphicons. [Font Awesome](https://fontawesome.com/start) is a good replacement. Once you've included the Font Awesome stylesheet into your _Layout page with a link tag, the icons are just as easy to use. To show a search icon, for example:

&lt;i class="fas fa-search"&gt;&lt;/i&gt;

## Module 4

### Clip 2 

Alternatives to MSSQL 




