# simple-rest-api
This is a simple rest api for HospitalManagement.

## Quick Glance
This project has mainly four files (basically .js files).
- server.js
- config.js
- middleware.js
- Mainapp.js

server.js file validates the user's login credentilas. If the credentials are correct, then user can access the Mainapp.js.
middleware.js basically authenticates user while accessing the site.

## How to run it?
- Run the server.js by giving correct login credentials.  In server.js, I had kept default username and password.  Copy the JWT token given by the server.  JWT token is provided only when you give the correct login credentials.
- Run the Mainapp.js.  While you visit any page, make sure that you had added the JWT token for Authorization in the headers part.  Add the token in this form "Bearer _JWTtoken_".
- I would suggest you to run it in "postman".
