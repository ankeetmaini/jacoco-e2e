# jacoco-e2e-gradle-spring-boot

## running service

```bash
./gradlew build && java -jar build/libs/rest-service-0.0.1-SNAPSHOT.jar
```

java -jar org.jacoco.cli-0.8.6-nodeps.jar report jacoco.exec --classfiles=build/classes --html coverage
