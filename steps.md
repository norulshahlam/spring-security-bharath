
0. security constants
1. dependency for 
  - string to json
  - jwt
  - spring security
2. user model
3. user mcontroller
4. security config 
  - allow & restrict urls
5. JwtAuthenticationEntryPoint 
  - called when unauthorized
  - sets of config: set status, content type, etc..
6. InvalidLoginResponse
  - the json obj to return the exception handled by JwtAuthenticationEntryPoint
  - pojos
7. Once JwtAuthenticationEntryPoint is configured, add its obj to security config class, in authenticationEntryPoint().
  - this will give the response body we want eg http://localhost:8080/**



