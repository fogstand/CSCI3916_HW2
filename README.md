# CSCI3916_HW2
# https://csc3916ravisherhw2.herokuapp.com/

# signup
1. POST :no username or password sent you should return an error(Fail)
2. If success should return {success:true, msg:'Successful created new user.(Pass)
3. All other methods should return error (e.g. GET, PUT, DELETE, PATCH) -it should respond with a simple statement saying it doesn’t support the HTTP method.

# Sign In
1 POST §If user not found you should return an error (401)
2.If success should return {success:true, token:'JWT '+token}
3.All other methods should return error (e.g. GET, PUT, DELETE, PATCH)-it should respond with a simple statement saying it doesn’t support the HTTP method.o

# Movies
GET should return { status: 200, message: ‘GET movies”,  headers: headers: header from request,query: query string from request,env: your unique key}
POST:  should  return  {“status”:  200,  message:  “movie saved”, headers: headers: header from request,query: query string from request, env: your unique key}
PUT :  should  return  {“status:  200,  message:  “movie updated”, headers: headers: header from request,query: query string from request, env: yourunique key}•PUTshould require authentication (JWTAuth)
DELETE :  should  return  {“status:  200,  message:  “movie deleted”, headers: headers: header from request,query: query string from request, env: your unique key}•Delete should require authentication (Basic Auth)
All other methods should return error (e.g. PATCH) -it should respond with a simple statement saying it doesn’t support the HTTP method.
Any requests made to the base URL (no URN specified) should also be rejected. 
