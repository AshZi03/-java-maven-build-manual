----manually making simple-java-application----
mkdir simple-java-application
cd simple-java-application
mkdir -p src/main/java/com/example
nano pom.xml
cd src/main/java/com/example
nano App.java
cd ~/simple-java-application
----creating maven package----
mvn clean package
ls target
----run jar file----
java -jar target/sample-java-app-1.0-SNAPSHOT.jar
----output----
Hello, CargoFL!
