# BlazorServer.Authentication

This is an example on how to implement Identity and AuthenticationStateProvider to an existing Blazor Server Application .

## Prerequisites
1. MySql Server Version 8.0.24
2. .NET 6
3. Visual Studio 2022

## Running the application
1. Clone the Repo
2. Open appsettings.json and change the ConnectionStrings according to your MySql Server user/password.
```
"ConnectionStrings": {
    "Default": "SERVER=localhost;database=authentication;user=your_user_name;password=your_password"
  }
```

3. On your Visual Studio Package Manager Console, run the following commands:
    - ```PM> add-migration "your migration name"```
    - ```PM> update-database ```
3. Build and Run the Application

4. Click on Register and provide the neccessary data needed, then click register. (*Password must be 5 characters long*)
