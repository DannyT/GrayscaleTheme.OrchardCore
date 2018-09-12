# GrayscaleTheme.OrchardCore

## Setup - Visual Studio 2017

* Open the .sln
* Build all (`ctrl + shift + b`), this may take a few minutes as all the nuget packages are installed.
* Run Cms.Web

## Setup - dotnet cli

* Install the latest versions of the .NET Core SDK from this page https://www.microsoft.com/net/download/core
* Run the following commands from the root
```sh
dotnet build
cd Cms.Web
dotnet run
```
* open http://localhost:59511