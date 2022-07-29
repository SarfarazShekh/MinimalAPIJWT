# Minimal API JWT
 1. Create empty .net core project (.net 6)
 2. Install Required depenedancies
 ##### Add Entity Frame work core From Nuget
		      -Microsoft.EntityFrameworkCore
		      -Microsoft.EntityFrameworkCore.design
		      -Microsoft.EntityFrameworkCore.SqlServer
	       -Microsoft.EntityFrameworkCore.SqlLit
 ##### Install the dotnet tool use pakage console manager
         - dotnet tool istall --global dotnet-ef
Add the connection string in appsetting.jsnon

###### Add JWT Token
		      - Microsoft.AspNetCore.Authentication.JwtBearer 
		      - System.IdentityModel.Tokens.Jwt
##### For Open API
	      	- Microsoft.OpenApi
##### Swagger 
	      	- Swashbuckle.AspNetCore
		      - Swashbuckle.AspNetCore.Swagger
