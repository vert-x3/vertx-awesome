# vertx-awesome

Vert.x Awesome is an list of awesome frameworks, libraries or other components for use with or that use
[Vert.x](https://github.com/eclipse/vert.x) version 3.

If you want your component to appear here, send a pull request to this repository to add it.

Please note that we can't vouch for the stability or production-worthiness of everything on this list unless it has
the icon ![(stack)](stack.png "Vert.x Stack") next to it.

That icon means the component is part of the `official` [Vert.x stack](http://vert-x3.github.io/docs/).

For vert.x version 2, check [this page](./vert-x2.md).

## Contents

- [Web frameworks](#web-frameworks)
- [Authentication Authorisation](#authentication-authorisation)
- [Database Clients](#database-clients)
- [Integration](#integration)
- [Language Support](#language-support)
- [Reactive](#reactive)
- [Sync Thread Non Block](#sync-thread-non-block)
- [Vert.x Event Bus Clients](#vertx-event-bus-clients)
- [Cluster Managers](#cluster-managers)
- [Cloud Support](#cloud-support)
- [Docker](#docker)
- [Search engines](#search-engines)
- [Service factory](#service-factory)
- [Dependency Injection](#dependency-injection)
- [Distribution](#distribution)
- [Examples](#examples)

## Web frameworks

* [Vert.x Web](https://github.com/vert-x3/vertx-web)  ![(stack)](stack.png "Vert.x Stack") - full featured web toolkit for Vert.x.
* [Vert.x Jersey](https://github.com/englishtown/vertx-jersey) - create JAX-RS [Jersey](https://jersey.java.net/) resources in Vert.x.
* [Kovert](https://github.com/kohesive/kovert) - Invisible REST framework for Kotlin + Vert.x Web.

## Authentication Authorisation

* [Vert.x Auth JDBC](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-jdbc)  ![(stack)](stack.png "Vert.x Stack") - Vert.x authentication/authorisation JDBC based.
* [Vert.x Auth JWT](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-jwt)  ![(stack)](stack.png "Vert.x Stack") - Vert.x Authorisation based on JSON Web Tokens.
* [Vert.x Auth Shiro](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-shiro)  ![(stack)](stack.png "Vert.x Stack") - Vert.x AuthN/AuthZ based on [Apache Shiro](http://shiro.apache.org/).

## Database Clients

*Clients for connecting to databases*

* Relational Databases
  * [JDBC](https://github.com/vert-x3/vertx-jdbc-client) ![(stack)](stack.png "Vert.x Stack") - Asynchronous interface around a JDBC datasource
  * [MySQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) - Asynchronous client for MySQL
  * [PostgreSQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) - Asynchronous client for PostgreSQL

* NoSQL Databases
  * [MongoDB](https://github.com/vert-x3/vertx-mongo-client) ![(stack)](stack.png "Vert.x Stack") - An asynchronous client for interacting with a MongoDB database
  * [Redis](https://github.com/vert-x3/vertx-redis-client) ![(stack)](stack.png "Vert.x Stack") - Asynchronous API to interact with Redis
  * [Cassandra](https://github.com/englishtown/vertx-cassandra) - Asynchronous API to interact with Cassandra and Cassandra Mapping

## Integration

* Mail
  * [SMTP](https://github.com/vert-x3/vertx-mail-client) ![(stack)](stack.png "Vert.x Stack") - Async SMTP client

* Messaging
  * [AMQP 1.0](https://github.com/vert-x3/vertx-amqp-service) - Async AMQP 1.0 bridge
  * [RabbitMQ](https://github.com/vert-x3/vertx-rabbitmq-client) - RabbitMQ client (AMQP 0.9.4)
  * [kafka](https://github.com/cyngn/vertx-kafka) - Kafka client for consuming and producing messages.

* JavaEE
  * [JCA adaptor](https://github.com/vert-x3/vertx-jca) ![(stack)](stack.png "Vert.x Stack") - Java Connector Architecture Adaptor for the Vert.x event bus

* Meteor
  * [Meteor](https://github.com/jmusacchio/vertxbus/) - Meteor integration support through Vert.x event bus

* Metrics
  * [Hawkular metrics](https://github.com/tsegismont/vertx-monitor) -  [Hawkular](http://www.hawkular.org/) implementation of the Vert.x Metrics SPI
  * [DropWizard metrics](https://github.com/vert-x3/vertx-dropwizard-metrics) ![(stack)](stack.png "Vert.x Stack") - Metrics implementation using DropWizard metrics
  * [OpenTsDb Metrics](https://github.com/cyngn/vertx-opentsdb) - [OpenTsDb](http://opentsdb.net/) metrics client for vert.x
  * [Bosun Monitoring](https://github.com/cyngn/vertx-bosun) - [Bosun](https://bosun.org/) client library for vert.x

## Language Support

*Programming language support for Vert.x*

* [Ceylon](https://github.com/vert-x3/vertx-lang-ceylon) - Ceylon support
* [Groovy](https://github.com/vert-x3/vertx-lang-groovy) ![(stack)](stack.png "Vert.x Stack") - Groovy support
* [Java](https://github.com/eclipse/vert.x) ![(stack)](stack.png "Vert.x Stack") - Vert.x main repository (including the Java API)
* [JavaScript](https://github.com/vert-x3/vertx-lang-js) ![(stack)](stack.png "Vert.x Stack") - JavaScript support
* [Python](https://github.com/vert-x3/vertx-lang-python) - Python support
* [Ruby](https://github.com/vert-x3/vertx-lang-ruby) ![(stack)](stack.png "Vert.x Stack") - Ruby support
* [Scala](https://github.com/vert-x3/vertx-lang-scala) - Scala support
* [TypeScript](https://github.com/michel-kraemer/vertx-lang-typescript) - TypeScript support

## Reactive

* [Reactive Streams](https://github.com/vert-x3/vertx-reactive-streams) ![(stack)](stack.png "Vert.x Stack") - Vert.x Reactive Streams
* [Reactive Extensions](https://github.com/vert-x3/vertx-rx) ![(stack)](stack.png "Vert.x Stack") - Vert.x Reactive Extensions.
* [vertx-util](https://github.com/cyngn/vertx-util) - Light weight promises & latches for vert.x

## Sync Thread Non Block

* [Sync](https://github.com/vert-x3/vertx-sync) - Synchronous but non-OS-thread-blocking verticles

## Vert.x Event Bus Clients

*Clients to connect applications to the vert.x event bus*

* [JavaScript](https://www.npmjs.com/package/vertx3-eventbus-client) ![(stack)](stack.png "Vert.x Stack") - JavaScript event bus client
* [C++11](https://github.com/julien3/vertxbuspp) - C++11 event bus client
* [Java](https://github.com/saffron-technology/vertx-eventbusbridge) - Java implementation of vertxbus.js

## Cluster Managers

*Implementations of the vert.x cluster manager SPI*

* [Hazelcast Cluster Manager](https://github.com/vert-x3/vertx-hazelcast) ![(stack)](stack.png "Vert.x Stack") - Hazelcast cluster manager
* [JGroups Cluster Manager](https://github.com/vert-x3/vertx-jgroups) - JGroups cluster manager
* [Zookeeper Cluster Manager](https://github.com/stream1984/vertx-zookeeper) - Zookeeper cluster manager
* [Copycat Cluster Manager](https://github.com/kuujo/vertx-copycat) - a [Copycat](https://github.com/kuujo/copycat) based Cluster Manager implementation for Vert.x 3.

## Cloud Support

* [OpenShift DIY cartridge](https://github.com/vert-x3/vertx-openshift-diy-quickstart) ![(stack)](stack.png "Vert.x Stack") - OpenShift DIY Cartridge using Vert.x
* [OpenShift Vert.x cartridge](https://github.com/vert-x3/vertx-openshift-cartridge) ![(stack)](stack.png "Vert.x Stack") - OpenShift Vert.x Cartridge using Vert.x

## Docker

* [Docker images](https://github.com/vert-x3/vertx-stack/tree/master/stack-docker) ![(stack)](stack.png "Vert.x Stack") - Docker images for Vert.x

## Search engines

* [Vert.x ElasticSearch Service](https://github.com/englishtown/vertx-elasticsearch-service) - Vert.x 3 [elastic search](https://www.elastic.co/) service with event bus proxying.
* [Vert.x Solr Service](https://github.com/englishtown/vertx-solr-service) - Vert.x 3 Solr service with event bus proxying.

## Testing

* [Vert.x Unit](https://github.com/vert-x3/vertx-unit) ![(stack)](stack.png "Vert.x Stack") - Async polyglot unit testing for Vert.x.

## Service Factory

* [Service Factory](https://github.com/vert-x3/vertx-service-factory) ![(stack)](stack.png "Vert.x Stack") - Vert.x Service Factory
* [Maven Service Factory](https://github.com/vert-x3/vertx-maven-service-factory) ![(stack)](stack.png "Vert.x Stack") - Maven Vert.x Service Factory
* [HTTP Service Factory](https://github.com/vert-x3/vertx-http-service-factory) ![(stack)](stack.png "Vert.x Stack") - Vert.x HTTP Service Factory

## Dependency Injection

* [Vert.x Guice](https://github.com/englishtown/vertx-guice) - Vert.x verticle factory for Guice dependency injection
* [Vert.x HK2](https://github.com/englishtown/vertx-hk2) - Vert.x verticle factory for HK2 dependency injection
* [Spring Vert.x Extension](https://github.com/amoAHCP/spring-vertx-ext) - Vert.x verticle factory for Spring DI injection

## Distribution

* [Vert.x Stack](https://github.com/vert-x3/vertx-stack) ![(stack)](stack.png "Vert.x Stack") - Vert.x + the endorsed modules

## Examples

* [Vert.x examples](https://github.com/vert-x3/vertx-examples) ![(stack)](stack.png "Vert.x Stack") - The official Vert.x examples including web examples, how to use the official database clients, ...
* [Vert.x feeds](https://github.com/aesteve/vertx-feeds) - Example of an RSS aggregator built using Vert.x, Gradle, MongoDB, Redis, Handlebars templates, AngularJS, the event bus and SockJS
* [Vert.x Markdown service](https://github.com/aesteve/vertx-markdown-service) - Example on how to use [service-proxy](https://github.com/vert-x3/vertx-service-proxy) with Gradle.
