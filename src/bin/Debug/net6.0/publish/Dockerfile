FROM mcr.microsoft.com/dotnet/aspnet:6.0
WORKDIR /publish
COPY . .
EXPOSE 5186
ENTRYPOINT ["dotnet", "myWebApp.dll"]