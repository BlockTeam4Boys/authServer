### As OpenID Provider Server this project using Keycloak  

## Setup instruction 

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
**Set http://localhost:8085 as url and digitaldocs-service as client name**
