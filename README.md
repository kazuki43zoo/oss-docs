# oss-docs

## spring-security

```
$ git clone https://github.com/spring-projects/spring-security.git
$ cd spring-security
$ cd checkout {version}
$ ./gradlew reference
```
docs/manual/build/reference

## spring-batch

```
$ git clone https://github.com/spring-projects/spring-batch.git
$ cd spring-batch
$ git checkout {version}
$ ./gradlew reference
```

build/reference

## logback

```
$ git clone https://github.com/qos-ch/logback.git
$ cd logback
$ git checkout v_{version}
```

logback-site/src/site/pages

## hibernate-validator

```
$ git clone https://github.com/hibernate/hibernate-validator.git
$ cd hibernate-validator
$ git checkout {version}
$ mvn -pl documentation clean package
```

documentation/target/asciidoc-html

## mybatis

```
$ git clone https://github.com/mybatis/mybatis-3.git
$ cd mybatis-3
$ git checkout mybatis-{version}
$ ./mvnw clean site:site
```

target/site

## mybatis-spring

```
$ git clone https://github.com/mybatis/spring.git
$ cd spring
$ git checkout mybatis-spring-{version}
$ ./mvnw clean site:site
```

target/site

