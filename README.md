1. Run mvn jetty:run
2. type: 
http://localhost:8080/JacksonGuiceExample/web/users
http://localhost:8080/JacksonGuiceExample/web/users/1
http://localhost:8080/JacksonGuiceExample/web/users/numberOfUsers


	!!! Important - if you have running Apache Server (httpd) as a server/service - stop it
	in other way you get an error:
	[ERROR] client.JerseyClientGet Failed : HTTP error code : 404