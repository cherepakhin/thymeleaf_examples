thymeleaf
---------

In order to learn more and download the latest version:

[http://www.thymeleaf.org](http://www.thymeleaf.org)

Examples ThymeLeaf from [https://github.com/thymeleaf/thymeleaf.git](https://github.com/thymeleaf/thymeleaf.git).

------------------------
mvn package: take the compiled code and package it in its distributable format, such as a JAR.
mvn install: install the package into the local repository, for use as a dependency in other projects locally
------------------------

````shell
echo $JAVA_HOME
````
-> /home/vasi/.sdkman/candidates/java/current

````shell
/home/vasi/.sdkman/candidates/java/current/bin/java -version
````

-> java 17

````shell
export JAVA_HOME=/usr/lib/jvm/java-1.17.0-openjdk-amd64
````

````shell
cd ~/prog/java/themleaf/thymeleaf 
./package.sh
````

Result:

````text
[INFO] Processing sources for module project: org.thymeleaf.examples:thymeleaf-examples:pom:3.1.4-SNAPSHOT
[INFO] Building zip: /home/vasi/prog/java/themleaf/thymeleaf/dist/target/thymeleaf-3.1.4-SNAPSHOT-dist.zip
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary for thymeleaf parent 3.1.4-SNAPSHOT:
[INFO] 
[INFO] thymeleaf parent ................................... SUCCESS [  0.013 s]
[INFO] thymeleaf lib ...................................... SUCCESS [  0.007 s]
[INFO] thymeleaf .......................................... SUCCESS [ 21.360 s]
[INFO] thymeleaf-spring5 .................................. SUCCESS [ 12.338 s]
[INFO] thymeleaf-spring6 .................................. SUCCESS [ 10.946 s]
[INFO] thymeleaf-extras-springsecurity5 ................... SUCCESS [  4.787 s]
[INFO] thymeleaf-extras-springsecurity6 ................... SUCCESS [  4.215 s]
[INFO] thymeleaf testing lib .............................. SUCCESS [  0.000 s]
[INFO] thymeleaf-testing .................................. SUCCESS [  8.572 s]
[INFO] thymeleaf-testing-spring5 .......................... SUCCESS [  3.320 s]
[INFO] thymeleaf-testing-spring6 .......................... SUCCESS [  3.409 s]
[INFO] thymeleaf tests .................................... SUCCESS [  0.001 s]
[INFO] thymeleaf tests - core ............................. SUCCESS [  5.648 s]
[INFO] thymeleaf tests - spring5 .......................... SUCCESS [  1.524 s]
[INFO] thymeleaf tests - spring6 .......................... SUCCESS [  1.607 s]
[INFO] thymeleaf tests - springsecurity5 .................. SUCCESS [  0.219 s]
[INFO] thymeleaf tests - springsecurity6 .................. SUCCESS [  0.232 s]
[INFO] thymeleaf examples ................................. SUCCESS [  0.001 s]
[INFO] thymeleaf examples core ............................ SUCCESS [  0.000 s]
[INFO] thymeleaf examples core - GTVG [jakarta] ........... SUCCESS [  1.084 s]
[INFO] thymeleaf examples core - GTVG [javax] ............. SUCCESS [  0.511 s]
[INFO] thymeleaf examples spring5 ......................... SUCCESS [  0.001 s]
[INFO] thymeleaf examples spring5 - extraThyme ............ SUCCESS [  0.890 s]
[INFO] thymeleaf examples spring5 - Say Hello ............. SUCCESS [  0.711 s]
[INFO] thymeleaf examples spring5 - Spring Mail ........... SUCCESS [  0.710 s]
[INFO] thymeleaf examples spring5 - STSM .................. SUCCESS [  0.774 s]
[INFO] thymeleaf examples spring5 - Thymeleaf vs JSP ...... SUCCESS [  0.717 s]
[INFO] thymeleaf examples spring6 ......................... SUCCESS [  0.001 s]
[INFO] thymeleaf examples spring6 - extraThyme ............ SUCCESS [  1.050 s]
[INFO] thymeleaf examples spring6 - Say Hello ............. SUCCESS [  0.812 s]
[INFO] thymeleaf examples spring6 - Spring Mail ........... SUCCESS [  0.697 s]
[INFO] thymeleaf examples spring6 - STSM .................. SUCCESS [  1.012 s]
[INFO] thymeleaf examples spring6 - Thymeleaf vs JSP ...... SUCCESS [  0.869 s]
[INFO] thymeleaf examples springboot2 ..................... SUCCESS [  0.029 s]
[INFO] thymeleaf examples springboot2 - Big List [MVC] .... SUCCESS [  2.480 s]
[INFO] thymeleaf examples springboot2 - Big List [WebFlux]  SUCCESS [  0.718 s]
[INFO] thymeleaf examples springboot2 - SSE [WebFlux] ..... SUCCESS [  0.651 s]
[INFO] thymeleaf examples springboot2 - STSM [MVC] ........ SUCCESS [  0.428 s]
[INFO] thymeleaf examples springboot2 - STSM [WebFlux] .... SUCCESS [  0.490 s]
[INFO] thymeleaf examples springboot3 ..................... SUCCESS [  0.000 s]
[INFO] thymeleaf examples springboot3 - Big List [MVC] .... SUCCESS [  1.829 s]
[INFO] thymeleaf examples springboot3 - Big List [WebFlux]  SUCCESS [  0.870 s]
[INFO] thymeleaf examples springboot3 - SSE [WebFlux] ..... SUCCESS [  0.867 s]
[INFO] thymeleaf examples springboot3 - STSM [MVC] ........ SUCCESS [  0.430 s]
[INFO] thymeleaf examples springboot3 - STSM [WebFlux] .... SUCCESS [  0.723 s]
[INFO] thymeleaf examples springsecurity5 ................. SUCCESS [  0.000 s]
[INFO] thymeleaf examples springsecurity5 - WebSecurity ... SUCCESS [  0.710 s]
[INFO] thymeleaf examples springsecurity6 ................. SUCCESS [  0.001 s]
[INFO] thymeleaf examples springsecurity6 - WebSecurity ... SUCCESS [  0.788 s]
[INFO] thymeleaf distribution ............................. SUCCESS [01:53 min]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
````

````shell
cd ~/prog/java/themleaf/thymeleaf/lib/
mvn clean package
````

OK

````shell
cd ~/prog/java/themleaf/thymeleaf/dist/
mvn clean package
````

OK

Screens see in examples/__project/doc/*.png

Screenshot example: [examples/springboot2/thymeleaf-examples-springboot2-biglist-mvc/doc/screen1_fremarker.png](./examples/springboot2/thymeleaf-examples-springboot2-biglist-mvc/doc/screen1_fremarker.png)

Downloading from central-portal-snapshots: https://central.sonatype.com/repository/maven-snapshots/org/thymeleaf/thymeleaf-parent/3.1.4-SNAPSHOT/thymeleaf-parent-3.1.4-20260411.201100-5.pom
     