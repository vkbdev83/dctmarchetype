# Documentum Maven Archetype

This project is to automate the Base setup of  Project structure, modules and packages for the Documentum xCP using maven archetype . 
The Project structure are setup with 3 distinct modules with each modules focus on individual purpose. Project consist of 3 modules

  1. common - Contains all properties , utilities for executing queries and managing session and Constants.
  2. modules - Contains all TBO's , SBO's and Job/Method Modules 
  3. xcpmodules - Contains all the xCP Java Modules
  
  SETUP
  
  1. git clone https://github.com/vkbdev83/dctmarchetype 
  
  2. Navigate to the git clone folder and execute below commands
      
      Install the maven archetype using the mvn install command
    
           CMD Prompt > mvn install
           
      Generate the Project Structure ,modules , packages and base classess using below command
      
      CMD Prompt >mvn archetype:generate
  -DgroupId=[your project's group id]
  -DartifactId=[your project's artifact id]
  -DarchetypeGroupId=a.b.dctm
  -DarchetypeArtifactId=dctmxcp-archetype
  
  3. Imnport the Project into your IDE , this should provide the base project structure for your customizations/enhancements. 
      
      
  

