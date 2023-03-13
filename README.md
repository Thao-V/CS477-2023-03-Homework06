# CS477-2023-03-Homework06
## Continue Lab 6 based on Lab 5 to implement the features below for RESTful Application:
1. Add a login feature which username and password. If logged in successfully, return JWT, otherwise, error message.
2. For all CRUD operations on Books, they have to be authenticated. If call APIs withou JTW, return 401 unauthorized. With incorrect JWT, return 403 Forbidden. Only with correct, return JSON data
3. Implement the middleware to allow the logged in user can access the routes in the previous lab
