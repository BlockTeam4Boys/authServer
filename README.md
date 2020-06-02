###As OpenID Provider Server this project using Keycloak  

##Setup instruction 

1. Run the following command
```
$ docker-compose -f keycloak-compose.yml up -d
```
2. Goto http://localhost:8181/auth/
3. Goto Admin Console
4. Input "admin" "admin" to login
5. Complete **2, 3, 4, 6, 7** steps from here -
 ```
https://medium.com/@bcarunmail/securing-rest-api-using-keycloak-and-spring-oauth2-6ddf3a1efcc2
```
**Set http://localhost:8085 as url**
**Set digitaldocs-service as client name**

Your secret can be available here http://localhost:8181/auth/admin/master/console/#/realms/digitaldocs/clients
Just open your client and go to credentials

Your client_id is name of your client