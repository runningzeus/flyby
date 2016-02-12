# flyby

continuous delivery simplified 

## weekend : 11th Feb 2016

* development environment : java 8, maven 3, testng, fest, git, powermock, 
* maven should be used as build, test and release management tool
* spring boot will be used as application layer
* jax-rs as client / server interaction specification
* jetty as deployment tool 
* swagger as REST API documentation engine 
* REST assured as REST API test engine 


### functional feature list

* api client should be able to invoke a REST API to create a simple workflow that builds, test and notifies 
* api client should be able to confirm to proceed towards deployment 
* api client should be able to receive notification about success / failure of the deployment

### technical feature list

* availability of swagger documented REST API
* availability of tests for the REST API using REST assured
* release of 0.0.1 of the maven module
