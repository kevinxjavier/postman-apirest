# [postman-apirest](https://github.com/kevinxjavier/postman-apirest.git)
Here you will find the postman collection and a csv folder which contains the examples files to load in the postman collection.
Remember sometime after close the Postman app you will need to load the csv file otherwise will throws an error.

# [core-parent](https://github.com/kevinxjavier/core-parent.git)
This is the "first" SpringBoot project we will need just to install.

# [ms-jwt-security-management](https://github.com/kevinxjavier/ms-jwt-security-management.git)
This is the "second" SpringBoot project we will need to install and execute. 

This micro provides 2 endpoints in the postman collection found in folder Token:
* Signup "endpoint use it to create a valid user"
* Login "endpoint use it to login the user created with previous endpoint"

# [ms-shopping-basket-management](https://github.com/kevinxjavier/ms-shopping-basket-management.git)
Finally this "third" SpringBoot project in order to install and execute. 

This micro provides 4 endpoints, 3 of them will upload csv files to a remote server leaving a copy in the local server 
(one of this 3 has an invalid file just for tested purpose).

The last one just send a request body in JSON: with items (id, name, value), this will calculate total value of items (also the other 3 endpoints) and save it also in a 
local and remote server. 

Also for fun this last endpoint save the request body JSON in a database.
