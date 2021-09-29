# spring-auth-jwt-swagger

/api/authenticate

	Body > raw,JSON
~~~
		{
		"username" : "{username}",
		"password" : "{password}"
		}
 ~~~
 
/api/hello
~~~
	-Headers
		-Content-Type
			-application/json
      
		-Authorization
			-Bearer {token}
~~~

/swagger-ui.html
