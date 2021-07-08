# ⚠️ DEPRECATED

This repository is no longer active, all the sources have been moved to a [new monorepo](https://github.com/gravitee-io/gravitee-api-management/tree/master/gravitee-apim-repository/gravitee-apim-repository-hazelcast).

The new repository will be become the single GitHub repository for everything related to Gravitee.io API Management.

## Gravitee Hazelcast Repository

A repository implementation based on [Hazelcast](https://hazelcast.com/).

### Requirement

The minimum requirement is:
 * Maven3 
 * Jdk8

### Building

```
$ git clone https://github.com/gravitee-io/gravitee-repository-hazelcast.git
$ cd gravitee-repository-hazelcast
$ mvn clean package
```

### Installing

Unzip the gravitee-repository-hazelcast-x.y.z-SNAPSHOT.zip in the plugins directory.

### Configuration

repository.mongodb options : 

| Parameter                                        |   default  |
| ------------------------------------------------ | ---------: |
| configurationFile                                |  ${gravitee.home}/config/hazelcast.xml |