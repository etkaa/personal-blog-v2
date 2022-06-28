# personal-blog-v2

This is the updated version of personal blog. Previous version didn't have a database so the data would be
lost everytime server was restarted.

With this version MongoDB configurations has been added using Mongoose library. After you compose a post and submit
it, it will be displayed on the homepage. When you click on "Read More..", it will send a query to the database with 
the unique id for that post and then plug all the data into the EJS layout templates. 

This app has been built by using Express.js, Node.js, MongoDB, Mongoose, EJS, HTML, CSS and JavaScript.
