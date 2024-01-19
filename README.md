[![Quality Gate Status](http://54.69.165.75:9000/api/project_badges/measure?project=GPC%3Agithub%3Amaven-basic&metric=alert_status)](http://54.69.165.75:9000/dashboard?id=GPC%3Agithub%3Amaven-basic)
# maven-basic
Sample llustratation of a basic maven test viewed through SonarQube, Jenkins, GitHub, Jira
This simple Maven project is importing JaCoCo's coverage report. For multi-module project example

## Usage

* Build the project, execute all the tests and analyze the project with SonarQube Scanner for Maven(from root  of the project):

        mvn clean verify sonar:sonar

## Documentation

[SonarScanner for Maven](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner-for-maven/)

