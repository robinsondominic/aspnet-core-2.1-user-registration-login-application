# aspnet-core-2.1-user-registration-login-application
C# user registration and login scaffolded web application in asp.net core 2.1 that connects to MySQL database
Open source C# asp.net core Razor membership application. C# code can be used to develop any web application that requires user login and registration , a user dashboard or admin dashboard.

Features
- User Login
- User Registration
- Forgot/Reset Password
- User Dashboard

to use: 
- download complete solution or code.
- create your database on any local or remote mysql server using mysqlworkbench or phpadmin
- setup connection string settings in appsettings.json: example  "ConnectionStrings": {
    "DefaultConnection": "server=127.0.0.1;port=3306;database=db-name;uid=db-user;password=db-password"
  }
- in the project folder delete the Migrations folder (see below screen print)
- ![image](https://user-images.githubusercontent.com/98348781/173124497-15abb800-8b16-4944-a7e5-f10fa8011221.png)
- open package manager console from view menu in visual studio (see below)
- ![image](https://user-images.githubusercontent.com/98348781/173124656-08d14908-785d-404e-8254-a38e69362147.png)
- create new migirations code based on mySql database using the below command
- Add-Migration InitialCreate
- Once the above code is executed you will see the Migration folder created on the root of the project (see screen print below)
- ![image](https://user-images.githubusercontent.com/98348781/173124870-3d186874-e049-4924-a36e-2f44a2f20009.png)
- Now execute the below command to apply new migration code to the database.
- PM> Update-Database
- ASP.Net Core application is ready with identity server implemented using  MySQL as back-end database. You can execute the application and see the login and Register pages working.
