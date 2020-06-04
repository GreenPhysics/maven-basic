[![Quality Gate Status](http://54.69.165.75:9000/api/project_badges/measure?project=GreenPhysics%3Agithub-jenkins-sonar-jira&metric=alert_status)](http://54.69.165.75:9000/dashboard?id=GreenPhysics%3Agithub-jenkins-sonar-jira)
# maven-basic
Sample llustratation of a basic maven test in viewed through SonarQube, Jenkins, GitHub, Jira
This simple Maven project is importing JaCoCo's coverage report. For multi-module project example
see [multi-module Maven project](../maven-multimodule/README.md)

## Usage

* Build the project, execute all the tests and analyze the project with SonarQube Scanner for Maven(from root  of the project):

        mvn clean verify sonar:sonar

## Documentation

[SonarScanner for Maven](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner-for-maven/)

