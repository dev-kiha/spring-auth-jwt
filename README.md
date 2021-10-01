# spring-auth-jwt

{domain}/authenticate

	Body > raw,JSON
  ~~~
		{
		"username" : "{username}",
		"password" : "{password}"
		}
 ~~~
 
{domain}/hello
~~~
	-Headers
		-Content-Type
			-application/json
      
		-Authorization
			-Bearer {token}
~~~
