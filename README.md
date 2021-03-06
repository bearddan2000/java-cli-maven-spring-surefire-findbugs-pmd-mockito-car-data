# java-cli-maven-spring-surefire-findbugs-pmd-mockito-car-data

## Description
Analyze source code for potential bugs.
A POC for spring app. Testing done with surefire
and pmd plugins using mockito framework.

## Tech stack
- java
- maven
	- findbugs
  - spring
  - pmd
  - surefire
  - mockito
    - junit5

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/junit-5)
