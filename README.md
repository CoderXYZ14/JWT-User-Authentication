## JWT-User-Authentication
-Send a POST /signin
 Body-{
    username:string
    password:string
  }
return a json web token with username encrypted

-Then GET /users
 takes authorization header as input and return an array of all users is signed in (token is correct)
 else return 403 status code
