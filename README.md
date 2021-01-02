# Documentum Maven Archetype

This project is to automate the Base setup of  Project structure, modules and packages for the Documentum xCP using maven archetype . 
The Project structure are swtup with 3 distinct modules with each modules focus on individual purpose. Project consist of 3 modules

  1. common - Contains all properties , utilities for executing queries and managing session and Constants.
  2. modules - Contains all TBO's , SBO's and Job/Method Modules 
  3. xcpmodules - Contains all the xCP Java Modules
  
  SETUP
  
  1. git checkout https://github.com/vkbdev83/dctmarchetype 
  2. Navigate to the check out folder and execute below 
  
      CMD Prompt > mvn install
      
      CMD Prompt >mvn archetype:generate
  -DgroupId=[your project's group id]
  -DartifactId=[your project's artifact id]
  -DarchetypeGroupId=a.b.dctm
  -DarchetypeArtifactId=dctmxcp-archetype
      
      
  

