MurabahaClub Central Configuration Repository
=====================

This repository hosts the central configuration backend from which all the configuration of all the Spring Boot Based services will be loaded including the configuration server itself



## Configuration File Naming Convention ##
All configuration files should be named as follows:
```
	application-name[-profile].[(yml)|(properties)]
```
## Configuration Update Process ##
All the configuration updates should be first tested in a branch and then only merged to the master through a pull request post review.

### Specifying a branch in your config client ###
You ay specify a particular branch of this repository to be used by mentioning the below property in your **bootstrap.yml**
```
spring.cloud.config.label=mybranch
```
where the myrbanch **should be an existing branch on this repository.**

Optionally you may check this post for further customizations : [Using Spring Cloud Config, Maintaining Configuration Branches](http://www.naturalprogrammer.com/spring-cloud-config-maintain-configuration-branches/)

MurabahaClub Central Configuration Repository
=====================

This repository hosts the central configuration backend from which all the configuration of all the Spring Boot Based services will be loaded including the configuration server itself



## Configuration File Naming Convention ##
All configuration files should be named as follows:
```
	application-name[-profile].[(yml)|(properties)]
```
## Configuration Update Process ##
All the configuration updates should be first tested in a branch and then only merged to the master through a pull request post review.

### Specifying a branch in your config client ###
You ay specify a particular branch of this repository to be used by mentioning the below property in your **bootstrap.yml**
```
spring.cloud.config.label=mybranch
```
where the myrbanch **should be an existing branch on this repository.**

Optionally you may check this post for further customizations : [Using Spring Cloud Config, Maintaining Configuration Branches](http://www.naturalprogrammer.com/spring-cloud-config-maintain-configuration-branches/)

