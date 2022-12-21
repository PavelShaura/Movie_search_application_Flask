# My privat "Kinopoisk" with a bunch of different films!

## This project will require knowledge of Flask, SQLAlchemy, Marshmallow (or any other validator of your choice), REST, CRUD, JWT

## **Project Description**

*1. Authentication

In order for each user to have the opportunity to bookmark their favorite movies for viewing later, we need to somehow differentiate them, so we organize registration and authentication pages based on the already studied JWT specification.

*2. Users

Each user will have a page with his profile, where he will be able to choose his favorite genre, specify his first and last name, and also, if necessary, change his password.

*3. Films, directors, genres

Of course, you need to add the most important entities — films, directors and genres. For them, we will only make it possible to read (get requests).

Pagination will work for all objects so that we can display them on the screen page by page, and it will also be possible to watch the newest movies.
It is also necessary for the user to implement a mechanism for adding and deleting movies to /from bookmarks, as well as viewing all movies saved in bookmarks.
Set up works correctly with front added through index.html (port :25000)
If you want to work with node.js change port to (:5000)

Main part

/auth/register - POST
/auth/login - POST, PUT
/user/ - GET, PATCH
/user/password - PUT
/movies/ - GET (params: status, page)
/movies/ - GET
/genres/ - GET (params: page)
/genres/ - GET
/directors/ - GET (params: page)
/directors/ - GET


By Pavel Shaura
