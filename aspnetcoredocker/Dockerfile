
FROM microsoft/aspnetcore:1.1
LABEL Name=aspnetcoredocker Version=0.0.1 
ARG source=./bin/Debug/netcoreapp1.1/publish
WORKDIR /app
EXPOSE 3000
COPY $source .
ENTRYPOINT dotnet aspnetcoredocker.dll
