# Docker hub Readme

# tag `default-1.2.2`, tag `default`

- migrated github repo
- change version to `semver` format
- rename `java-cikit` to `cikit`

# tag `default-1.21`

- using latest tags and default packages
- base: `ubuntu:latest`
- apt: `default-jdk`, `ant`, `maven`, `junit`, `junit4`
- init maven with `maven-archetype-quickstart`
- `java-cikit` - show versions

```
# java-cikit
java-cikit version 1.21

# uname -a
Linux 5868aa757558 5.4.0-58-generic #64-Ubuntu SMP Wed Dec 9 08:16:25 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux

# java -version
openjdk version "11.0.9.1" 2020-11-04
OpenJDK Runtime Environment (build 11.0.9.1+1-Ubuntu-0ubuntu1.20.04)
OpenJDK 64-Bit Server VM (build 11.0.9.1+1-Ubuntu-0ubuntu1.20.04, mixed mode, sharing)

# javac -version
javac 11.0.9.1

# ant -version
Apache Ant(TM) version 1.10.7 compiled on October 24 2019

# mvn -version
Apache Maven 3.6.3
Maven home: /usr/share/maven
Java version: 11.0.9.1, vendor: Ubuntu, runtime: /usr/lib/jvm/java-11-openjdk-amd64
Default locale: en_US, platform encoding: ANSI_X3.4-1968
OS name: "linux", version: "5.4.0-58-generic", arch: "amd64", family: "unix"

# java -cp /usr/share/java/junit.jar junit.runner.Version
3.8.2

# java -cp /usr/share/java/junit4.jar junit.runner.Version
4.12
```

# tag `default-1.2`

- using latest tags and default packages
- base: `ubuntu:latest`
- apt: `default-jdk`, `ant`, `maven`, `junit`
- init maven with `maven-archetype-quickstart`
- `java-cikit` - show versions

```
# java-cikit
java-cikit version 1.2

# uname -a
Linux 95948edcb536 5.4.0-58-generic #64-Ubuntu SMP Wed Dec 9 08:16:25 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux

# java -version
openjdk version "11.0.9.1" 2020-11-04
OpenJDK Runtime Environment (build 11.0.9.1+1-Ubuntu-0ubuntu1.20.04)
OpenJDK 64-Bit Server VM (build 11.0.9.1+1-Ubuntu-0ubuntu1.20.04, mixed mode, sharing)

# javac -version
javac 11.0.9.1

# ant -version
Apache Ant(TM) version 1.10.7 compiled on October 24 2019

# mvn -version
Apache Maven 3.6.3
Maven home: /usr/share/maven
Java version: 11.0.9.1, vendor: Ubuntu, runtime: /usr/lib/jvm/java-11-openjdk-amd64
Default locale: en_US, platform encoding: ANSI_X3.4-1968
OS name: "linux", version: "5.4.0-58-generic", arch: "amd64", family: "unix"

# java -cp /usr/share/java/junit.jar junit.runner.Version
3.8.2
```

# tag `default-1.1`

- using latest tags and default packages
- base: `ubuntu:latest`
- apt: `default-jdk`, `ant`, `maven`

```
# uname -a
Linux 85c6b2ca9ccc 5.4.0-58-generic #64-Ubuntu SMP Wed Dec 9 08:16:25 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux

# java -version
openjdk version "11.0.9.1" 2020-11-04
OpenJDK Runtime Environment (build 11.0.9.1+1-Ubuntu-0ubuntu1.20.04)
OpenJDK 64-Bit Server VM (build 11.0.9.1+1-Ubuntu-0ubuntu1.20.04, mixed mode, sharing)

# javac -version
javac 11.0.9.1

# ant -version
Apache Ant(TM) version 1.10.7 compiled on October 24 2019

# mvn -version
Apache Maven 3.6.3
Maven home: /usr/share/maven
Java version: 11.0.9.1, vendor: Ubuntu, runtime: /usr/lib/jvm/java-11-openjdk-amd64
Default locale: en_US, platform encoding: ANSI_X3.4-1968
OS name: "linux", version: "5.4.0-58-generic", arch: "amd64", family: "unix"
```

# tag `default-1.0`

- using latest tags and default packages
- base: `ubuntu:latest`
- apt: `default-jdk`, `ant`

```
# uname -a
Linux be7cbebed036 5.4.0-58-generic #64-Ubuntu SMP Wed Dec 9 08:16:25 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux

# java -version
openjdk version "11.0.9.1" 2020-11-04
OpenJDK Runtime Environment (build 11.0.9.1+1-Ubuntu-0ubuntu1.20.04)
OpenJDK 64-Bit Server VM (build 11.0.9.1+1-Ubuntu-0ubuntu1.20.04, mixed mode, sharing)

# javac -version
javac 11.0.9.1

# ant -version
Apache Ant(TM) version 1.10.7 compiled on October 24 2019

# mvn -version
```
