# docker-java-cikit

- CI/CD image for java project

  - OpenJDK - [https://jdk.java.net](https://jdk.java.net)
    - JAVA_HOME = /usr/lib/jvm/default-java
  - Apache ant - [https://ant.apache.org](https://ant.apache.org)
    - ANT_HOME = /usr/share/ant
  - Apache maven - [https://maven.apache.org](https://maven.apache.org)
  - Junit - [https://junit.org](https://junit.org)
    - /usr/share/java

## History

- `1.2.2` - 2021-Sep-30 - rename `java-cikit` to `cikit`, change version to `semver`
- `1.21` - 2021-Jan-12 - add `junit4`
- `1.2` - 2021-Jan-11 - add `junit`, `java-cikit`, - init maven with `maven-archetype-quickstart`
- `1.1` - 2021-Jan-10 - add `maven`
- `1.0` - 2021-Jan-09 - init `ubuntu:latest` with `default-jdk`,`ant`
