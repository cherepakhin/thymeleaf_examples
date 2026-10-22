Examles ThymeLeaf from [https://github.com/thymeleaf/thymeleaf.git](https://github.com/thymeleaf/thymeleaf.git).

------------------------
mvn package: take the compiled code and package it in its distributable format, such as a JAR.
mvn install: install the package into the local repository, for use as a dependency in other projects locally
------------------------
echo $JAVA_HOME
/home/vasi/.sdkman/candidates/java/current

/home/vasi/.sdkman/candidates/java/current/bin/java -version
java 17

~/prog/java/themleaf/thymeleaf$ ./package.sh  - OK

cd lib
export JAVA_HOME=/usr/lib/jvm/java-1.17.0-openjdk-amd64
mvn clean package - OK

cd dist
 mvn clean package - ????????
 Downloading from central-portal-snapshots: https://central.sonatype.com/repository/maven-snapshots/org/thymeleaf/thymeleaf-parent/3.1.4-SNAPSHOT/thymeleaf-parent-3.1.4-20260411.201100-5.pom


 thymeleaf
 ---------
 
 In order to learn more and download the latest version:
 
     http://www.thymeleaf.org


     