# Testing the Spring CLI uses

## Hello World
```bash
spring run app.groovy
```

## New project
```bash
spring init --artifactId springclitest \
 --description "Testing the spring CLI capabilities" \
 --groupId com.davidlj95 --language kotlin \
 --build gradle
 -d="data-jpa,data-rest,liquibase,postgresql,jdbc"
rm springclitest.zip
```
