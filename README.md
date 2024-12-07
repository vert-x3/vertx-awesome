# Awesome Vert.x [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="vertx-logo.svg" align="right" width="250" alt="Vert.x logo">](http://vertx.io)

*Awesome Vert.x* is a list of awesome frameworks, libraries or other components related to
[Vert.x](https://github.com/eclipse/vert.x).

If you want your component to appear here, send a pull request to this repository to add it.

Please note that we can't vouch for the stability or production-worthiness of everything on this list unless it has
the icon <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px">
next to it. This icon means the component is part of the official
[Vert.x stack](https://vertx.io/docs/).

## Contents

* [Books](#books)
* [Build tools](#build-tools)
* [Web Frameworks](#web-frameworks)
* [Authentication Authorisation](#authentication-authorisation)
* [Database Clients](#database-clients)
* [Integration](#integration)
* [Middleware](#middleware)
* [Language Support](#language-support)
* [Reactive](#reactive)
* [Sync Thread Non Block](#sync-thread-non-block)
* [Vert.x Event Bus Clients](#vertx-event-bus-clients)
* [Vert.x Event Bus Extensions](#vertx-event-bus-extensions)
* [Cluster Managers](#cluster-managers)
* [Cloud Support](#cloud-support)
* [Microservices](#microservices)
* [Search Engines](#search-engines)
* [Service Factory](#service-factory)
* [Config](#config)
* [Dependency Injection](#dependency-injection)
* [Testing](#testing)
* [Development Tools](#development-tools)
* [Miscellaneous](#miscellaneous)
* [Distribution](#distribution)
* [Examples](#examples)
* [Deployment](#deployment)
* [Utilities](#utilities)
* [Articles](#articles)
* [Front-End](#front-end)

## Books

* [Building Reactive Microservices in Java](https://www.oreilly.com/library/view/building-reactive-microservices/9781491986295/) by Clément Escoffier
* [Vert.x in Action](https://www.manning.com/books/vertx-in-action) by Julien Ponge

## Build tools

* [Vert.x Maven plugin](https://github.com/reactiverse/vertx-maven-plugin)
* [Vert.x Gradle plugin](https://plugins.gradle.org/plugin/io.vertx.vertx-plugin)
* [Vert.x Codegen Gradle plugin](https://github.com/bulivlad/vertx-codegen-plugin) - A Gradle plugin to facilitate the codegen usage for Vert.x Java projects.

## Web Frameworks

* [Vert.x Web](https://github.com/vert-x3/vertx-web)  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Full featured web toolkit for Vert.x.
* [Vert.x Jersey](https://github.com/englishtown/vertx-jersey) - Create JAX-RS [Jersey](https://eclipse-ee4j.github.io/jersey/) resources in Vert.x.
* [Kovert](https://github.com/kohesive/kovert) - Invisible REST framework for Kotlin + Vert.x Web.
* [Handlers](https://github.com/spriet2000/vertx-handlers-http) - Open web framework for Vert.x.
* [QBit](https://github.com/advantageous/qbit) - REST and WebSocket method call marshaling and reactive library.
* [vertx-rest-storage](https://github.com/swisspush/vertx-rest-storage) - Persistence for REST resources in the filesystem or a redis database.
* [Jubilee](https://github.com/isaiah/jubilee) - A rack compatible Ruby HTTP server built on Vert.x 3.
* [Knot.x](https://github.com/Cognifide/knotx) - Efficient & high-performance integration platform for modern websites built on Vert.x 3.
* [Irked](https://github.com/GreenfieldTech/irked) - Annotations-based configuration for Vert.x Web, with a controller framework and expressive APIs for REST.
* [REST.VertX](https://github.com/zandero/rest.vertx) - Lightweight JAX-RS (RestEasy) like annotation processor for Vert.x verticals.
* [Atmosphere Vert.x](https://github.com/Atmosphere/atmosphere-vertx) - Realtime Client Server Framework for the JVM, supporting WebSockets and Server Sent Events with Cross-Browser Fallbacks.
* [Vert.x Vaadin](https://github.com/mcollovati/vertx-vaadin) - Run Vaadin applications on Vert.x.
* [Serverx](https://github.com/lukehutch/serverx) - Allows you to quickly and easily set up a Vert.x-powered server using only route handler annotations.
* [Cloudopt Next](https://github.com/cloudoptlab/cloudopt-next) - Cloudopt Next is a very lightweight and modern, JVM-based, full stack kotlin framework designed for building modular, easily testable JVM applications with support for Java, Kotlin language, crafted from the best of breed Java libraries and standards.
* [Donkey](https://github.com/AppsFlyer/donkey) - Modern Clojure HTTP server and client built for ease of use and performance.
* [SCX](https://github.com/scx567888/scx) - An open and easy-to-use web framework, most functions are based on annotations.
* [vertx-rest](https://github.com/dream11/vertx-rest) - Abstraction over resteasy-vertx to simplify writing a Vert.x REST application based on JAX-RS annotations.

## Authentication Authorisation

* [Vert.x Auth SQL](https://github.com/eclipse-vertx/vertx-auth)  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x authentication/authorisation based on the Vert.x SQL client and a relational database.
* [Vert.x Auth JWT](https://github.com/eclipse-vertx/vertx-auth/tree/master/vertx-auth-jwt)  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation based on JSON Web Tokens.
* [Vert.x Auth htdigest](https://github.com/eclipse-vertx/vertx-auth/tree/master/vertx-auth-htdigest)  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [Apache htdigest](https://httpd.apache.org/docs/2.4/programs/htdigest.html).
* [Vert.x Auth Mongo](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-mongo)  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [MongoDB](https://www.mongodb.com/).
* [Vert.x Auth OAuth2](https://github.com/eclipse-vertx/vertx-auth/tree/master/vertx-auth-oauth2) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [OAuth 2](https://oauth.net/2/).
* [Vert.x Auth htpasswd](https://github.com/eclipse-vertx/vertx-auth/tree/master/vertx-auth-htpasswd) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [htpasswd](https://httpd.apache.org/docs/2.4/programs/htpasswd.html).

* [Vert.x-Pac4j](https://github.com/pac4j/vertx-pac4j) - Vert.x authentication/authorisation implemented using [pac4j](http://www.pac4j.org/).

## Database Clients

*Clients for connecting to databases*

* Relational Databases
  * [Reactive SQL Client](https://github.com/eclipse-vertx/vertx-sql-client) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - High performance reactive SQL client.
  * [JDBC](https://github.com/vert-x3/vertx-jdbc-client) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous interface around a JDBC datasource.
  * [MySQL / PostgreSQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous Client for MySQL/PostgreSQL.
  * [PostgreSQL](https://github.com/vietj/reactive-pg-client) - Reactive PostgreSQL Client.
  * [database](https://github.com/susom/database) - Client for Oracle, PostgreSQL, SQL Server, HyperSQL, etc. designed for security, correctness, and ease of use.
  * [jOOQ](https://github.com/jklingsporn/vertx-jooq) - Doing typesafe, asynchronous SQL and generate code using jOOQ.
  * [jOOQx](https://github.com/zero88/jooqx) - Leverages the power of typesafe SQL from `jOOQ DSL` and uses the reactive and non-blocking SQL driver from Vert.x.
  * [Exposed Vert.x SQL Client](https://github.com/huanshankeji/exposed-vertx-sql-client) - Kotlin's [Exposed](https://github.com/JetBrains/Exposed) on top of [Vert.x Reactive SQL Client](https://github.com/eclipse-vertx/vertx-sql-client).

* NoSQL Databases
  * [MongoDB](https://github.com/vert-x3/vertx-mongo-client) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - An asynchronous client for interacting with a MongoDB database.
  * [Redis](https://github.com/vert-x3/vertx-redis-client) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous API to interact with Redis.
  * [Cassandra](https://github.com/vert-x3/vertx-cassandra-client) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - A Vert.x client allowing applications to interact with a Cassandra service.
  * [Cassandra](https://github.com/englishtown/vertx-cassandra) - Asynchronous API to interact with Cassandra and Cassandra Mapping.
  * [OrientDB](https://github.com/cstamas/vertx-orientdb) - Non-blocking OrientDB server integration.
  * [Bitsy](https://github.com/cstamas/vertx-bitsy) - Non-blocking Bitsy Graph server integration.
  * [MarkLogic](https://github.com/etourdot/vertx-marklogic) - Asynchronous client for Marklogic Database Server.
  * [SirixDB](https://github.com/sirixdb/sirix/tree/master/bundles/sirix-rest-api) - Non-blocking SirixDB HTTP-server.
  * [DGraph](https://github.com/aesteve/vertx-dgraph-client) - An example on how to build a Vert.x gRPC compliant client. Here targeting [dgraph](https://dgraph.io)
  * [RxFirestore](https://github.com/pjgg/rxfirestore) - Non-blocking Firestore SDK written in a reactive way.
  * [MongoDB](https://github.com/imrafaelmerino/vertx-mongo-effect) - Pure functional and reactive MongoDB client on top of [Vert.x Effect](https://github.com/imrafaelmerino/vertx-mongo-effect). Full support for retry, fallback and recovery operations.
  * [Aerospike](https://github.com/dream11/vertx-aerospike-client) - Asynchronous and non-blocking API to interact with Aerospike server. Uses [AerospikeClient's](https://github.com/aerospike/aerospike-client-java) async commands internally and handles the result on the Vert.x Context.

* [vertx-pojo-mapper](https://github.com/BraintagsGmbH/vertx-pojo-mapper) - Non-blocking POJO mapping for MySQL and MongoDB.
* [vertx-mysql-binlog-client](https://github.com/guoyu511/vertx-mysql-binlog-client) - A Vert.x client for tapping into MySQL replication stream.

## Integration

* Server-Sent Events
  * [jEaSSE](https://github.com/mariomac/jeasse) - Java Easy SSE. A simple, lightweight implementation of SSE.
  * [vertx-sse](https://github.com/aesteve/vertx-sse) - Vert.x SSE implementation + event-bus SSE bridge.

* Mail
  * [SMTP](https://github.com/vert-x3/vertx-mail-client) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Async SMTP client.
  * [vertx-smtp-server](https://github.com/cinterloper/vertx-smtp-server) - SMTP server bridging to EventBus.

* REST
  * [Retrofit adapter for Vert.x](https://github.com/vietj/retrofit-vertx) - A highly scalable adapter for Retrofit with Vert.x.
  * [openapi4j adapter for Vert.x](https://github.com/openapi4j/openapi4j/tree/master/openapi-operation-adapters/openapi-operation-vertx) - OpenAPI 3 request validator and router factory alternative.
  * [Vert.x Effect HTTP client](https://github.com/imrafaelmerino/vertx-effect) - Pure functional and reactive HTTP client using [Vert.x Effect](https://github.com/imrafaelmerino/vertx-effect) with OAuth support and retry, fallback and recovery operations.

* File Server
  * [Vert.x TFTP Client](https://github.com/OneManCrew/vertx-tftp-client) - TFTP client for Vert.x support download/upload files.
* Messaging
  * [AMQP 1.0](https://github.com/vert-x3/vertx-amqp-bridge) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Interact with AMQP 1.0 servers using the Vert.x Producer and Consumer APIs.
  * [MQTT](https://github.com/vert-x3/vertx-mqtt) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Provides two different components: an MQTT server for handling all the MQTT communication and messages exchanges with clients and an MQTT client for sending and receiving messages against an MQTT broker.
  * [RabbitMQ](https://github.com/vert-x3/vertx-rabbitmq-client) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - A RabbitMQ client (AMQP 0.9.1).
  * [Kafka Client](https://github.com/vert-x3/vertx-kafka-client) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - A Kafka client.
  * [kafka](https://github.com/cyngn/vertx-kafka) - Kafka client for consuming and producing messages.
  * [SaltStack](https://github.com/cinterloper/vertx-salt) - A bi-directional bridge between the SaltStack event system and the Vert.x event bus.
  * [STOMP](https://github.com/vert-x3/vertx-stomp) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - A Kafka client and server.
  * [ZeroMQ](https://github.com/dano/vertx-zeromq) - ZeroMQ Event Bus bridge.
  * [Azure ServiceBus](https://github.com/TextBack/vertx-azure-servicebus) - Azure [ServiceBus](https://azure.microsoft.com/en-us/products/service-bus/) producer and consumer (fully async, doesn't use Microsoft Azure SDK).
  * [AMQP 1.0 - Kafka bridge](https://github.com/rhiot/amqp-kafka-bridge) - Bridge for sending/receiving messages to/from Apache Kafka using the AMQP 1.0 protocol.
  * [Vert.x Kafka Client](https://github.com/vert-x3/vertx-kafka-client) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Apache Kafka client for reading and sending messages from/to an Apache Kafka cluster.
  * [The White Rabbit](https://github.com/viartemev/the-white-rabbit) - An asynchronous RabbitMQ (AMQP) client based on Kotlin coroutines.
  * [WAMP Broker](https://github.com/i22-digitalagentur/vertx-wamp) - A WAMP broker you can embed into your Vert.x application.

* JavaEE
  * [JCA adaptor](https://github.com/vert-x3/vertx-jca) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Java Connector Architecture Adaptor for the Vert.x event bus.
  * [Weld](https://github.com/weld/weld-vertx) - Brings the CDI programming model into the Vert.x ecosystem (register CDI observer methods as Vert.x message consumers, CDI-powered Verticles, define routes in a declarative way, etc.).

* Meteor
  * [Meteor](https://github.com/jmusacchio/vertxbus/) - Meteor integration support through Vert.x event bus.

* Metrics
  * [Hawkular metrics](https://github.com/tsegismont/vertx-monitor) - [Hawkular](http://www.hawkular.org/) implementation of the Vert.x Metrics SPI.
  * [DropWizard metrics](https://github.com/vert-x3/vertx-dropwizard-metrics) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Metrics implementation using DropWizard metrics.
  * [Micrometer metrics](https://github.com/vert-x3/vertx-micrometer-metrics) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Metrics implementation using Micrometer metrics.
  * [OpenTsDb Metrics](https://github.com/cyngn/vertx-opentsdb) - [OpenTsDb](http://opentsdb.net/) metrics client for Vert.x.
  * [Bosun Monitoring](https://github.com/cyngn/vertx-bosun) - [Bosun](https://bosun.org/) client library for Vert.x.

* Netflix - Hystrix
  * [Hystrix Metrics Stream](https://github.com/kennedyoliveira/hystrix-vertx-metrics-stream.git) - Emits metrics for Hystrix Dashboard from a Vert.x application with [Hystrix](https://github.com/Netflix/Hystrix).

* Dart
  * [Vert.x Dart SockJS](https://github.com/wem/vertx-dart-sockjs) - [Dart](https://www.dartlang.org/) integration for [Vert.x SockJS bridge](http://vertx.io/docs/vertx-web/java/#_sockjs_event_bus_bridge) and plain SockJS with use of dart:js.

* Push Notifications
  * [Onesignal](https://github.com/jklingsporn/vertx-push-onesignal) - Send push notifications to (mobile/web) apps from your Vert.x application with [OneSignal](https://onesignal.com/).

* CNCF CloudEvents
  * [CloudEvents.io Java SDK](https://github.com/cloudevents/sdk-java) - Send and receive [CloudEvents](https://cloudevents.io/) using the [Vert.x HTTP Transport](https://github.com/cloudevents/sdk-java/blob/master/http/vertx/README.md) for CloudEvents.

## Middleware

* [Apache Camel](https://camel.apache.org/components/vertx-component.html) - [Apache Camel](http://camel.apache.org/) component for bridging Camel with the Vert.x event bus.
* [Gateleen](https://github.com/swisspush/gateleen) - Middleware library based on Vert.x to build advanced JSON/REST communication servers.
* [Gravitee.io](https://gravitee.io) - An OSS API Platform including an API Gateway and an OAuth2 / OIDC authorization server based on Vert.x Core / Vert.x Web and other modules.
* [API Framework](https://github.com/vinscom/api-framework) - Vert.x and Glue based microservice framework removing distinction between standalone and serveless application. All services can run in standalone server, but, if required, same codebase can be used to run any service as serverless application.

## Language Support

*Programming language support for Vert.x*

* [Ceylon](https://github.com/vert-x3/vertx-lang-ceylon) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Ceylon support.
* [Groovy](https://github.com/vert-x3/vertx-lang-groovy) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Groovy support.
* [Java](https://github.com/eclipse/vert.x) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x main repository (including the Java API).
* [JavaScript](https://github.com/vert-x3/vertx-lang-js) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - JavaScript support.
* [Python](https://github.com/vert-x3/vertx-lang-python) - Python support.
* [Ruby](https://github.com/vert-x3/vertx-lang-ruby) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Ruby support.
* [Scala](https://github.com/vert-x3/vertx-lang-scala) - <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Scala support.
* [Kotlin](https://github.com/vert-x3/vertx-lang-kotlin) - <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Kotlin support.
* [EcmaScript](https://github.com/reactiverse/es4x) - EcmaScript >=6 (JavaScript) support.
* [Php](https://github.com/vert-x-cn/vertx-lang-jphp) - Php support.

*Language extensions*

* [Grooveex](https://github.com/aesteve/grooveex) - Syntactic sugar + utilities (DSL builders, etc.) on top of [vertx-lang-groovy](https://github.com/vert-x3/vertx-lang-groovy).

## Reactive

* [Reactive Streams](https://github.com/vert-x3/vertx-reactive-streams) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Reactive Streams.
* [Vert.x Rx](https://github.com/vert-x3/vertx-rx) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Reactive Extensions.
* [Vert.x Sync](https://github.com/vert-x3/vertx-sync) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x fiber support.
* [Kotlin coroutines](https://github.com/vert-x3/vertx-lang-kotlin/tree/master/vertx-lang-kotlin-coroutines) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x support for Kotlin coroutines.
* [vertx-util](https://github.com/cyngn/vertx-util) - Light weight promises & latches for Vert.x.
* [QBit](https://github.com/advantageous/qbit) - Async typed actor-like lib that runs easily in Vert.x Async Callbacks. Callback management.
* [VxRifa](https://nsforth.github.io/vxrifa) - Utility library for Vert.X that allows using strong-typed interfaces in communication through EventBus.
* [Vert.x Effect](https://github.com/imrafaelmerino/vertx-effect) - Pure functional and reactive library based on the IO Monad to implement any complex flow. Full support for retry, fallback and recovery operations.
* [SmallRye Mutiny](https://smallrye.io/smallrye-mutiny/) - Intuitive event-driven reactive programming library for Java with [bindings for Vert.x](https://smallrye.io/smallrye-mutiny-vertx-bindings/).

## Sync Thread Non Block

* [Sync](https://github.com/vert-x3/vertx-sync) - Synchronous but non-OS-thread-blocking verticles.

## Vert.x Event Bus Clients

*Clients to connect applications to the Vert.x event bus*

* [JavaScript](https://www.npmjs.com/package/vertx3-eventbus-client) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - JavaScript event bus client.
* [C++11](https://github.com/julien3/vertxbuspp) - C++11 event bus client.
* [Java](https://github.com/saffron-technology/vertx-eventbusbridge) - Java implementation of vertxbus.js.
* [Java](https://github.com/abdlquadri/vertx-eventbus-java) - Java and Android Event Bus Client.
* [Java](https://github.com/danielstieger/javaxbus) - Simple Java Event Bus Client using plain TCP socket I/O.
* [CLI](https://github.com/cinterloper/vxc) - Command-line binary client for Vert.x event bus - pipe in JSON, emit JSON.
* [Swift](https://github.com/tobias/vertx-swift-eventbus) - Event bus client for [Apple's Swift](https://swift.org) using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Python](https://github.com/jaymine/TCP-eventbus-client-Python) - Event bus client for Python using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [C#](https://github.com/jaymine/TCP-eventbus-client-C-Sharp) - Event bus client for C# using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [C](https://github.com/jaymine/TCP-eventbus-client-C) - Event bus client for C99 using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Go](https://github.com/jponge/vertx-go-tcp-eventbus-bridge)- Event bus client for Go-lang using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Smalltalk](https://github.com/mumez/VerStix)- Event bus client for [Pharo Smalltalk](http://pharo.org/) using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge).
* [Java](https://github.com/nielsbaloe/vertxui/tree/master/vertxui-core/src/main/java/live/connector/vertxui/client/transport) - Event bus support in JavaScript through Java code.
* [Elixir](https://github.com/PharosProduction/ExVertx) - Event bus support for Elixir apps using TCP socket.
* [Rust](https://github.com/aesteve/vertx-eventbus-client-rs) - Event bus client for Rust applications through TCP.

## Vert.x Event Bus Extensions

* [Eventbus Service](https://github.com/wowselim/eventbus-service) - Code generator for type-safe event bus communication via simple Kotlin interfaces.

## Cluster Managers

*Implementations of the Vert.x cluster manager SPI*

* [Hazelcast Cluster Manager](https://github.com/vert-x3/vertx-hazelcast) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Hazelcast cluster manager.
* [Ignite Cluster Manager](https://github.com/vert-x3/vertx-ignite) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Ignite cluster manager.
* [JGroups Cluster Manager](https://github.com/vert-x3/vertx-jgroups) - JGroups cluster manager.
* [Zookeeper Cluster Manager](https://github.com/vert-x3/vertx-zookeeper) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Zookeeper cluster manager.
* [Atomix Cluster Manager](https://github.com/atomix/atomix-vertx) - An [Atomix](http://atomix.io) based cluster manager implementation for Vert.x 3.
* [Infinispan Cluster Manager](https://github.com/vert-x3/vertx-infinispan) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Infinispan cluster manager.
* [Consul Cluster Manager](https://github.com/reactiverse/consul-cluster-manager) - Consul cluster manager.

## Cloud Support

* [OpenShift DIY cartridge](https://github.com/vert-x3/vertx-openshift-diy-quickstart) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - OpenShift DIY Cartridge using Vert.x.
* [OpenShift Vert.x cartridge](https://github.com/vert-x3/vertx-openshift-cartridge) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - OpenShift Vert.x Cartridge using Vert.x.
* [AWS SDK](https://github.com/reactiverse/aws-sdk) - Use AWS Java SDK v2 (async) with Vert.x

## Microservices

* [Service Discovery](https://github.com/vert-x3/vertx-service-discovery) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery" height="16px"> - Vert.x Service Discovery.
* [Circuit Breaker](https://github.com/vert-x3/vertx-circuit-breaker) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Circuit Breaker" height="16px"> - Vert.x Circuit Breaker.
* [Service Discovery - Consul](https://github.com/vert-x3/vertx-service-discovery) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Consul" height="16px"> - [Consul](https://www.consul.io/) extension to Vert.x Service Discovery.
* [Service Discovery - Docker links](https://github.com/vert-x3/vertx-service-discovery) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Docker Links" height="16px"> - [Docker](https://www.docker.com/) extension to Vert.x Service Discovery.
* [Service Discovery - Kubernetes](https://github.com/vert-x3/vertx-service-discovery) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Kubernetes" height="16px"> - [Kubernetes](http://kubernetes.io/) extension to Vert.x Service Discovery.
* [Service Discovery - Redis backend](https://github.com/vert-x3/vertx-service-discovery) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Redis backend" height="16px"> - [Redis](http://redis.io/) storage backend for Vert.x Service Discovery.
* [Vert.x GraphQL Service Discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) - [GraphQL](http://graphql.org/) service discovery and querying for your Vert.x microservices.
* [Resilience4j](https://github.com/resilience4j/resilience4j) - Resilience4j is a fault tolerance library designed for Java8 and functional programming. Resilience4j provides modules for Circuit Breaking, Rate Limiting, Bulkheading, Automatic retrying, Response caching and Metric measuring.
* [Failsafe](https://failsafe.dev/) - Failsafe is a lightweight, *zero-dependency* library for handling failures in Java 8+. Concise API. Integration with libraries that use their own schedulers for async executions, such as Akka or Vert.x. [Vert.x example](https://github.com/failsafe-lib/failsafe/blob/master/examples/src/main/java/dev/failsafe/examples/VertxExample.java)
* [Autonomous Services](https://github.com/mikand13/autonomous-services) - A toolkit for creating autonomous services. An architecture that leverages vert.x and nannoq-tools to provide an event-based reactive architecure without centralized components, neither for communication or data, providing a theoretically linear scalability across the architecture.
* [Apache ServiceComb Java Chassis](https://github.com/apache/servicecomb-java-chassis) - ServiceComb Java Chassis is a Software Development Kit (SDK) for rapid development of microservices in Java, providing service registration, service discovery, dynamic routing, and service management features.
* [SmallRye Fault Tolerance](https://github.com/smallrye/smallrye-fault-tolerance) - SmallRye Fault Tolerance is an implementation of Eclipse MicroProfile Fault Tolerance with additional features not defined by the specification. Native support of [Vert.x](https://smallrye.io/docs/smallrye-fault-tolerance/6.2.6/integration/event-loop.html) and [Mutiny](https://smallrye.io/docs/smallrye-fault-tolerance/6.2.6/reference/asynchronous.html#async-types).

## Search Engines

* [Vert.x Elasticsearch Service](https://github.com/englishtown/vertx-elasticsearch-service) - Vert.x 3 [Elasticsearch](https://www.elastic.co/) service with event bus proxying.
* [Vert.x Solr Service](https://github.com/englishtown/vertx-solr-service) - Vert.x 3 Solr service with event bus proxying.

## Service Factory

* [Service Factory](https://github.com/vert-x3/vertx-service-factory) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Service Factory.
* [Maven Service Factory](https://github.com/vert-x3/vertx-maven-service-factory) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Maven Vert.x Service Factory.
* [HTTP Service Factory](https://github.com/vert-x3/vertx-http-service-factory) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x HTTP Service Factory.
* [Node.js Service Factory](https://github.com/mellster2012/vertx-nodejs-service-factory) - Vert.x Node.js Service Factory.
* [Eclipse SISU Service Factories](https://github.com/cstamas/vertx-sisu) - Vert.x integration with [Eclipse SISU](https://www.eclipse.org/sisu/) DI container offering alternatives for `vertx-service-factory` and `vertx-maven-service-factory`.

## Config

* [Vert.x Config AWS SSM Store](https://github.com/Finovertech/vertx-config-aws-ssm) - A [config store](http://vertx.io/docs/vertx-config/java/) implementation for retrieving configuration values from the [AWS EC2 SSM Parameter Store](https://aws.amazon.com/ec2/systems-manager/parameter-store/).
* [Vert.x Boot](https://github.com/jponge/vertx-boot) - Deploying verticles from a HOCON configuration.

## Dependency Injection

* [Vert.x Guice](https://github.com/englishtown/vertx-guice) - Vert.x verticle factory for Guice dependency injection.
* [Vert.x HK2](https://github.com/englishtown/vertx-hk2) - Vert.x verticle factory for HK2 dependency injection.
* [Spring Vert.x Extension](https://github.com/amoAHCP/spring-vertx-ext) - Vert.x verticle factory for Spring DI injection.
* [Vert.x Beans](https://github.com/rworsnop/vertx-beans) - Inject Vert.x objects as beans into your Spring application.
* [QBit](https://github.com/advantageous/qbit) - QBit works with Spring DI and Spring Boot (and of course Vert.x). Allows you to use QBit, Vert.x, Spring DI and Spring Boot in the same application.
* [Vert.x Eclipse SISU](https://github.com/cstamas/vertx-sisu) - Vert.x integration with [Eclipse SISU](https://www.eclipse.org/sisu/) DI container.
* [Vert.x Spring Verticle Factory](https://github.com/juanavelez/vertx-spring-verticle-factory) - A Vert.x Verticle Factory that makes use of Spring to obtain and configure Verticles.
* [Glue](https://github.com/vinscom/glue) - Proven and opinionated programming, and configuration model for Java and Vert.x based applications. Inspired from ATG Nucleus, provides powerful layer base configuration management using simple properties file.

## Testing

* [Vert.x Unit](https://github.com/vert-x3/vertx-unit) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Async polyglot unit testing for Vert.x.
* [Vert.x JUnit5](https://github.com/vert-x3/vertx-junit5) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Async unit testing for Vert.x with junit5.
* [Vert.x WireMongo](https://github.com/noenv/vertx-wiremongo) - Lightweight MongoDB mocking for Vert.x

## Development Tools

* [Vert.x shell](https://github.com/vert-x3/vertx-shell)  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Allows for interaction with Vert.x from the command line.
* [Vert.x health check](https://github.com/vert-x3/vertx-health-check) - Allows for remote health checking in Vert.x projects.
* [Vert.x Hot](https://github.com/dazraf/vertx-hot) - A Maven plugin for the hot-deploy of Maven Vert.x projects.
* [slush-vertx](https://www.npmjs.com/package/slush-vertx) - A template driven Vert.x project generator for different languages and build tools.
* [Vert.x for Visual Studio Code](https://github.com/pmlopes/VertxSnippet) - A Visual Studio Code (polyglot) plugin for Vert.x. Also available from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=pmlopes.vertxsnippet).
* [Vert.x Starter](http://www.jetdrone.xyz/vertx-starter/) - A browser-based project starter and project templates for Vert.x applications.
* [Vert.x LiveReload](https://github.com/ybonnel/vertx-livereload) - A simple livereload server for Vert.x applications.
* [openapi-generator](https://github.com/OpenAPITools/openapi-generator) - OpenAPI Generator allows generation of API client libraries (SDK generation), server stubs, documentation and configuration automatically given an OpenAPI Spec (v2, v3).

## Miscellaneous

* [Vert.x Child Process](https://github.com/vietj/vertx-childprocess) - Spawn child process from Vert.x.
* [vertx-redisques](https://github.com/swisspush/vertx-redisques) - A highly scalable redis-persistent queuing system for Vert.x.
* [Simple File Server](https://github.com/pitchpoint-solutions/sfs) - An OpenStack Swift compatible distributed object storage server that can serve and securely store billions of large and small files using minimal resources implemented using Vert.x.
* [Vert.x Boot](https://github.com/jponge/vertx-boot) - Deploying verticles from a HOCON configuration.
* [GDH](https://github.com/maxamel/GDH) - Generalized Diffie-Hellman key exchange Java library built on top of Vert.x.
* [vertx-values](https://github.com/imrafaelmerino/vertx-values) - Send immutable and persistent JSON from [json-values](https://github.com/imrafaelmerino/json-values) across the event bus.

## Distribution

* [Vert.x Stack](https://github.com/vert-x3/vertx-stack) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x + the endorsed modules.

## Examples

* [Vert.x blueprint - Microservice application](https://github.com/sczyh30/vertx-blueprint-microservice) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x blueprint showing how to build a complex microservice application.
* [Vert.x blueprint - Job Queue](https://github.com/sczyh30/vertx-blueprint-job-queue) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x blueprint showing how to build a distributed job processing application.
* [Vert.x blueprint - TODO backend](https://github.com/sczyh30/vertx-blueprint-todo-backend) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x blueprint showing how to build a backend for a TODO application.
* [Vert.x examples](https://github.com/vert-x3/vertx-examples) <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x examples including web examples, how to use the official database clients, etc.
* [Vert.x feeds](https://github.com/aesteve/vertx-feeds) - Example of an RSS aggregator built using Vert.x, Gradle, MongoDB, Redis, Handlebars templates, AngularJS, the event bus and SockJS.
* [Vert.x Markdown service](https://github.com/aesteve/vertx-markdown-service) - Example on how to use [service-proxy](https://github.com/vert-x3/vertx-service-proxy) with Gradle.
* [Example using event bus and service proxies to connect vertx and node](https://github.com/advantageous/vertx-node-ec2-eventbus-example) - Step by step example with wiki description showing how to connect Vert.x and Node using event bus and service proxies.
* [Vert.x Todo-Backend implementation](https://github.com/aesteve/todo-backend-vertx) - Pure Java 8 implementation of the Todo MVC backend. Uses a Vert.x LocalMap for storage.
* [Kotlin Todo-Backend implementation](https://github.com/aesteve/vertx-kotlin-todomvc) - Kotlin implementation of the Todo MVC backend.
* [Scala Todo-Backend implementation](https://github.com/aesteve/vertx-scala-todomvc) - Scala implementation of the Todo MVC backend.
* [Grooveex Todo-Backend implementation](https://github.com/aesteve/todo-backend-grooveex) - Todo MVC backend implementation with Vert.x + Groovy + some syntactic sugar + DSL routing facilities.
* [Vert.x Gradle Starter](https://github.com/yyunikov/vertx-gradle-starter) - Java 8 starter application with example of using Vert.x with Gradle build system, profiles configuration and SLF4J.
* [Vert.x Gentics Mesh Example](https://github.com/gentics/mesh-vertx-example) - Example on how to build a template-based web server with Gentics Mesh and handlebars.
* [HTTP/2 showcase](https://github.com/aesteve/http2-showcase) - A simple demo, showing how HTTP/2 can drastically improve user experience when a huge latency is involved.
* [Vert.x Music Store](https://github.com/tsegismont/vertx-musicstore) - An example application on how to build Vert.x applications with RxJava.
* [Crabzilla](https://github.com/crabzilla/crabzilla) - Yet another Event Sourcing experiment. A project exploring Vert.x to develop Event Sourcing / CQRS applications.
* [Vert.x PostgreSQL Starter](https://github.com/BillyYccc/vertx-postgresql-starter) - A starter to build a monolithic CRUD RESTful Web Service with Vert.x stack and PostgreSQL.
* [Cloud Foundry](https://github.com/amdelamar/vertx-cloudfoundry) - An example Vert.x for deploying to a [Cloud Foundry](https://www.cloudfoundry.org/) service provider.
* [Knative](https://github.com/knative/docs/tree/main/code-samples/community/serving/helloworld-vertx) - An example application on how to use [Reactive Extensions Vert.x](https://github.com/vert-x3/vertx-rx) with [Knative](https://github.com/knative).
* [Starter Single Verticle API](https://github.com/jgarciasm/ssv-api) - REST API Starter and Project Template ready to deploy with lots of plumbing code, examples, and documentation to quickly develope an API with almost no knowledge of vert.x and without any waste of time.
* [AI model output API based on PMML with Vert.x](https://github.com/immusen/vertx-pmml) - High performance PMML evaluator API based on Vert.x. Supports dynamic routing configuration for multiple PMML models via JSON.

## Deployment

* [Vert.x Deploy Application](https://github.com/msoute/vertx-deploy-tools) - (Seamless) deploy to AWS based Vert.x application clusters.

## Utilities

* [Chime](https://github.com/LisiLisenok/Chime) - Time scheduler working on Vert.x event bus allowing for scheduling with *cron-style* and *interval* timers.
* [Vert.x Cron](https://github.com/diabolicallabs/vertx-cron) - Schedule events with cron specifications. Has event bus and Observable versions.
* [Vert.x CronUtils](https://github.com/NoEnv/vertx-cronutils) - An abstraction of cron-utils for the vertx scheduler. Unix, Cron4j and Quartz style expressions are supported.
* [Vert.x Scheduler](https://github.com/zero88/vertx-scheduler) - A lightweight plugable scheduler based on plain Vert.x core without any external libs for scheduling with *cron-style* and *interval* timers with a detail *monitor* on both sync and async task.
* [Vert.x POJO config](https://github.com/aesteve/vertx-pojo-config) - Allows for mapping between standard JSON configuration and a (type-safe) configuration Java bean. Also allows the configuration bean to be validated through JSR 303.
* [Vert.x Async](https://github.com/gchauvet/vertx-async) - Portage of caolan/async nodejs module to Vert.x framework that provides helpers methods for common async patterns.
* [Vert.x JOLT](https://github.com/lusoalex/vertx-jolt) - JSON to JSON transformation tool based on the original bazaarvoice JOLT project. Helpful to transform different json structure into an expected json format.
* [Vert.x Dependent Verticle Deployer](https://github.com/juanavelez/vertx-dependent-verticle-deployer) - A Vert.x Verticle intended to deploy verticles and their dependent verticles.
* [Vert.x Dataloader](https://github.com/engagingspaces/vertx-dataloader) - Java port of Facebook Dataloader for Vert.x. Efficient batching and caching for your data layer.
* [Vert.x Util](https://github.com/juanavelez/vertx-util) - A collection of Vert.x utility methods.
* [Vert.x Web Accesslog](https://github.com/romanpierson/vertx-web-accesslog) - Just a simple handler to be used in Vert.x Web to generate access logs.
* [Vert.x GraphQL Utils](http://github.com/tibor-kocsis/vertx-graphql-utils) - A route handler and Vert.x compatible interfaces to handle GraphQL queries in Vert.x and Vert.x Web.
* [Nannoq-Tools](https://noriginmedia.github.io/nannoq-tools/) - Nannoq-Tools is a toolkit for constructing robust, scalable and distributed applications leveraging Vert.x including modules for authentication, cluster management, Firebase Cloud Messaging, DynamoDB, fully generic queries, REST, and more.
* [Contextual logging](https://github.com/reactiverse/reactiverse-contextual-logging) - Mapped Diagnostic Context (MDC) that works with the Vert.x event-loop model.
* [Vert.x JsonPath](https://github.com/NoEnv/vertx-jsonpath) - A very basic implementation of JsonPath using Vert.x’s JsonObject and JsonArray, mimicking their getX, containsKey, put and remove methods.

## Presentations

* [Vert.x Youtube channel](https://www.youtube.com/channel/UCGN6L3tRhs92Uer3c6VxOSA)

## Community

* [User Group](https://groups.google.com/forum/?fromgroups#!forum/vertx) - Discuss all user issues related to *using* Vert.x.
* [Developer Group](https://groups.google.com/forum/?fromgroups#!forum/vertx-dev) - A group for Vert.x core *developers* and *contributors*.
* [Discord Server](https://discord.gg/KzEMwP2) - Chat about any Vert.x-related topic.
* [Issues](https://github.com/vert-x3/issues/issues) - Vert.x core issue tracker.
* [Wiki](https://github.com/vert-x3/wiki/wiki) - Contains useful information about Vert.x.
* [Blog](http://vertx.io/blog/) - The official Vert.x blog containing many tutorials and other information.

## Articles

* [Embracing Reactive Applications on JVM: a Deep Dive into Modern I/O Models and Vert.x](https://www.infoq.com/articles/reactive-java-vertx-deep-dive/)
* [Going reactive with Eclipse Vert.x and RX Java](https://blogs.oracle.com/javamagazine/post/going-reactive-with-eclipse-vertx-and-rxjava)
* [Vert.x 3.3.0 Features Enhanced Networking Microservices, Testing and More](https://www.infoq.com/news/2016/06/Vert.x-3.3.0-release-features)
* [Interview with Tim Fox About Vert.x 3, the Original Reactive, Microservice Toolkit for the JVM](http://www.infoq.com/articles/vertx-3-tim-fox)

## Tutorials

* [Introduction to Vert.x](https://vertx.io/get-started/)

## Front-End

* [VertxUI](https://github.com/nielsbaloe/vertxui) - A pure Java front-end toolkit with descriptive fluent views-on-models, POJO traffic, JUnit testing on the virtual DOM or mixed-language on a real DOM, and more.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
