FROM mcr.microsoft.com/dotnet/sdk:8.0 AS build-env


WORKDIR /app

COPY bin/Release/net8.0/publish/ .

COPY ./bin/Debug/net8.0/ .

COPY Program.cs .
COPY PersonNumberVerifier.cs .

CMD ["dotnet", "persnrkontroll.dll"]
