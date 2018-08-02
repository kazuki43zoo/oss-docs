# oss-docs

## spring-framework

```
$ git clone https://github.com/spring-projects/spring-framework.git
$ cd spring-framework
$ git checkout v{version}
$ ./gradlew reference
```

build/reference

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

## spring-integration

```
$ git clone https://github.com/spring-projects/spring-integration.git
$ cd spring-integration
$ git checkout v{version}
$ ./gradlew reference
```

build/reference

## spring-ws

```
$ git clone https://github.com/spring-projects/spring-ws.git
$ cd spring-ws
$ git checkout v{version}
$ ./gradlew reference
```

build/reference

## spring-restdocs

```
$ git clone https://github.com/spring-projects/spring-restdocs.git
$ cd spring-restdocs
$ git checkout v{version}
$ ./gradlew docsZip
```
docs/build/asciidoc/html5


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

## junit4

```
$ git clone https://github.com/junit-team/junit4.wiki.git
$ cd junit4.wiki
$ gitbook init
$ gitbook build
```

_book

* README.md

```
# Introduction

This pages generated from JUnit 4 [wiki](https://github.com/junit-team/junit4/wiki).
```

* SUMMARY.md

```
# Summary

* [Download and Install](Download-and-Install.md)
* [Getting Started](Getting-Started.md)
* [Maintainer Documentation](Maintainer-Documentation.md)
* [Deprecation Policy](Deprecation-Policy.md)
* [I want to help!](I-want-to-help!.md)

##  JUnit Usage and Idioms
* [Assertions](Assertions.md)
* [Test Runners](Test-Runners.md)
* [Aggregating tests in Suites](Aggregating-tests-in-Suites.md)
* [Test Execution Order](Test-Execution-Order.md)
* [Exception Testing](Exception-Testing.md)
* [Matchers and assertThat](Matchers-and-assertThat.md)
* [Ignoring Tests](Ignoring-Tests.md)
* [Timeout for Tests](Timeout-for-Tests.md)
* [Parameterized Tests](Parameterized-Tests.md)
* [Assumptions with Assume](Assumptions-with-Assume.md)
* [Rules](Rules.md)
* [Theories](Theories.md)
* [Test Fixtures](Test-Fixtures.md)
* [Categories](Categories.asciidoc)
* [Use with Maven](Use-with-Maven.md)
* [Use with Gradle](Use-with-Gradle.md)
* [Multithreaded code and Concurrency](Multithreaded-code-and-Concurrency.md)
* [Java contract test helpers](Java-contract-test-helpers.md)
* [Continuous Testing](Continuous-Testing.md)

##  Third-party extensions

* [Custom Runners](Custom-Runners.md)
```

## reset-assured


```
$ git clone https://github.com/rest-assured/rest-assured.wiki.git
$ cd rest-assured.wiki
$ gitbook init
$ gitbook build
```

_book

* README.md

```
# Introduction

This pages generated from rest-assured [wiki](https://github.com/rest-assured/rest-assured/wiki).
```

* SUMMARY.md

```
# Summary

* [Getting Started](GettingStarted.md)
* [Downloads](Downloads.md)
* [Usage Guide](Usage.md) ([Legacy documentation](Usage_Legacy.md) (prior to v2.0))
* [Release Notes](ReleaseNotes.md) ([Change Log](https://raw.githubusercontent.com/jayway/rest-assured/master/changelog.txt))
* [Snapshot dependencies](snapshot.md)
* [FAQ](FAQ.md)
* [Support](http://groups.google.com/group/rest-assured) (google group/mailing list)
```


