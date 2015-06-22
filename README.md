# vertx-awesome

Vert.x Awesome is an list of awesome frameworks, libraries or other components for use with
[Vert.x](https://github.com/eclipse/vert.x) version 3.

If you want your component to appear here, send a pull request to this repository to add it.

For vert.x version 2, check [this page](./vert-x2.md).

## Contents

- [Database Clients](#database-clients)
- [Integration](#integration)
- [Language Support](#language-support)
- [Vert.x Event Bus Clients](#vert.x-event-bus-clients)
- [Cloud Support](#cloud-support)
- [Docker](#docker)

## Database Clients

*Clients for connecting to databases*

* Relational Databases
  * [JDBC](https://github.com/vert-x3/vertx-jdbc-client) ![(stack)](stack.png "Vert.x Stack") - Asynchronous interface around a JDBC datasource
  * [MySQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) ![(stack)](stack.png "Vert.x Stack") - Asynchronous client for MySQL
  * [PostgreSQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) ![(stack)](stack.png "Vert.x Stack") - Asynchronous client for PostgreSQL

* NoSQL Databases
  * [MongoDB](https://github.com/vert-x3/vertx-mongo-client) ![(stack)](stack.png "Vert.x Stack") - An asynchronous client for interacting with a MongoDB database
  * [Redis](https://github.com/vert-x3/vertx-redis-client) ![(stack)](stack.png "Vert.x Stack") - Asynchronous API to interact with Redis

## Integration

* Mail
  * [SMTP](https://github.com/vert-x3/vertx-mail-client) - Async SMTP client

* Messaging
  * [AMQP 1.0](https://github.com/vert-x3/vertx-amqp-service) - Async AMQP 1.0 bridge
  * [RabbitMQ](https://github.com/vert-x3/vertx-rabbitmq-client) - RabbitMQ client (AMQP 0.9.4)

* JavaEE
  * [JCA adaptor](https://github.com/vert-x3/vertx-jca) - Java Connector Architecture Adaptor for the Vert.x event bus

* Meteor
  * [Meteor](https://github.com/jmusacchio/vertxbus/) - Meteor integration support through Vert.x event bus

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

## Vert.x Event Bus Clients

* [C++11](https://github.com/julien3/vertxbuspp) - C++11 event bus client

## Cloud Support

* [OpenShift DIY cartridge](https://github.com/vert-x3/vertx-openshift-diy-quickstart) - OpenShift DIY Cartridge using Vert.x
* [OpenShift Vert.x cartridge](https://github.com/vert-x3/vertx-openshift-cartridge) - OpenShift Vert.x Cartridge using Vert.x

## Docker

* [Docker images](https://github.com/vert-x3/vertx-stack/tree/master/stack-docker) - Docker images for Vert.x
