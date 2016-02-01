# simple CRUD applicatoin in laravel
------------
What is this application?

This is a simple blogging application with the following features:

1. Anyone can login/register
2. Users can be 'admin', 'author' or 'subscriber'.
3. Authors can write/update/delete their own posts.
4. Admin has full access on the website and can read/ write/ update/ delete any of the posts.
5. Anyone can read these posts
6.Users can comment on the posts (only after login)


Database tables
------------
* users (default + role)
* posts (id, author, title, body, slug, published_on, last_modified, active)
* comments (id, on_post, from_user, body, at_time)


Using This Application
------------
1.

  * Edit the .env.example file to match your database and rename to .env
  * Set up and run the migrations
I am also attaching my sql file You can import it also.


2. Ensure that the permissions on the storage folder are set correctly. You will get a 500 error otherwise.

3. Ensure that you have set the correct image path for justboil.me to the appropriate folder or just use the default /images and make sure that folder has the correct permissions to upload images (usually owned by the webserver user).
