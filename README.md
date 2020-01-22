# TDD Starter

This is a Maven archetype for quickly bootstrapping a Java Maven project for TDD kata goodness.

## Use

Maven must be available
 
### Installation in local repository

```shell script
mvn install
```
 
 ### Use to generate a new project
 
The magic incantation is something like

```shell script
mvn archetype:generate              \
  -DarchetypeGroupId=name.prochyra  \
  -DarchetypeArtifactId=tdd-starter \
  -DarchetypeVersion=1.0            \
  -DgroupId=<my.groupid>            \
  -DartifactId=<my-artifactId>
```

BOOM!