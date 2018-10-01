# dotnetpwa
Example of **PWA** (Progressive Web App) with login and registration.
Made with **asp .net core**, **Identity**, **MySQL** and hosted on **Azure** (free account).

Live preview: https://dotnetpwa.azurewebsites.net/

Installation steps: 
 1. Setup  **MySQL** on your localhost
 2. Setup connection string as environment variable: 
 
     Variable name:
    `MYSQLCONNSTR_localdb`
   
    Variable value: `server=localhost;port=3306;database=aspnetcore_identity_pwa;uid=kedzior;password=kedzior`
    
    When using **Azure**, use activate **MySQL In App**
    
 3. `dotnet restore`
 4. `dotnet run`
 
**Have fun!**

<img width="774" alt="login-kedzior io dotnetpwa" src="https://user-images.githubusercontent.com/40808369/46316019-41f0c380-c5cf-11e8-9c84-4bf0d0bb4864.png">
