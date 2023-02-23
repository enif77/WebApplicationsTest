# WebApplications Test

Used for "advanced" IIS setup.

The main app is in .NET Framework 4.8. The "new" app is in .NET 6.0. The task is to run them both under a
single domain. The main app will run as "myapp.com", the second one as "myapp.com/new".

## Setup steps

- Create a new site for the .NET Framework, aka the "main", app.
- Copy the .NET 6 application somewhere, wher IIS can reach it (wwwroot/...).
- Add a new app under the main app site with alias "new".
