# Blog_Website

## Project Details

npm installs required

* body parser
* ejs
* express
* mongoose
* lodash

This is a Express app running on MongoDB database. The style.css can be found in the public folder. All the .ejs files can be found in the view folder and the footer and header are in partials folder in view.

The app can be run on localhost:3000

The compose route takes user entered blog and redirects to the home route where all the blogpost can be found. All blogpost are loaded using the Post.findOne() method from mongoDB database.  

Post.save() method saves the content of the Schema of the blogpost in the MongoDB database.
