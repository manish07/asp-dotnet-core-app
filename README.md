To create APS.NET Core web app project:
1. dotnet new webapp -o aspnetcoreapp
2. dotnet dev-certs https --trust
3. cd aspnetcoreapp
dotnet watch run

To commit the code to github repository:
1. git init
2. git add *
3. git commit -m "asp dotnet core web app"
4. git remote add origin git@github.com:manish07/asp-dotnet-core-app.git
5. git push --set-upstream origin master
