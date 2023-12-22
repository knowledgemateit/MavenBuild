
Use Maven Build first to create war file in Target folder.
mvn pakage

sudo yum install java-1.8.0-amazon-corretto.x86

java -version

yum install maven git maven docker tree -y

sysemctl start docker

docker run -d --name project -p 8080:8080 consol/tomcat-7.0

docker ps -a ( find the container ID)

docker cp target/java-example.war e04e61981bce:/opt/tomcat/webapps

Access your java project via the web address.
