# upgrad
Includes application.properties for services utilising config server in Java SpringBoot Microservices Application.
Config server cannot access application properties file kept in nested hierarchy.
It should be present directly at first level in a repository. If the repository is not public
it is required to provide credentials of the repository for config server application to access the repository.
