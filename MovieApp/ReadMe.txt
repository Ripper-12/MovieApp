2024-02-01 11:30
There was a package restore failure error. tried resolving the error 
made a new projects and in the part 4 of scafolding again i got the same error several times.
12:00
reinstalled visual studio community 2022
started a new project faced the same error.

2024-02-03 17:00
uninstalled visual studio 2022 and
Downloaded and installed Visual studio enterprise 2022
Made a controller and added some control to the page
Made a view for the controller
added a data model class,
while doing scafolding an error occurred 
"Error:There was a error running the code generator.
package restore failed:Rolling back changes for 'MvcMovie'".

18:00
I tried making a new project but the same error persisted.

23:15
After hours of surfing through the internet i found the solution.
I added a new package source for NuGet packages
searched and installed all the required package, added the package to the project.
after adding all that i tried once again and it worked like a charm.

23:25
After migrating and updating the databse to match the model.
It Worked.
Populating the database.

2024-02-05 14:28
worked with controller methods and views
Looked at the post request methods for empty field Message.
added search to the ASP.NET core movie app. changed parameter to id and back to searchString.
added form to the index of the movie app for search function.
added search by title.

15:30
added search by genre to the index view

2024-02-08 11:30
added a new field called rating and added the migration for rating and updated the database.
build the solution and ran the app and it works perfectly we can change and edit the rating now.

12:10
adding validation to the code.