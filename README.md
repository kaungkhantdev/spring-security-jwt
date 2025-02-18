# Spring Boot JWT 
[Reference link](https://medium.com/@tericcabrel/implement-jwt-authentication-in-a-spring-boot-3-application-5839e4fd8fac)

```bash
JWT_SECRET_KEY="your-key"
```

### Build jar file
```bash
mvn clean package
```

### Run with env variables
```bash
java -jar target/your-jar.jar --JWT_SECRET_KEY="your-key"
```