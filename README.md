# **Popular Movies-Stage1**

Popular-Movies--Stage is the Project1 Android app for the Udacity course [Developing Android Apps: Android Fundamentals](https://www.udacity.com/course/ud853).
In this app I have build the core experience of my movies app.
This app will:
 + Present the user with a grid arrangement of movie posters upon launch.
 + Allows user to change sort order via a setting:
 + The sort order can be by most popular or by highest-rated
 + Allowing the user to tap on a movie poster and transitioning to a details screen with additional information such as:
 -original title
 -movie poster image thumbnail
 -A plot synopsis (called overview in the api)
 -user rating (called vote_average in the api)
 -release date

 Take the course to find out how to build this app a step at a time, and eventually create your own Android App!
 
 ## **themoviedb API Key is required.**
An API key for themoviedb.org must be included with the build.
Obtain a key via the following [instructions](https://www.themoviedb.org/documentation/api), and include the unique key for the build by adding the following line in line number 75 in MainActivityFragment.java file:
String url = "http://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&api_key=**********"; Replace ********** by your key here.

 
