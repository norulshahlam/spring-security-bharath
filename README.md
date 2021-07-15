v3 - https://cognizant.udemy.com/course/spring-security-fundamentals/learn/lecture/23041560#content

  - antMatchers: set some url to authenticate
  - now http://localhost:8080/hello need to authentivate
  - not http://localhost:8080/bye


v2
  - custom auth provider
  - in MyAuthenticationProvider.java
  - now we can remove the userDetailsService as we r using our own custom auth provider
  - also we use form instead of basic login
  - we can login using browser

this is v1
  - use beans for bcrypt

this is version 0
 - basic auth with encoder
 - http://localhost:8080/hello  