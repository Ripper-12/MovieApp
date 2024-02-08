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
I tried installing new packages through the Nuget package manager but all i got was error of package not found.

23:15
After hours of surfing through the internet i found the solution.
I added a new package source for NuGet packages
searched and installed all the required package, added the package to the project.
after adding all that i tried once again and it worked like a charm.

23:25
After migrating and updating the databse to match the model.
It Worked.
Populated the database with new movies.

2024-02-05 14:28
worked with controller methods and views
Looked at the post request methods for empty field Message.
added search to the ASP.NET core movie app. changed parameter to id and back to searchString.
added form to the index of the movie app for search function.
added search by title.
15:30
created a new class in model 
changed the index method in moviesController with genre as a search string.
Added search by genre to the index view.

2024-02-08 11:30
added a new field called rating in Movie class,
Build the solution and updated the bind attribute for both the create and edit action methods for rating.
Added Rating field in Index  and Create Views.
Seeded the Database for Rating.
Added migration table for rating and updated the database.
build the solution and ran the app and it works perfectly we can change and edit the rating now.

12:10
added validation rules to the Movie model through built-in attributes such as Required, StringLength,DataType.
Run the app and checked for validation messsages.
Examined the Details method that the code verifies the search method before doing anything with it. 
Examined Delete method which returns the view of the movie and then only we can delete the specified movie.