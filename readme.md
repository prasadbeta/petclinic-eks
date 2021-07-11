this is java project.

also we builds using maven .

it connects with the database(mysql)

database info pom.xml , schema.sql

we need to build : mvn clean package -P MySql

we are deploying to the eks(k8s)

code + Dockerfile 


where our app will run : tomcat 

what is iniput : war file 

if we need to war we have to build 


Jenkins--maven --  petclinic
job : war file 
/var/lib/jenkins/workspace/petclinic/target/


