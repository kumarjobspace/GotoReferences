* Update-Package -reinstall
https://stackoverflow.com/questions/32578513/nuget-not-updating-project-references

NuGet package restore does not modify the project files. It just downloads and extracts the NuGet packages to the packages directory.

If you are trying to edit the packages.config file and then have the project's updated you would have to use the Package Manager Console and run:

How to install a package into all projects of a solution - Get-Project -All | Install-Package packageName
