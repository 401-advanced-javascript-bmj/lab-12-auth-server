![CF](http://i.imgur.com/7v5ASc8.png) LAB  
=================================================  
  
## Lab 12 Back End  
  
### Authors: Joe, Becky, Morgana  
  
### Links and Resources
* [submission PR](https://github.com/401-advanced-javascript-bmj/lab-12-auth-server/pull/2)  
* [back-end](https://lab-12-backend.herokuapp.com/)  
  
### Modules  
#### `app.js, wordpress.js, middleware.js, router.js, users-model.js, 404.js, error.js`
##### Exported Values and Methods

###### `app -> express server`  
###### `wordpress -> wordpress auth2.0 authentication function`  
###### `book -> express Router instance`  
###### `middleware -> authentication middleware`  
###### `router -> express Router instance`  
###### `users-model -> mongoose model`  
###### `404 -> route not found middleware`  
###### `error -> error handler middleware`  
  
### Setup  
#### `.env` requirements  
* `PORT` - Port Number  
* `MONGODB_URI` - URL to the running mongo instance/db  
* `WORDPRESS_CLIENT_ID`
* `WORDPRESS_CLIENT_SECRET`
   
#### Running the app  
* `npm start`  
Endpoints:  
* `/signup` - basic auth only  
* `/signin` - basic auth only  
* `/oauth` - oauth wordpress login  
  
#### UML  
![uml]()