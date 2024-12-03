```shell
dotnet add package Microsoft.EntityFrameworkCore --version 8.0.1
dotnet add package Microsoft.EntityFrameworkCore.Relational --version  8.0.1
dotnet add package Microsoft.EntityFrameworkCore.Tools --version 8.0.1
dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore --version 8.0.1
dotnet add package Pomelo.EntityFrameworkCore.MySql --version 8.0.1
dotnet tool install --global dotnet-ef
dotnet ef migrations add InitialCreate
dotnet ef database update
export PATH=$PATH:~/.dotnet/tools
P@ssw0rd

cd EJBCA
docker compose up -d 
```