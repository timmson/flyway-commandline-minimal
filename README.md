Flyway commandline minimal
==========================

It is fork of [Flyway](https://github.com/flyway/flyway)

If you have any questions, send it via email: [timmson666@mail.ru](mailto:timmson666@mail.ru?subjet=flyway-commandline-minimal)


### What changed
```java
//loadJdbcDrivers();
//loadJavaMigrationsFromJarDirs(properties);
```


## How to build
```sh
mvn clean package
```

## How to run
```sh
java -cp flyway-core-<version>.jar:flyway-commandline-minimal-<version>.jar:<your driver>.jar org.flywaydb.commandline.Main -driver=<your driver> -url=<jdbc url> -user=<jdbc user> -password=<jdbc password> -locations=<sql locations> 
```

