v5 - https://cognizant.udemy.com/course/spring-security-fundamentals/learn/lecture/22739509#content

  - test!

v4 - https://cognizant.udemy.com/course/spring-security-fundamentals/learn/lecture/23113356#content

  - custom filter - MySecurityFilter.java
  - we print out before and after filter
  - A filter is an object that performs filtering tasks on either the request to a resource (a servlet or static content), or on the response from a resource, or both.
  - use this filter in securityConfig.java,
  - also set to use for which auth type eg auth, cors, csrf

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