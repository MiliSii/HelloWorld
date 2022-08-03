# Task Maven


Maven Lifecycle: default, clean, and site and all of them have phases. Phases rely on plugins to do work.

Default -main lifecycle,
Clean- remove the /target folder,
Site- creating a website.

commands:
mvn install – for building project,
mvn test – for test, 
mvn clear – deletes the build directory named target and its contents,
mvn package – for creating jars.

.m2 is local repository. It is used for storing all the dependency jars after Maven project is builed. My Location: C:\Users\milicasi\.m2\repository\maven 

Pom file structure:
Project root i.e. <project>,
Model version i.e. <modelVersion>,
Group ID i.e. <groupId>,
Artifact Id i.e. <artifactId>,
Version i.e. <version>,
Plugin configuration,
Dependencies,
Resources,
Plugin lists,
Plugin execution Ids.
  
  
 For parent/child:
POM file in Project root directory. Reference from child POM file which contains the same coordinates stated in parent POM. Child POM file refer the parent POM file using the <parent> tag. Child POM file inherits all dependencies and properties from the parent POM file. Additionally, It also inherits subprojects dependencies.



  
