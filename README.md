# PHP REST API

Simple PHP REST API with no framework.

## Quick Start

Import the data.sql file, change the params in the config/Database.php file to your own

OR create a new bigger json or even sql file for more complex tests using something like https://www.mockaroo.com/

Or other json files can be convert to a data.sql file using https://sqlizer.io/

Use Postman or similar for CRUD requests

Useful quick start project.

## App Info

Example requests (live demo at this url)

//Get all posts

https://webmobapps.com/staging6/api/post/read.php

//Get a single post

https://webmobapps.com/staging6/api/post/read_single.php?id=3

//Create a post (post request) set application/json submit raw json key values

Keys below

title,
body,
author,
category_id


https://webmobapps.com/staging6/api/post/create.php

//Update a post (use put , put params in body of request, application/json)

https://webmobapps.com/staging6/api/post/update.php

//Delete a post (use delete, put id in body of request, application/json)

https://webmobapps.com/staging6/api/post/delete.php

//TO DO

Set up Categories CRUD

### Author

P A McGowan

https://webmobapps.com
https://minimallinux.tk

### Version

1.0.0

### License

This project is licensed under the MIT License
