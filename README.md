# Tikitapp
A demo app based on selling concert tickets for bands on tour. This app is intended to demonstrate adding NodaTime, MJML and SASS/SCSS to a regular .NET 6 MVC web project.

## Running SQL Server with Docker

This app uses Entity Framework and Microsoft SQL Server.

To run SQL in a Docker image:

```bash
docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=p@ssw0rd" -p 1433:1433 -d mcr.microsoft.com/mssql/server:2019-latest
```

This will start a local Docker instance running SQL Server 2019 latest, with the `sa` password set to `p@ssw0rd`

