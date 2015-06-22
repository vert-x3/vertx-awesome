# vertx-awesome

Vert.x 2 Awesome is an list of awesome frameworks, libraries or other components for use with
[Vert.x](https://github.com/eclipse/vert.x) version 2.

If you want your component to appear here, send a pull request to this repository to add it.

For vert.x version 3, check [this page](./README.md).

## Contents
- [Testing](#testing)
- [Database / Key-Value](#database--key-value)
- [Messaging](#messaging)
- [Image manipulation](#image-manipulation)
- [Network protocols](#network-protocols)
- [Mail](#mail)
- [Event processing](#event-processing)
- [Language implementations](#language-implementations)
- [Build tool integration](#build-tool-integration)
- [JSON / BSON](#json--bson)
- [Metrics](#metrics)
- [Dependency injection](#dependency-injection)
- [Web middleware frameworks](#web-middlewre-frameworks)
- [REST](#rest)
- [Session management](#session-management)
- [Management](#management)
- [Cloud support](#cloud-support)
- [Mobile clients](#mobile-client)
- [Integration](#integration)
- [Asynchronous composition / promises](#asynchronous-composition--promises)
- [Archiving](#archiving)
- [Work queueing](#work-queuing)
- [Social networks](#social-networks)
- [Scaffolding](#scaffolding)
- [Natural Language Processing](#natural-language-processing)

## The vert.x module registry
* `io.vertx~module-registry` - https://github.com/vert-x/vertx-module-registry - The Vert.x module registry itself!

## Testing

* `org.mock-server~mockserver-vertx` http://www.mock-server.com/ - MockServer is an API to enable the easy mocking of any system you integrate with via HTTP or HTTPS (i.e. services, web sites, etc). There are currently specific clients written in Java and JavaScript although any language that can send JSON via HTTP can easily use the MockServer API.

* `mohlemeyer~vertxQunitSinon` - https://github.com/mohlemeyer/vertxQunitSinon - This module contains ports of the QUnit and Sinon.JS JavaScript testing frameworks for the Vert.x platform, supplemented by an easy to use testrunner.

## Database / Key-Value

* `monoid-us~vertx-postgresql` - https://github.com/monoid-us/vertx-postgresql - Asynchronous PostgreSQL driver with support for transactions. This driver is used as a library directly in your Verticle and supports running transactions against the database.

* `com.jonnywray.vertx~mod-kairosdb` - https://github.com/jonnywray/mod-kairosdb - This is a Vertx module that allows data to be inserted, queryed and deleted from the KairosDB time series database.

* `io.vertx~mod-mysql-postgresql` - https://github.com/vert-x/mod-mysql-postgresql - This Vert.x module uses the https://github.com/mauricio/postgresql-async drivers to support a fully async module for MySQL and PostgreSQL.

* `io.vertx~mod-mongo-persistor` - https://github.com/vert-x/mod-mongo-persistor - This module allows data to be saved, retrieved, searched for, and deleted in a MongoDB instance. MongoDB is a great match for persisting vert.x data since it natively handles JSON (BSON) documents.

* `io.vertx~mod-redis` - https://github.com/vert-x/mod-redis - This module allows data to be saved, retrieved, searched for, and deleted in a Redis. Redis is an open source, BSD licensed, advanced key-value store. It is often referred to as a data structure server since keys can contain strings, hashes, lists, sets and sorted sets. To use this module you must have a Redis server instance running on your network.

* `io.vertx~mod-redis-client` - Client module for io.vertx~mod-redis

* `com.bloidonia~mod-jdbc-persistor` - https://github.com/timyates/mod-jdbc-persistor - JDBC event bus module for Vert.x

* `ashertarno~vertx-memcached` - https://github.com/ashertarno/vertx-memcached - This module provides a Vert.x client for cache/storage servers, implementing memcached protocol.

* `com.kennethjorgensen.vertx~vertx-mod-riak-persistor` -https://bitbucket.org/kennethjor/vertx-mod-riak-persistor - This module provides a vert.x client for riak.


## Messaging

* `com.zanox.vertx~mod-kafka` - https://github.com/zanox/mod-kafka - Kafka module allows to receive events published by other Vert.x verticles and send those events to Kafka broker.
* `p14n~vert-zeromq` - https://github.com/p14n/vert-zeromq - Providing a bridge from zero-mq to the vert-x event bus.
* `com.jetdrone~mod-stomp-io` - https://github.com/pmlopes/mod-stomp-io - This module allows communcation between Message brokers such as ActiveMQ, RabbitMQ Apache Apollo using the STOMP protocol.
* `RabbitMQ` - https://github.com/stream1984/mod-rabbitmq

## Image manipulation

* `com.kafeblog.vertx~image-magick` - https://github.com/khoinguyen/vertx-imagemagick - Vert.x ImageMagick module provide EventBus to handle the Image processing with ImageMagick

## Network protocols

* `mohlemeyer~vertxFtpClient` - https://github.com/mohlemeyer/vertxFtpClient - An asynchronous FTP client module for the Vert.x platform.

## Mail

* `mohlemeyer~a-mailer` - https://github.com/mohlemeyer/a-mailer - Vert.x module to send email messages via SMTP fully asynchronously.
* `io.vertx~mod-mailer` - https://github.com/vert-x/mod-mailer - This module allows emails to be sent via SMTP. Uses blocking JavaMail API.
* Vert.x IMAP client - https://github.com/karanth/vertx-imap

## Event processing

* `net.kuujo~vertigo` - https://github.com/kuujo/vertigo - Vertigo is a distributed event processing framework built on the Vert.x application platform. Following a concept and structure similar to Storm, Vertigo allows real-time problems to be broken down into smaller tasks (as Vert.x verticles) and distributed across one or many Vert.x instances, managing communication between components in a predictable and reliable manner.
* `net.kuujo~vertigo-python` - https://github.com/kuujo/vertigo-python - Python API for Vertigo (see above)
* `net.kuujo~vertigo-js` - https://github.com/kuujo/vertigo-js - JavaScript API for Vertigo (see above)

## Language implementations

* `io.vertx~lang-clojure` - https://github.com/vert-x/mod-lang-clojure - Clojure API implementation for Vert.x
* `io.vertx~lang-dynjs` - https://github.com/vert-x/mod-lang-php - JavaScript API implementation for Vert.x that uses the DynJS JavaScript engine
* `io.vertx~lang-nashorn` - https://github.com/vert-x/mod-lang-nashorn - JavaScript API implementation for Vert.x that uses the Oracle Nashorn JavaScript engine
* `io.vertx~lang-rhino` - https://github.com/vert-x/mod-lang-rhino - JavaScript API implementation for Vert.x that uses the Mozilla Rhino JavaScript engine
* `io.vertx~lang-scala~0.2.0` - https://github.com/vert-x/mod-lang-scala - Scala API implementation for Vert.x.
* `io.vertx~lang-groovy` - https://github.com/vert-x/mod-lang-groovy - Groovy API implementation for Vert.x
* `io.vertx~lang-jython` - https://github.com/vert-x/mod-lang-jython - Python API implementation for Vert.x, using the Jython Python engine.
* `io.vertx~lang-jruby` - https://github.com/vert-x/mod-lang-jruby - Ruby API implementation for Vert.x, using the JRuby Ruby engine.
* `vietj~lang-ceylon` - https://github.com/vietj/vertx-ceylon - Ceylon language API implementation for Vert.x
* `io.vertx~lang-php` - https://github.com/vert-x/mod-lang-php - PHP language API implementation for Vert.x
* Yeti - https://github.com/chrisichris/yvertx
* Kotlin - https://github.com/zhaopuming/kert.x
* TypeScript definition files for Vert.x APIs https://github.com/frankwallis/vertx-typescript


## Build tool integration

* Maven. https://github.com/vert-x/vertx-maven - Maven archetype and plugin for Vert.x
* Gradle. https://github.com/vert-x/vertx-gradle-template - Gradle template project for Vert.x


## JSON / BSON

* `com.campudus~json-schema-validator` - https://github.com/campudus/vertx-json-schema-validator - Vert.x module to validate JSON against a schema (see http://json-schema.org/)
* `com.jetdrone~mod-bson-io` - https://github.com/pmlopes/mod-bson-io - BSON event bus wrapper for Vert.x

## Metrics

* `com.bloidonia~mod-metrics` - https://github.com/timyates/mod-metrics - A vert.x mod to try and expose stats over JMX using the Metrics library.
* https://github.com/englishtown/vertx-mod-metrics

## Dependency injection

* `com.alienos.vertx~mod-guice` - https://github.com/tigeba/mod-guice - mod-guice is a Google Guice module for Vert.x. It includes everything you need to be Guicing your Vert.x like a pro in five minutes.
* `com.englishtown~vertx-mod-guice` - https://github.com/englishtown/vertx-mod-guice - Enable Verticle and Module dependency injection using Google Guice. The default Vert.x Java VerticleFactory is replaced with com.englishtown.vertx.guice.GuiceVerticleFactory for Verticle construction.
* `com.englishtown~vertx-mod-hk2` - https://github.com/englishtown/vertx-mod-hk2 - Enable Verticle and Module dependency injection using HK2. The default Vert.x Java VerticleFactory is replaced with com.englishtown.vertx.hk2.HK2VerticleFactory for Verticle construction.
* `bytor99999~mod-spring-appcontext` - https://github.com/bytor99999/mod-spring-appcontext - This module creates a Spring ApplicationContext so that you can use the Spring Framework in your Vert.x applications.

## Web middleware frameworks

* `com.jetdrone~yoke` - https://github.com/pmlopes/yoke - Yoke is a polyglot middleware framework for Vert.x, shipping with over 12 bundled middleware (think - like Node.js Express for Vert.x)
* `com.jetdrone~yoke-extras` - Extras module for Yoke. (Including OAuth)
* https://github.com/spriet2000/vertx-stacker - Stacker provides a minimal and adaptable interface for developing web applications on the vert.x 2.0 platform.
* `io.vertx~mod-web-server` - https://github.com/vert-x/mod-web-server - This is a simple example web server which efficiently serves files from the file system.
* `whiteship2000~mod-socket-io` - https://github.com/keesun/mod-socket-io - This module allows the Vert.x users can make a socket.io server as node.js users do.
* Atmosphere for Vert.x. https://github.com/Atmosphere/atmosphere-vertx A Java WebSocket and HTTP server powered by the Atmosphere Framework and the Vert.x Framework.
* Thymeleaf template engine - https://github.com/swilliams-pivotal/mod-thymeleaf
* Moustache template engine - https://github.com/jorishermans/vert.x-mustache

## REST

* `com.englishtown~vertx-mod-jersey` - https://github.com/englishtown/vertx-mod-jersey - Allows creating JAX-RS jersey resources that will handle incoming http requests to vert.x.
* `vertx-bricks` - https://github.com/ThiagoUriel/vertx-brix - Simplifies RESTful API development in Vert.x. Provides a straightforward REST server implementation for endpoint publishing, and basic dependency injection for the Event Bus.

## Session management

* `com.campudus~session-manager` - https://github.com/campudus/vertx-session-manager - This module allows to store data in a session. Sessions can time out after a specified amount of time. The stored information of timed out sessions will be deleted.
* `io.vertx~mod-auth-mgr` - https://github.com/vert-x/mod-auth-mgr - This is a basic auth manager that verifies usernames and passwords in a MongoDB database and generates time-limited session ids. These session ids can be passed around the event bus.

## Management

`org.crashub~vertx.shell` - https://github.com/crashub/mod-shell - The module mod-shell provides an embedded shell for Vert.x based on CRaSH shell.

## Cloud support

* OpenShift - Using diy cartridge - https://github.com/vert-x/openshift-vertx
* OpenShift - first class cartridge - https://github.com/nscavell/openshift-origin-cartridge-vertx
* Cloudbees - https://github.com/CloudBees-community/vertx-clickstack
* Heroku - https://github.com/tomaslin/heroku-buildpack-vertx-jdk7
* CloudFoundry - https://github.com/cloudfoundry-samples/vertx-vtoons/
* Cloudify http://rantav.github.io/cloudify-widget-pages/vertx.html
* Chef template for Vert.x https://github.com/zanox/vertx

## Mobile clients

* https://github.com/goodow/realtime-channel - IoS Vert.x event bus client
* https://github.com/goodow/realtime-android - Android Vert.x event bus client
* `ashertarno~vertx-gcm` - https://github.com/ashertarno/vertx-gcm - This module provides a Google Cloud Messaging for Android server side solution for Vert.x. Google Cloud Messaging for Android (GCM) is a service that helps developers push data from servers to their Android applications on Android devices.

## Integration

* Vert.x event bus JCA adaptor: https://github.com/gaol/vertx-resource-adapter
* Vert.x Apache Camel component http://camel.apache.org/vertx.html https://github.com/apache/camel/blob/master/components/camel-vertx/src/main/java/org/apache/camel/component/vertx/VertxComponent.java
* https://github.com/projectodd/nodyn - Node.js drop-in compatibility for Vert.x


## Asynchronous composition / promises

* `io.vertx~mod-rxvertx` - https://github.com/vert-x/mod-rxvertx - Vert.x module which uses RxJava to add support for Reactive Extensions (RX) using the RxJava library. This allows VertX developers to use the RxJava type-safe composable API to build VertX verticles.
* `com.englishtown~vertx-mod-when` - https://github.com/englishtown/vertx-mod-when - Provides when.java wrappers for standard vert.x objects to return promises.
* `com.darylteo~vertx-promises-java` - https://github.com/darylteo/rxjava-promises - Promises is a pattern for callback-based flow control. This particular implementation of Promises is useful in places where blocking calls are undesired.
* `com.darylteo~vertx-promises-groovy` - As above but Groovy API.

## Archiving

* `io.vertx~mod-unzip` - https://github.com/vert-x/mod-unzip - Simple worker module that given the file name of a zip file, unzips it to a temp directory or a specified directory and returns the filename in a Json message

## Work queueing

* `io.vertx~mod-work-queue` - https://github.com/vert-x/mod-work-queue - This module queues messages (work) sent to it, and then forwards the work to one of many processors that may be attached to it, if available.

## Social networks

* `orolle~mod-facebook` - https://github.com/orolle/mod-facebook - mod-facebook uses the facebook query language to access data from facebook.

## Scaffolding

* https://github.com/sebastienblanc/vertxgo - VertxGo (aka 'Vertigo' or 'Vert.x Go!') is a CRUD Scaffolding Vert.x Module.

## Natural Language Processing

* Stanford core NLP https://github.com/jonnywray/mod-stanford-corenlp
