# Java Basic Skeleton: Save the boilerplate in your new projects


##  Introduction

This is a repository intended to serve as a starting point if you want to bootstrap a Java project with JUnit and Gradle.

##  How To Start

1. Install Java 11: `brew cask install corretto` or download it [here](https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/downloads-list.html)
2. Set it as your default JVM: `export JAVA_HOME='/Library/Java/JavaVirtualMachines/amazon-corretto-11.jdk/Contents/Home'`
3. Clone this repository
4. Execute some [Gradle lifecycle tasks](https://docs.gradle.org/current/userguide/java_plugin.html#lifecycle_tasks) in order to check everything is OK:
    1. Create [the project JAR](https://docs.gradle.org/current/userguide/java_plugin.html#sec:jar): `make build`
    2. Run the tests and plugins verification tasks: `make test`




