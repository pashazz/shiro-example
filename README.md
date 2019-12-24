Apache Shiro Spring-Boot Example
================================

This example can be run using the Apache Maven command: `mvn spring-boot:run`

Then browse or use cURL to: http://localhost:8080/troopers

``` bash
curl --user emperor:secret http://localhost:8080/troopers
```

* [Controller](./src/main/java/com/stormpath/shiro/samples/springboot/controllers/StormtrooperController.java)
* [User properties](./src/main/resources/shiro-users.properties)

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
