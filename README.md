# WebApp-Login-With-Database-Connection
A CI/CD project where Three instances are created using AWS services. Jenkins was installed with Maven and Git pluggin on one instance, Tomcat server was installed on second instance, a third AWS RDS oracle 10g database instance was created to store login table information. 
* Create a pipeline in Jenkins for the Maven project.
* Connect Git repoitory to the Jenkins pipeline.
* Create a link between the Tomcat server and the Database server for login authorization.
* Finally, build the project and select deploy war/ear to a container plugin in post build section to send the created WAR file over to the Tomcat server.
