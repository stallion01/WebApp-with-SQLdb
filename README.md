# CI-example
This repository stores code for the Java webapp with SQLdb using continuous integration with Jenkins and Ansible

# Run Sonar Scan

```
mvn sonar:sonar -Dsonar.projectKey=com.ansible -Dsonar.host.url=http://localhost:9000  -Dsonar.login=admin -Dsonar.password=admin

```
