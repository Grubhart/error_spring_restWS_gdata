this is a Pure spring restful web service in order to build and deploy execute:

```sh
$ ./gradlew tomcatRunWar
```

Then, if you visit [http://localhost:8080/aggregators/orders](http://localhost:8080/aggregators/orders), you should get the following JSON response, which indicates that you don't yet have any Orders in the application:

```json
[]
```
