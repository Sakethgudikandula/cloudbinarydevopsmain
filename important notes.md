### JENKINS: CI tool
##SONARQUBE: Continuous static code analysis
#### Maven: Build tool 
Maven LIfecycle: 
  validate - validate the project is correct and all necessary information is available
  compile - compile the source code of the project
  test - test the compiled source code using a suitable unit testing framework. These tests should not require the code be packaged or deployed
  package - take the compiled code and package it in its distributable format, such as a JAR.
  verify - run any checks on results of integration tests to ensure quality criteria are met
  install - install the package into the local repository, for use as a dependency in other projects locally
  deploy - done in the build environment, copies the final package to the remote repository for sharing with other developers and projects.


SONARQUBE- CONTINUOUS STATIC CODE ANALYSIS- if faing any issues with the processed code, it will show the errors in the sonarqube and we need to make the changes before deploying. We can also do this in sonarcloud as software as a service

JFROG- storing of artificats ie binary code repostory is done here just for future purpose to check the code 
