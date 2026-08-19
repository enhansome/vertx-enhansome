# Awesome Vert.x with stars

[<img src="vertx-logo.svg" align="right" width="250" alt="Vert.x logo">](http://vertx.io)

*Awesome Vert.x* is a list of awesome frameworks, libraries or other components related to
[Vert.x](https://github.com/eclipse/vert.x) ⭐ 14,684 | 🐛 230 | 🌐 Java | 📅 2026-08-17.

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
* [Game development](#game-development)
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

* [Vert.x Maven plugin](https://github.com/reactiverse/vertx-maven-plugin) ⭐ 81 | 🐛 7 | 🌐 Java | 📅 2026-07-24
* [Vert.x Codegen Gradle plugin](https://github.com/bulivlad/vertx-codegen-plugin) ⭐ 9 | 🐛 0 | 🌐 Groovy | 📅 2020-06-18 - A Gradle plugin to facilitate the codegen usage for Vert.x Java projects.
* [Vert.x Gradle plugin](https://plugins.gradle.org/plugin/io.vertx.vertx-plugin)

## Web Frameworks

* [Vert.x Web](https://github.com/vert-x3/vertx-web) ⭐ 1,151 | 🐛 153 | 🌐 Java | 📅 2026-08-10  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Full featured web toolkit for Vert.x.
* [QBit](https://github.com/advantageous/qbit) ⭐ 707 | 🐛 61 | 🌐 Java | 📅 2018-01-18 - REST and WebSocket method call marshaling and reactive library.
* [Cloudopt Next](https://github.com/cloudoptlab/cloudopt-next) ⭐ 350 | 🐛 3 | 🌐 Kotlin | 📅 2024-02-25 - Cloudopt Next is a very lightweight and modern, JVM-based, full stack kotlin framework designed for building modular, easily testable JVM applications with support for Java, Kotlin language, crafted from the best of breed Java libraries and standards.
* [Jubilee](https://github.com/isaiah/jubilee) ⭐ 326 | 🐛 8 | 🌐 Ruby | 📅 2017-01-04 - A rack compatible Ruby HTTP server built on Vert.x 3.
* [Donkey](https://github.com/AppsFlyer/donkey) ⭐ 298 | 🐛 8 | 🌐 Java | 📅 2023-12-05 - Modern Clojure HTTP server and client built for ease of use and performance.
* [REST.VertX](https://github.com/zandero/rest.vertx) ⭐ 168 | 🐛 6 | 🌐 Java | 📅 2026-06-21 - Lightweight JAX-RS (RestEasy) like annotation processor for Vert.x verticals.
* [Kovert](https://github.com/kohesive/kovert) ⭐ 158 | 🐛 9 | 🌐 Kotlin | 📅 2018-11-15 - Invisible REST framework for Kotlin + Vert.x Web.
* [Vert.x Jersey](https://github.com/englishtown/vertx-jersey) ⭐ 155 | 🐛 18 | 🌐 Java | 📅 2021-10-28 - Create JAX-RS [Jersey](https://eclipse-ee4j.github.io/jersey/) resources in Vert.x.
* [Knot.x](https://github.com/Cognifide/knotx) ⭐ 126 | 🐛 16 | 📅 2022-03-28 - Efficient & high-performance integration platform for modern websites built on Vert.x 3.
* [vertx-rest](https://github.com/dream11/vertx-rest) ⭐ 49 | 🐛 3 | 🌐 Java | 📅 2025-12-23 - Abstraction over resteasy-vertx to simplify writing a Vert.x REST application based on JAX-RS annotations.
* [Vert.x Vaadin](https://github.com/mcollovati/vertx-vaadin) ⚠️ Archived - Run Vaadin applications on Vert.x.
* [Atmosphere Vert.x](https://github.com/Atmosphere/atmosphere-vertx) ⭐ 44 | 🐛 3 | 🌐 Java | 📅 2026-02-24 - Realtime Client Server Framework for the JVM, supporting WebSockets and Server Sent Events with Cross-Browser Fallbacks.
* [Irked](https://github.com/GreenfieldTech/irked) ⭐ 36 | 🐛 0 | 🌐 Java | 📅 2026-08-08 - Annotations-based configuration for Vert.x Web, with a controller framework and expressive APIs for REST.
* [vertx-rest-storage](https://github.com/swisspush/vertx-rest-storage) ⭐ 19 | 🐛 18 | 🌐 Java | 📅 2026-08-03 - Persistence for REST resources in the filesystem or a redis database.
* [Serverx](https://github.com/lukehutch/serverx) ⭐ 19 | 🐛 4 | 🌐 Java | 📅 2022-09-01 - Allows you to quickly and easily set up a Vert.x-powered server using only route handler annotations.
* [Handlers](https://github.com/spriet2000/vertx-handlers-http) ⭐ 11 | 🐛 1 | 🌐 Java | 📅 2020-10-13 - Open web framework for Vert.x.
* [SCX](https://github.com/scx567888/scx) ⚠️ Archived - An open and easy-to-use web framework, most functions are based on annotations.

## Authentication Authorisation

* [Vert.x Auth SQL](https://github.com/eclipse-vertx/vertx-auth) ⭐ 175 | 🐛 56 | 🌐 Java | 📅 2026-08-10  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x authentication/authorisation based on the Vert.x SQL client and a relational database.

* [Vert.x Auth JWT](https://github.com/eclipse-vertx/vertx-auth/tree/master/vertx-auth-jwt) ⭐ 175 | 🐛 56 | 🌐 Java | 📅 2026-08-10  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation based on JSON Web Tokens.

* [Vert.x Auth htdigest](https://github.com/eclipse-vertx/vertx-auth/tree/master/vertx-auth-htdigest) ⭐ 175 | 🐛 56 | 🌐 Java | 📅 2026-08-10  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [Apache htdigest](https://httpd.apache.org/docs/2.4/programs/htdigest.html).

* [Vert.x Auth OAuth2](https://github.com/eclipse-vertx/vertx-auth/tree/master/vertx-auth-oauth2) ⭐ 175 | 🐛 56 | 🌐 Java | 📅 2026-08-10 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [OAuth 2](https://oauth.net/2/).

* [Vert.x Auth htpasswd](https://github.com/eclipse-vertx/vertx-auth/tree/master/vertx-auth-htpasswd) ⭐ 175 | 🐛 56 | 🌐 Java | 📅 2026-08-10 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [htpasswd](https://httpd.apache.org/docs/2.4/programs/htpasswd.html).

* [Vert.x-Pac4j](https://github.com/pac4j/vertx-pac4j) ⭐ 135 | 🐛 1 | 🌐 Java | 📅 2026-08-07 - Vert.x authentication/authorisation implemented using [pac4j](http://www.pac4j.org/).

* [Vert.x Auth Mongo](https://github.com/vert-x3/vertx-auth/tree/master/vertx-auth-mongo) ⭐ 19 | 🐛 2 | 🌐 Java | 📅 2026-08-07  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Authorisation/Authentication based on [MongoDB](https://www.mongodb.com/).

## Database Clients

*Clients for connecting to databases*

* [vertx-pojo-mapper](https://github.com/BraintagsGmbH/vertx-pojo-mapper) ⭐ 56 | 🐛 41 | 🌐 HTML | 📅 2018-08-23 - Non-blocking POJO mapping for MySQL and MongoDB.

* [vertx-mysql-binlog-client](https://github.com/guoyu511/vertx-mysql-binlog-client) ⭐ 16 | 🐛 0 | 🌐 Java | 📅 2017-10-29 - A Vert.x client for tapping into MySQL replication stream.

* Relational Databases
  * [Reactive SQL Client](https://github.com/eclipse-vertx/vertx-sql-client) ⭐ 912 | 🐛 77 | 🌐 Java | 📅 2026-08-13 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - High performance reactive SQL client.
  * [jOOQ](https://github.com/jklingsporn/vertx-jooq) ⭐ 392 | 🐛 47 | 🌐 Java | 📅 2024-01-11 - Doing typesafe, asynchronous SQL and generate code using jOOQ.
  * [JDBC](https://github.com/vert-x3/vertx-jdbc-client) ⭐ 131 | 🐛 32 | 🌐 Java | 📅 2026-08-10 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous interface around a JDBC datasource.
  * [MySQL / PostgreSQL](https://github.com/vert-x3/vertx-mysql-postgresql-client) ⭐ 121 | 🐛 30 | 🌐 Java | 📅 2023-05-12 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous Client for MySQL/PostgreSQL.
  * [PostgreSQL](https://github.com/vietj/reactive-pg-client) ⭐ 75 | 🐛 13 | 🌐 Java | 📅 2019-07-19 - Reactive PostgreSQL Client.
  * [database](https://github.com/susom/database) ⭐ 43 | 🐛 4 | 🌐 Java | 📅 2026-08-12 - Client for Oracle, PostgreSQL, SQL Server, HyperSQL, etc. designed for security, correctness, and ease of use.
  * [jOOQx](https://github.com/zero88/jooqx) ⭐ 34 | 🐛 33 | 🌐 Java | 📅 2026-08-07 - Leverages the power of typesafe SQL from `jOOQ DSL` and uses the reactive and non-blocking SQL driver from Vert.x.
  * [Exposed Vert.x SQL Client](https://github.com/huanshankeji/exposed-vertx-sql-client) ⭐ 10 | 🐛 16 | 🌐 Kotlin | 📅 2026-07-25 - Kotlin's [Exposed](https://github.com/JetBrains/Exposed) ⭐ 9,281 | 🐛 167 | 🌐 Kotlin | 📅 2026-08-18 on top of [Vert.x Reactive SQL Client](https://github.com/eclipse-vertx/vertx-sql-client) ⭐ 912 | 🐛 77 | 🌐 Java | 📅 2026-08-13.

* NoSQL Databases
  * [SirixDB](https://github.com/sirixdb/sirix/tree/master/bundles/sirix-rest-api) ⭐ 1,214 | 🐛 9 | 🌐 Java | 📅 2026-08-18 - Non-blocking SirixDB HTTP-server.
  * [Redis](https://github.com/vert-x3/vertx-redis-client) ⭐ 142 | 🐛 29 | 🌐 Java | 📅 2026-08-11 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Asynchronous API to interact with Redis.
  * [MongoDB](https://github.com/vert-x3/vertx-mongo-client) ⭐ 63 | 🐛 27 | 🌐 Java | 📅 2026-08-10 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - An asynchronous client for interacting with a MongoDB database.
  * [Cassandra](https://github.com/englishtown/vertx-cassandra) ⭐ 40 | 🐛 7 | 🌐 Java | 📅 2023-03-19 - Asynchronous API to interact with Cassandra and Cassandra Mapping.
  * [Cassandra](https://github.com/vert-x3/vertx-cassandra-client) ⭐ 35 | 🐛 3 | 🌐 Java | 📅 2026-08-10 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - A Vert.x client allowing applications to interact with a Cassandra service.
  * [Aerospike](https://github.com/dream11/vertx-aerospike-client) ⭐ 32 | 🐛 3 | 🌐 Java | 📅 2025-12-22 - Asynchronous and non-blocking API to interact with Aerospike server. Uses [AerospikeClient's](https://github.com/aerospike/aerospike-client-java) ⭐ 248 | 🐛 21 | 🌐 Java | 📅 2026-08-18 async commands internally and handles the result on the Vert.x Context.
  * [RxFirestore](https://github.com/pjgg/rxfirestore) ⭐ 9 | 🐛 2 | 🌐 Java | 📅 2022-02-11 - Non-blocking Firestore SDK written in a reactive way.
  * [OrientDB](https://github.com/cstamas/vertx-orientdb) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2017-11-21 - Non-blocking OrientDB server integration.
  * [MarkLogic](https://github.com/etourdot/vertx-marklogic) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2016-05-27 - Asynchronous client for Marklogic Database Server.
  * [Bitsy](https://github.com/cstamas/vertx-bitsy) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2017-02-25 - Non-blocking Bitsy Graph server integration.
  * [DGraph](https://github.com/aesteve/vertx-dgraph-client) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2019-01-14 - An example on how to build a Vert.x gRPC compliant client. Here targeting [dgraph](https://docs.dgraph.io)
  * [Neo4j Java Driver Vert.x](https://github.com/romanbsd/neo4j-java-driver-vertx) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2026-08-15 - Vert.x wrapper around the Neo4j Java Driver.
  * [MongoDB](https://github.com/imrafaelmerino/vertx-mongo-effect) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2024-11-23 - Pure functional and reactive MongoDB client on top of [Vert.x Effect](https://github.com/imrafaelmerino/vertx-mongo-effect) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2024-11-23. Full support for retry, fallback and recovery operations.

## Integration

* Server-Sent Events
  * [jEaSSE](https://github.com/mariomac/jeasse) ⭐ 68 | 🐛 3 | 🌐 Java | 📅 2018-11-05 - Java Easy SSE. A simple, lightweight implementation of SSE.
  * [vertx-sse](https://github.com/aesteve/vertx-sse) ⭐ 50 | 🐛 3 | 🌐 Java | 📅 2019-12-04 - Vert.x SSE implementation + event-bus SSE bridge.

* Mail
  * [SMTP](https://github.com/vert-x3/vertx-mail-client) ⭐ 40 | 🐛 15 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Async SMTP client.

* REST
  * [openapi4j adapter for Vert.x](https://github.com/openapi4j/openapi4j/tree/master/openapi-operation-adapters/openapi-operation-vertx) ⚠️ Archived - OpenAPI 3 request validator and router factory alternative.
  * [Retrofit adapter for Vert.x](https://github.com/vietj/retrofit-vertx) ⭐ 33 | 🐛 4 | 🌐 Java | 📅 2022-02-27 - A highly scalable adapter for Retrofit with Vert.x.
  * [Vert.x Effect HTTP client](https://github.com/imrafaelmerino/vertx-effect) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2024-11-23 - Pure functional and reactive HTTP client using [Vert.x Effect](https://github.com/imrafaelmerino/vertx-effect) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2024-11-23 with OAuth support and retry, fallback and recovery operations.

* File Server
  * [Vert.x TFTP Client](https://github.com/OneManCrew/vertx-tftp-client) ⭐ 3 | 🐛 1 | 🌐 Java | 📅 2021-06-07 - TFTP client for Vert.x support download/upload files.

* Messaging
  * [AMQP 1.0 - Kafka bridge](https://github.com/rhiot/amqp-kafka-bridge) ⭐ 338 | 🐛 17 | 🌐 Java | 📅 2026-08-14 - Bridge for sending/receiving messages to/from Apache Kafka using the AMQP 1.0 protocol.
  * [MQTT](https://github.com/vert-x3/vertx-mqtt) ⭐ 214 | 🐛 47 | 🌐 Java | 📅 2026-08-11 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Provides two different components: an MQTT server for handling all the MQTT communication and messages exchanges with clients and an MQTT client for sending and receiving messages against an MQTT broker.
  * [The White Rabbit](https://github.com/viartemev/the-white-rabbit) ⭐ 130 | 🐛 13 | 🌐 Kotlin | 📅 2026-08-14 - An asynchronous RabbitMQ (AMQP) client based on Kotlin coroutines.
  * [Kafka Client](https://github.com/vert-x3/vertx-kafka-client) ⭐ 90 | 🐛 29 | 🌐 Java | 📅 2026-08-10 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - A Kafka client.
  * [Vert.x Kafka Client](https://github.com/vert-x3/vertx-kafka-client) ⭐ 90 | 🐛 29 | 🌐 Java | 📅 2026-08-10 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Apache Kafka client for reading and sending messages from/to an Apache Kafka cluster.
  * [RabbitMQ](https://github.com/vert-x3/vertx-rabbitmq-client) ⭐ 76 | 🐛 16 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - A RabbitMQ client (AMQP 0.9.1).
  * [STOMP](https://github.com/vert-x3/vertx-stomp) ⭐ 36 | 🐛 22 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - A Kafka client and server.
  * [kafka](https://github.com/cyngn/vertx-kafka) ⭐ 31 | 🐛 3 | 🌐 Java | 📅 2016-03-21 - Kafka client for consuming and producing messages.
  * [ZeroMQ](https://github.com/dano/vertx-zeromq) ⭐ 13 | 🐛 2 | 🌐 Java | 📅 2026-01-15 - ZeroMQ Event Bus bridge.
  * [AMQP 1.0](https://github.com/vert-x3/vertx-amqp-bridge) ⭐ 8 | 🐛 2 | 🌐 Java | 📅 2026-05-05 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Interact with AMQP 1.0 servers using the Vert.x Producer and Consumer APIs.
  * [WAMP Broker](https://github.com/i22-digitalagentur/vertx-wamp) ⭐ 2 | 🐛 2 | 🌐 Java | 📅 2021-04-03 - A WAMP broker you can embed into your Vert.x application.
  * [Azure ServiceBus](https://github.com/TextBack/vertx-azure-servicebus) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2023-12-15 - Azure [ServiceBus](https://azure.microsoft.com/en-us/products/service-bus/) producer and consumer (fully async, doesn't use Microsoft Azure SDK).

* JavaEE
  * [Weld](https://github.com/weld/weld-vertx) ⚠️ Archived - Brings the CDI programming model into the Vert.x ecosystem (register CDI observer methods as Vert.x message consumers, CDI-powered Verticles, define routes in a declarative way, etc.).
  * [JCA adaptor](https://github.com/vert-x3/vertx-jca) ⭐ 10 | 🐛 1 | 🌐 Java | 📅 2023-05-12 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Java Connector Architecture Adaptor for the Vert.x event bus.

* Meteor
  * [Meteor](https://github.com/jmusacchio/vertxbus/) ⭐ 17 | 🐛 0 | 🌐 JavaScript | 📅 2017-10-23 - Meteor integration support through Vert.x event bus.

* Metrics
  * [Micrometer metrics](https://github.com/vert-x3/vertx-micrometer-metrics) ⭐ 55 | 🐛 1 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Metrics implementation using Micrometer metrics.
  * [DropWizard metrics](https://github.com/vert-x3/vertx-dropwizard-metrics) ⭐ 35 | 🐛 4 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Metrics implementation using DropWizard metrics.
  * [OpenTsDb Metrics](https://github.com/cyngn/vertx-opentsdb) ⭐ 11 | 🐛 2 | 🌐 Java | 📅 2016-03-21 - [OpenTsDb](http://opentsdb.net/) metrics client for Vert.x.
  * [Hawkular metrics](https://github.com/tsegismont/vertx-monitor) ⚠️ Archived - [Hawkular](http://www.hawkular.org/) implementation of the Vert.x Metrics SPI.
  * [Bosun Monitoring](https://github.com/cyngn/vertx-bosun) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2015-09-15 - [Bosun](https://bosun.org/) client library for Vert.x.

* Netflix - Hystrix
  * [Hystrix Metrics Stream](https://github.com/kennedyoliveira/hystrix-vertx-metrics-stream.git) ⭐ 15 | 🐛 2 | 🌐 Java | 📅 2016-10-03 - Emits metrics for Hystrix Dashboard from a Vert.x application with [Hystrix](https://github.com/Netflix/Hystrix) ⭐ 24,471 | 🐛 58 | 🌐 Java | 📅 2025-12-17.

* Dart
  * [Vert.x Dart SockJS](https://github.com/wem/vertx-dart-sockjs) ⭐ 0 | 🐛 0 | 📅 2019-09-17 - [Dart](https://www.dartlang.org/) integration for [Vert.x SockJS bridge](http://vertx.io/docs/vertx-web/java/#_sockjs_event_bus_bridge) and plain SockJS with use of dart:js.

* Push Notifications
  * [Onesignal](https://github.com/jklingsporn/vertx-push-onesignal) ⭐ 16 | 🐛 1 | 🌐 Java | 📅 2020-10-12 - Send push notifications to (mobile/web) apps from your Vert.x application with [OneSignal](https://onesignal.com/).

* CNCF CloudEvents
  * [CloudEvents.io Java SDK](https://github.com/cloudevents/sdk-java) ⭐ 444 | 🐛 79 | 🌐 Java | 📅 2026-07-16 - Send and receive [CloudEvents](https://cloudevents.io/) using the [Vert.x HTTP Transport](https://github.com/cloudevents/sdk-java/blob/master/http/vertx/README.md) ⭐ 444 | 🐛 79 | 🌐 Java | 📅 2026-07-16 for CloudEvents.

## Middleware

* [Gateleen](https://github.com/swisspush/gateleen) ⭐ 84 | 🐛 46 | 🌐 Java | 📅 2026-08-17 - Middleware library based on Vert.x to build advanced JSON/REST communication servers.
* [API Framework](https://github.com/vinscom/api-framework) ⭐ 10 | 🐛 2 | 🌐 Java | 📅 2026-01-15 - Vert.x and Glue based microservice framework removing distinction between standalone and serveless application. All services can run in standalone server, but, if required, same codebase can be used to run any service as serverless application.
* [Apache Camel](https://camel.apache.org/components/vertx-component.html) - [Apache Camel](http://camel.apache.org/) component for bridging Camel with the Vert.x event bus.
* [Gravitee.io](https://gravitee.io) - An OSS API Platform including an API Gateway and an OAuth2 / OIDC authorization server based on Vert.x Core / Vert.x Web and other modules.

## Language Support

*Programming language support for Vert.x*

* [Java](https://github.com/eclipse/vert.x) ⭐ 14,684 | 🐛 230 | 🌐 Java | 📅 2026-08-17 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x main repository (including the Java API).
* [EcmaScript](https://github.com/reactiverse/es4x) ⭐ 891 | 🐛 53 | 🌐 Java | 📅 2025-12-19 - EcmaScript >=6 (JavaScript) support.
* [Kotlin](https://github.com/vert-x3/vertx-lang-kotlin) ⭐ 302 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-07 - <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Kotlin support.
* [Scala](https://github.com/vert-x3/vertx-lang-scala) ⭐ 125 | 🐛 13 | 🌐 Scala | 📅 2025-10-14 - <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Scala support.
* [JavaScript](https://github.com/vert-x3/vertx-lang-js) ⭐ 35 | 🐛 11 | 🌐 JavaScript | 📅 2024-10-17 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - JavaScript support.
* [Ruby](https://github.com/vert-x3/vertx-lang-ruby) ⭐ 15 | 🐛 8 | 🌐 Ruby | 📅 2026-04-10 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Ruby support.
* [Groovy](https://github.com/vert-x3/vertx-lang-groovy) ⭐ 14 | 🐛 0 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Groovy support.
* [Ceylon](https://github.com/vert-x3/vertx-lang-ceylon) ⚠️ Archived <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Ceylon support.
* [Php](https://github.com/vert-x-cn/vertx-lang-jphp) ⚠️ Archived - Php support.
* [Python](https://github.com/vert-x3/vertx-lang-python) ⚠️ Archived - Python support.

*Language extensions*

* [Grooveex](https://github.com/aesteve/grooveex) ⭐ 14 | 🐛 6 | 🌐 Groovy | 📅 2016-05-23 - Syntactic sugar + utilities (DSL builders, etc.) on top of [vertx-lang-groovy](https://github.com/vert-x3/vertx-lang-groovy) ⭐ 14 | 🐛 0 | 🌐 Java | 📅 2026-08-07.

## Reactive

* [QBit](https://github.com/advantageous/qbit) ⭐ 707 | 🐛 61 | 🌐 Java | 📅 2018-01-18 - Async typed actor-like lib that runs easily in Vert.x Async Callbacks. Callback management.
* [Kotlin coroutines](https://github.com/vert-x3/vertx-lang-kotlin/tree/master/vertx-lang-kotlin-coroutines) ⭐ 302 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x support for Kotlin coroutines.
* [Vert.x Rx](https://github.com/vert-x3/vertx-rx) ⭐ 155 | 🐛 5 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Reactive Extensions.
* [Vert.x Sync](https://github.com/vert-x3/vertx-sync) ⭐ 99 | 🐛 14 | 🌐 Java | 📅 2025-05-02 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x fiber support.
* [Reactive Streams](https://github.com/vert-x3/vertx-reactive-streams) ⭐ 50 | 🐛 4 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Reactive Streams.
* [vertx-util](https://github.com/cyngn/vertx-util) ⭐ 22 | 🐛 0 | 🌐 Java | 📅 2016-03-21 - Light weight promises & latches for Vert.x.
* [Vert.x Effect](https://github.com/imrafaelmerino/vertx-effect) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2024-11-23 - Pure functional and reactive library based on the IO Monad to implement any complex flow. Full support for retry, fallback and recovery operations.
* [VxRifa](https://nsforth.github.io/vxrifa) - Utility library for Vert.X that allows using strong-typed interfaces in communication through EventBus.
* [SmallRye Mutiny](https://smallrye.io/smallrye-mutiny/) - Intuitive event-driven reactive programming library for Java with [bindings for Vert.x](https://smallrye.io/smallrye-mutiny-vertx-bindings/).

## Sync Thread Non Block

* [Sync](https://github.com/vert-x3/vertx-sync) ⭐ 99 | 🐛 14 | 🌐 Java | 📅 2025-05-02 - Synchronous but non-OS-thread-blocking verticles.

## Vert.x Event Bus Clients

*Clients to connect applications to the Vert.x event bus*

* [Java](https://github.com/nielsbaloe/vertxui/tree/master/vertxui-core/src/main/java/live/connector/vertxui/client/transport) ⚠️ Archived - Event bus support in JavaScript through Java code.
* [Go](https://github.com/jponge/vertx-go-tcp-eventbus-bridge) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2018-03-15- Event bus client for Go-lang using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge) ⭐ 54 | 🐛 10 | 🌐 Java | 📅 2026-08-07.
* [Java](https://github.com/abdlquadri/vertx-eventbus-java) ⭐ 23 | 🐛 3 | 🌐 Java | 📅 2017-08-29 - Java and Android Event Bus Client.
* [Java](https://github.com/saffron-technology/vertx-eventbusbridge) ⭐ 20 | 🐛 5 | 🌐 Java | 📅 2018-11-15 - Java implementation of vertxbus.js.
* [C++11](https://github.com/julien3/vertxbuspp) ⭐ 17 | 🐛 1 | 🌐 C++ | 📅 2017-04-10 - C++11 event bus client.
* [Elixir](https://github.com/PharosProduction/ExVertx) ⭐ 16 | 🐛 0 | 🌐 Elixir | 📅 2024-12-08 - Event bus support for Elixir apps using TCP socket.
* [Java](https://github.com/danielstieger/javaxbus) ⭐ 12 | 🐛 2 | 🌐 Java | 📅 2025-06-17 - Simple Java Event Bus Client using plain TCP socket I/O.
* [Python](https://github.com/jaymine/TCP-eventbus-client-Python) ⭐ 12 | 🐛 2 | 🌐 Python | 📅 2016-08-05 - Event bus client for Python using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge) ⭐ 54 | 🐛 10 | 🌐 Java | 📅 2026-08-07.
* [Smalltalk](https://github.com/mumez/VerStix) ⭐ 10 | 🐛 0 | 🌐 Smalltalk | 📅 2017-07-03- Event bus client for [Pharo Smalltalk](http://pharo.org/) using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge) ⭐ 54 | 🐛 10 | 🌐 Java | 📅 2026-08-07.
* [Rust](https://github.com/aesteve/vertx-eventbus-client-rs) ⭐ 10 | 🐛 4 | 🌐 Rust | 📅 2023-01-09 - Event bus client for Rust applications through TCP.
* [C#](https://github.com/jaymine/TCP-eventbus-client-C-Sharp) ⭐ 6 | 🐛 2 | 🌐 C# | 📅 2016-12-16 - Event bus client for C# using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge) ⭐ 54 | 🐛 10 | 🌐 Java | 📅 2026-08-07.
* [Swift](https://github.com/tobias/vertx-swift-eventbus) ⭐ 5 | 🐛 6 | 🌐 Swift | 📅 2018-04-24 - Event bus client for [Apple's Swift](https://swift.org) using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge) ⭐ 54 | 🐛 10 | 🌐 Java | 📅 2026-08-07.
* [C](https://github.com/jaymine/TCP-eventbus-client-C) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2016-08-09 - Event bus client for C99 using the [TCP-based protocol](https://github.com/vert-x3/vertx-tcp-eventbus-bridge) ⭐ 54 | 🐛 10 | 🌐 Java | 📅 2026-08-07.
* [CLI](https://github.com/cinterloper/vxc) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2017-02-06 - Command-line binary client for Vert.x event bus - pipe in JSON, emit JSON.

## Vert.x Event Bus Extensions

* [Eventbus Service](https://github.com/wowselim/eventbus-service) ⭐ 12 | 🐛 1 | 🌐 Kotlin | 📅 2026-06-08 - Code generator for type-safe event bus communication via simple Kotlin interfaces.

## Cluster Managers

*Implementations of the Vert.x cluster manager SPI*

* [Hazelcast Cluster Manager](https://github.com/vert-x3/vertx-hazelcast) ⭐ 82 | 🐛 4 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Hazelcast cluster manager.
* [Zookeeper Cluster Manager](https://github.com/vert-x3/vertx-zookeeper) ⭐ 75 | 🐛 31 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Zookeeper cluster manager.
* [Ignite Cluster Manager](https://github.com/vert-x3/vertx-ignite) ⭐ 34 | 🐛 3 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Ignite cluster manager.
* [Consul Cluster Manager](https://github.com/reactiverse/consul-cluster-manager) ⭐ 20 | 🐛 11 | 🌐 Java | 📅 2023-12-05 - Consul cluster manager.
* [Infinispan Cluster Manager](https://github.com/vert-x3/vertx-infinispan) ⭐ 16 | 🐛 5 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Infinispan cluster manager.
* [JGroups Cluster Manager](https://github.com/vert-x3/vertx-jgroups) ⚠️ Archived - JGroups cluster manager.

## Cloud Support

* [AWS SDK](https://github.com/reactiverse/aws-sdk) ⭐ 51 | 🐛 7 | 🌐 Java | 📅 2023-09-11 - Use AWS Java SDK v2 (async) with Vert.x
* [OpenShift Vert.x cartridge](https://github.com/vert-x3/vertx-openshift-cartridge) ⚠️ Archived <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - OpenShift Vert.x Cartridge using Vert.x.
* [OpenShift DIY cartridge](https://github.com/vert-x3/vertx-openshift-diy-quickstart) ⚠️ Archived <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - OpenShift DIY Cartridge using Vert.x.

## Microservices

* [Resilience4j](https://github.com/resilience4j/resilience4j) ⭐ 10,747 | 🐛 302 | 🌐 Java | 📅 2026-07-08 - Resilience4j is a fault tolerance library designed for Java8 and functional programming. Resilience4j provides modules for Circuit Breaking, Rate Limiting, Bulkheading, Automatic retrying, Response caching and Metric measuring.
* [Failsafe](https://failsafe.dev/) - Failsafe is a lightweight, *zero-dependency* library for handling failures in Java 8+. Concise API. Integration with libraries that use their own schedulers for async executions, such as Akka or Vert.x. [Vert.x example](https://github.com/failsafe-lib/failsafe/blob/master/examples/src/main/java/dev/failsafe/examples/VertxExample.java) ⭐ 4,309 | 🐛 79 | 🌐 Java | 📅 2025-12-28
* [Apache ServiceComb Java Chassis](https://github.com/apache/servicecomb-java-chassis) ⭐ 1,940 | 🐛 230 | 🌐 Java | 📅 2026-07-01 - ServiceComb Java Chassis is a Software Development Kit (SDK) for rapid development of microservices in Java, providing service registration, service discovery, dynamic routing, and service management features.
* [Service Discovery](https://github.com/vert-x3/vertx-service-discovery) ⭐ 121 | 🐛 14 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery" height="16px"> - Vert.x Service Discovery.
* [Service Discovery - Consul](https://github.com/vert-x3/vertx-service-discovery) ⭐ 121 | 🐛 14 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Consul" height="16px"> - [Consul](https://www.consul.io/) extension to Vert.x Service Discovery.
* [Service Discovery - Docker links](https://github.com/vert-x3/vertx-service-discovery) ⭐ 121 | 🐛 14 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Docker Links" height="16px"> - [Docker](https://www.docker.com/) extension to Vert.x Service Discovery.
* [Service Discovery - Kubernetes](https://github.com/vert-x3/vertx-service-discovery) ⭐ 121 | 🐛 14 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Kubernetes" height="16px"> - [Kubernetes](http://kubernetes.io/) extension to Vert.x Service Discovery.
* [Service Discovery - Redis backend](https://github.com/vert-x3/vertx-service-discovery) ⭐ 121 | 🐛 14 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Service Discovery - Redis backend" height="16px"> - [Redis](http://redis.io/) storage backend for Vert.x Service Discovery.
* [SmallRye Fault Tolerance](https://github.com/smallrye/smallrye-fault-tolerance) ⭐ 113 | 🐛 13 | 🌐 Java | 📅 2026-08-11 - SmallRye Fault Tolerance is an implementation of Eclipse MicroProfile Fault Tolerance with additional features not defined by the specification. Native support of [Vert.x](https://smallrye.io/docs/smallrye-fault-tolerance/6.2.6/integration/event-loop.html) and [Mutiny](https://smallrye.io/docs/smallrye-fault-tolerance/6.2.6/reference/asynchronous.html#async-types).
* [Circuit Breaker](https://github.com/vert-x3/vertx-circuit-breaker) ⭐ 67 | 🐛 6 | 🌐 Java | 📅 2026-08-13 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Circuit Breaker" height="16px"> - Vert.x Circuit Breaker.
* [Vert.x GraphQL Service Discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) ⭐ 53 | 🐛 5 | 🌐 Java | 📅 2021-11-12 - [GraphQL](http://graphql.org/) service discovery and querying for your Vert.x microservices.
* [Autonomous Services](https://github.com/mikand13/autonomous-services) ⭐ 1 | 🐛 0 | 🌐 Kotlin | 📅 2019-10-13 - A toolkit for creating autonomous services. An architecture that leverages vert.x and nannoq-tools to provide an event-based reactive architecure without centralized components, neither for communication or data, providing a theoretically linear scalability across the architecture.
* [GuicedEE](https://guicedee.com) - JPMS-first Java platform built on Guice and Vert.x 5 for modular, reactive, enterprise applications. Provides MicroProfile Config, Health, Metrics, OpenAPI, REST, persistence, and more out of the box.

## Game development

* [Orbital](https://github.com/tfkfan/orbital) ⭐ 24 | 🐛 10 | 🌐 Java | 📅 2026-06-30 - Vert.x based reactive distributed game server and battle-royale multiplayers development tool. Orbital contains basic extensible matchmaker, game/game room management, websocket integration and game lifecycle management features. Closest to "Colyseus" game engine competitor. [Docs](https://tfkfan.github.io/orbital).

## Search Engines

* [Vert.x Elasticsearch Service](https://github.com/englishtown/vertx-elasticsearch-service) ⭐ 60 | 🐛 6 | 🌐 Java | 📅 2016-11-18 - Vert.x 3 [Elasticsearch](https://www.elastic.co/) service with event bus proxying.
* [Vert.x Solr Service](https://github.com/englishtown/vertx-solr-service) ⭐ 4 | 🐛 2 | 🌐 Java | 📅 2016-11-07 - Vert.x 3 Solr service with event bus proxying.

## Service Factory

* [Service Factory](https://github.com/vert-x3/vertx-service-factory) ⭐ 24 | 🐛 0 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x Service Factory.
* [Maven Service Factory](https://github.com/vert-x3/vertx-maven-service-factory) ⭐ 14 | 🐛 5 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Maven Vert.x Service Factory.
* [HTTP Service Factory](https://github.com/vert-x3/vertx-http-service-factory) ⭐ 9 | 🐛 1 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x HTTP Service Factory.
* [Node.js Service Factory](https://github.com/mellster2012/vertx-nodejs-service-factory) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2015-12-17 - Vert.x Node.js Service Factory.
* [Eclipse SISU Service Factories](https://github.com/cstamas/vertx-sisu) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2017-03-30 - Vert.x integration with [Eclipse SISU](https://www.eclipse.org/sisu/) DI container offering alternatives for `vertx-service-factory` and `vertx-maven-service-factory`.

## Config

* [Vert.x Boot](https://github.com/jponge/vertx-boot) ⭐ 45 | 🐛 0 | 🌐 Java | 📅 2020-12-18 - Deploying verticles from a HOCON configuration.
* [Vert.x Config AWS SSM Store](https://github.com/Finovertech/vertx-config-aws-ssm) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2018-10-08 - A [config store](http://vertx.io/docs/vertx-config/java/) implementation for retrieving configuration values from the [AWS EC2 SSM Parameter Store](https://aws.amazon.com/ec2/systems-manager/parameter-store/).

## Dependency Injection

* [QBit](https://github.com/advantageous/qbit) ⭐ 707 | 🐛 61 | 🌐 Java | 📅 2018-01-18 - QBit works with Spring DI and Spring Boot (and of course Vert.x). Allows you to use QBit, Vert.x, Spring DI and Spring Boot in the same application.
* [Vert.x Guice](https://github.com/englishtown/vertx-guice) ⭐ 63 | 🐛 3 | 🌐 Java | 📅 2019-11-02 - Vert.x verticle factory for Guice dependency injection.
* [Spring Vert.x Extension](https://github.com/amoAHCP/spring-vertx-ext) ⭐ 50 | 🐛 1 | 🌐 Java | 📅 2019-04-03 - Vert.x verticle factory for Spring DI injection.
* [Vert.x HK2](https://github.com/englishtown/vertx-hk2) ⭐ 32 | 🐛 2 | 🌐 Java | 📅 2021-10-28 - Vert.x verticle factory for HK2 dependency injection.
* [Vert.x Beans](https://github.com/rworsnop/vertx-beans) ⭐ 26 | 🐛 3 | 🌐 Java | 📅 2026-01-26 - Inject Vert.x objects as beans into your Spring application.
* [Vert.x Spring Verticle Factory](https://github.com/juanavelez/vertx-spring-verticle-factory) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2025-03-23 - A Vert.x Verticle Factory that makes use of Spring to obtain and configure Verticles.
* [Vert.x Eclipse SISU](https://github.com/cstamas/vertx-sisu) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2017-03-30 - Vert.x integration with [Eclipse SISU](https://www.eclipse.org/sisu/) DI container.
* [Glue](https://github.com/vinscom/glue) ⭐ 1 | 🐛 4 | 🌐 Java | 📅 2022-01-04 - Proven and opinionated programming, and configuration model for Java and Vert.x based applications. Inspired from ATG Nucleus, provides powerful layer base configuration management using simple properties file.

## Testing

* [Vert.x JUnit5](https://github.com/vert-x3/vertx-junit5) ⭐ 43 | 🐛 11 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Async unit testing for Vert.x with junit5.
* [Vert.x Unit](https://github.com/vert-x3/vertx-unit) ⭐ 33 | 🐛 9 | 🌐 JavaScript | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Async polyglot unit testing for Vert.x.
* [Vert.x WireMongo](https://github.com/noenv/vertx-wiremongo) ⭐ 14 | 🐛 0 | 🌐 Java | 📅 2026-08-07 - Lightweight MongoDB mocking for Vert.x

## Development Tools

* [openapi-generator](https://github.com/OpenAPITools/openapi-generator) ⭐ 26,679 | 🐛 5,713 | 🌐 Java | 📅 2026-08-18 - OpenAPI Generator allows generation of API client libraries (SDK generation), server stubs, documentation and configuration automatically given an OpenAPI Spec (v2, v3).
* [Vert.x Hot](https://github.com/dazraf/vertx-hot) ⭐ 49 | 🐛 10 | 🌐 Java | 📅 2016-02-24 - A Maven plugin for the hot-deploy of Maven Vert.x projects.
* [Vert.x shell](https://github.com/vert-x3/vertx-shell) ⭐ 39 | 🐛 10 | 🌐 Java | 📅 2026-08-10  <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Allows for interaction with Vert.x from the command line.
* [Vert.x health check](https://github.com/vert-x3/vertx-health-check) ⭐ 15 | 🐛 9 | 🌐 Java | 📅 2026-08-07 - Allows for remote health checking in Vert.x projects.
* [Vert.x LiveReload](https://github.com/ybonnel/vertx-livereload) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2018-03-20 - A simple livereload server for Vert.x applications.
* [Vert.x for Visual Studio Code](https://github.com/pmlopes/VertxSnippet) ⭐ 1 | 🐛 0 | 📅 2019-11-29 - A Visual Studio Code (polyglot) plugin for Vert.x. Also available from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=pmlopes.vertxsnippet).
* [Vert.x Starter](http://www.jetdrone.xyz/vertx-starter/) - A browser-based project starter and project templates for Vert.x applications.

## Miscellaneous

* [Simple File Server](https://github.com/pitchpoint-solutions/sfs) ⭐ 88 | 🐛 8 | 🌐 Java | 📅 2022-10-04 - An OpenStack Swift compatible distributed object storage server that can serve and securely store billions of large and small files using minimal resources implemented using Vert.x.
* [Vert.x Child Process](https://github.com/vietj/vertx-childprocess) ⭐ 57 | 🐛 5 | 🌐 Java | 📅 2025-06-05 - Spawn child process from Vert.x.
* [Vert.x Boot](https://github.com/jponge/vertx-boot) ⭐ 45 | 🐛 0 | 🌐 Java | 📅 2020-12-18 - Deploying verticles from a HOCON configuration.
* [GDH](https://github.com/maxamel/GDH) ⭐ 34 | 🐛 5 | 🌐 Java | 📅 2019-10-25 - Generalized Diffie-Hellman key exchange Java library built on top of Vert.x.
* [vertx-redisques](https://github.com/swisspush/vertx-redisques) ⭐ 14 | 🐛 21 | 🌐 Java | 📅 2026-08-17 - A highly scalable redis-persistent queuing system for Vert.x.
* [vertx-values](https://github.com/imrafaelmerino/vertx-values) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2024-11-23 - Send immutable and persistent JSON from [json-values](https://github.com/imrafaelmerino/json-values) ⭐ 4 | 🐛 2 | 🌐 Java | 📅 2026-04-01 across the event bus.

## Distribution

* [Vert.x Stack](https://github.com/vert-x3/vertx-stack) ⭐ 123 | 🐛 8 | 🌐 Java | 📅 2026-08-07 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - Vert.x + the endorsed modules.

## Examples

* [Knative](https://github.com/knative/docs/tree/main/code-samples/community/serving/helloworld-vertx) ⭐ 5,079 | 🐛 40 | 🌐 HTML | 📅 2026-08-17 - An example application on how to use [Reactive Extensions Vert.x](https://github.com/vert-x3/vertx-rx) ⭐ 155 | 🐛 5 | 🌐 Java | 📅 2026-08-07 with [Knative](https://github.com/knative).
* [Vert.x examples](https://github.com/vert-x3/vertx-examples) ⭐ 3,581 | 🐛 46 | 🌐 Java | 📅 2026-05-26 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x examples including web examples, how to use the official database clients, etc.
* [Vert.x blueprint - Microservice application](https://github.com/sczyh30/vertx-blueprint-microservice) ⭐ 788 | 🐛 25 | 🌐 Java | 📅 2018-12-13 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x blueprint showing how to build a complex microservice application.
* [Vert.x blueprint - TODO backend](https://github.com/sczyh30/vertx-blueprint-todo-backend) ⭐ 185 | 🐛 1 | 🌐 Java | 📅 2020-05-23 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x blueprint showing how to build a backend for a TODO application.
* [Vert.x blueprint - Job Queue](https://github.com/sczyh30/vertx-blueprint-job-queue) ⭐ 146 | 🐛 4 | 🌐 Java | 📅 2018-07-10 <img src="vertx-favicon.svg" alt="(stack)" title="Vert.x Stack" height="16px"> - The official Vert.x blueprint showing how to build a distributed job processing application.
* [Vert.x feeds](https://github.com/aesteve/vertx-feeds) ⭐ 132 | 🐛 1 | 🌐 Java | 📅 2020-05-24 - Example of an RSS aggregator built using Vert.x, Gradle, MongoDB, Redis, Handlebars templates, AngularJS, the event bus and SockJS.
* [Crabzilla](https://github.com/crabzilla/crabzilla) ⭐ 75 | 🐛 1 | 🌐 Kotlin | 📅 2026-01-26 - Yet another Event Sourcing experiment. A project exploring Vert.x to develop Event Sourcing / CQRS applications.
* [Vert.x Music Store](https://github.com/tsegismont/vertx-musicstore) ⭐ 69 | 🐛 0 | 🌐 Java | 📅 2026-07-23 - An example application on how to build Vert.x applications with RxJava.
* [Example using event bus and service proxies to connect vertx and node](https://github.com/advantageous/vertx-node-ec2-eventbus-example) ⭐ 46 | 🐛 2 | 🌐 Java | 📅 2016-03-14 - Step by step example with wiki description showing how to connect Vert.x and Node using event bus and service proxies.
* [Vert.x PostgreSQL Starter](https://github.com/BillyYccc/vertx-postgresql-starter) ⭐ 36 | 🐛 1 | 🌐 Java | 📅 2021-11-07 - A starter to build a monolithic CRUD RESTful Web Service with Vert.x stack and PostgreSQL.
* [Vert.x Gentics Mesh Example](https://github.com/gentics/mesh-vertx-example) ⭐ 16 | 🐛 3 | 🌐 HTML | 📅 2025-10-22 - Example on how to build a template-based web server with Gentics Mesh and handlebars.
* [Vert.x Gradle Starter](https://github.com/yyunikov/vertx-gradle-starter) ⭐ 10 | 🐛 0 | 🌐 Java | 📅 2017-03-23 - Java 8 starter application with example of using Vert.x with Gradle build system, profiles configuration and SLF4J.
* [Kotlin Todo-Backend implementation](https://github.com/aesteve/vertx-kotlin-todomvc) ⭐ 7 | 🐛 1 | 🌐 Kotlin | 📅 2016-05-23 - Kotlin implementation of the Todo MVC backend.
* [HTTP/2 showcase](https://github.com/aesteve/http2-showcase) ⭐ 7 | 🐛 3 | 🌐 Java | 📅 2017-04-27 - A simple demo, showing how HTTP/2 can drastically improve user experience when a huge latency is involved.
* [Vert.x Markdown service](https://github.com/aesteve/vertx-markdown-service) ⭐ 6 | 🐛 1 | 🌐 Java | 📅 2015-11-15 - Example on how to use [service-proxy](https://github.com/vert-x3/vertx-service-proxy) ⭐ 70 | 🐛 18 | 🌐 Java | 📅 2026-08-18 with Gradle.
* [Vert.x Todo-Backend implementation](https://github.com/aesteve/todo-backend-vertx) ⭐ 5 | 🐛 0 | 🌐 Java | 📅 2016-04-24 - Pure Java 8 implementation of the Todo MVC backend. Uses a Vert.x LocalMap for storage.
* [Cloud Foundry](https://github.com/amdelamar/vertx-cloudfoundry) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2017-12-20 - An example Vert.x for deploying to a [Cloud Foundry](https://www.cloudfoundry.org/) service provider.
* [Starter Single Verticle API](https://github.com/jgarciasm/ssv-api) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2020-09-17 - REST API Starter and Project Template ready to deploy with lots of plumbing code, examples, and documentation to quickly develope an API with almost no knowledge of vert.x and without any waste of time.
* [AI model output API based on PMML with Vert.x](https://github.com/immusen/vertx-pmml) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2022-05-05 - High performance PMML evaluator API based on Vert.x. Supports dynamic routing configuration for multiple PMML models via JSON.
* [Scala Todo-Backend implementation](https://github.com/aesteve/vertx-scala-todomvc) ⭐ 1 | 🐛 0 | 🌐 Scala | 📅 2016-10-10 - Scala implementation of the Todo MVC backend.
* [Grooveex Todo-Backend implementation](https://github.com/aesteve/todo-backend-grooveex) ⭐ 1 | 🐛 0 | 🌐 Groovy | 📅 2016-05-23 - Todo MVC backend implementation with Vert.x + Groovy + some syntactic sugar + DSL routing facilities.

## Deployment

* [Vert.x Deploy Application](https://github.com/msoute/vertx-deploy-tools) ⚠️ Archived - (Seamless) deploy to AWS based Vert.x application clusters.

## Utilities

* [Vert.x Dataloader](https://github.com/engagingspaces/vertx-dataloader) ⭐ 73 | 🐛 1 | 🌐 Java | 📅 2017-08-06 - Java port of Facebook Dataloader for Vert.x. Efficient batching and caching for your data layer.
* [Vert.x Cron](https://github.com/diabolicallabs/vertx-cron) ⭐ 66 | 🐛 1 | 🌐 Java | 📅 2026-06-02 - Schedule events with cron specifications. Has event bus and Observable versions.
* [Contextual logging](https://github.com/reactiverse/reactiverse-contextual-logging) ⭐ 41 | 🐛 1 | 🌐 HTML | 📅 2026-08-10 - Mapped Diagnostic Context (MDC) that works with the Vert.x event-loop model.
* [Vert.x Web Accesslog](https://github.com/romanpierson/vertx-web-accesslog) ⭐ 30 | 🐛 3 | 🌐 Java | 📅 2025-05-15 - Just a simple handler to be used in Vert.x Web to generate access logs.
* [Chime](https://github.com/LisiLisenok/Chime) ⭐ 29 | 🐛 3 | 🌐 Ceylon | 📅 2017-11-07 - Time scheduler working on Vert.x event bus allowing for scheduling with *cron-style* and *interval* timers.
* [Vert.x CronUtils](https://github.com/NoEnv/vertx-cronutils) ⭐ 26 | 🐛 0 | 🌐 Java | 📅 2026-08-07 - An abstraction of cron-utils for the vertx scheduler. Unix, Cron4j and Quartz style expressions are supported.
* [Vert.x GraphQL Utils](http://github.com/tibor-kocsis/vertx-graphql-utils) ⭐ 25 | 🐛 0 | 🌐 Java | 📅 2018-05-30 - A route handler and Vert.x compatible interfaces to handle GraphQL queries in Vert.x and Vert.x Web.
* [Vert.x Scheduler](https://github.com/zero88/vertx-scheduler) ⭐ 14 | 🐛 24 | 🌐 Java | 📅 2026-08-14 - A lightweight plugable scheduler based on plain Vert.x core without any external libs for scheduling with *cron-style* and *interval* timers with a detail *monitor* on both sync and async task.
* [Vert.x Async](https://github.com/gchauvet/vertx-async) ⭐ 12 | 🐛 3 | 🌐 Java | 📅 2022-03-12 - Portage of caolan/async nodejs module to Vert.x framework that provides helpers methods for common async patterns.
* [Vert.x JsonPath](https://github.com/NoEnv/vertx-jsonpath) ⭐ 12 | 🐛 2 | 🌐 Java | 📅 2026-08-07 - A very basic implementation of JsonPath using Vert.x’s JsonObject and JsonArray, mimicking their getX, containsKey, put and remove methods.
* [Vert.x Dependent Verticle Deployer](https://github.com/juanavelez/vertx-dependent-verticle-deployer) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2019-01-11 - A Vert.x Verticle intended to deploy verticles and their dependent verticles.
* [Vert.x JOLT](https://github.com/lusoalex/vertx-jolt) ⭐ 4 | 🐛 9 | 🌐 Java | 📅 2026-01-15 - JSON to JSON transformation tool based on the original bazaarvoice JOLT project. Helpful to transform different json structure into an expected json format.
* [Vert.x POJO config](https://github.com/aesteve/vertx-pojo-config) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2016-05-01 - Allows for mapping between standard JSON configuration and a (type-safe) configuration Java bean. Also allows the configuration bean to be validated through JSR 303.
* [Vert.x Util](https://github.com/juanavelez/vertx-util) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2018-05-13 - A collection of Vert.x utility methods.
* [Nannoq-Tools](https://noriginmedia.github.io/nannoq-tools/) - Nannoq-Tools is a toolkit for constructing robust, scalable and distributed applications leveraging Vert.x including modules for authentication, cluster management, Firebase Cloud Messaging, DynamoDB, fully generic queries, REST, and more.

## Presentations

* [Vert.x Youtube channel](https://www.youtube.com/channel/UCGN6L3tRhs92Uer3c6VxOSA)

## Community

* [Wiki](https://github.com/vert-x3/wiki/wiki) ⭐ 191 | 🐛 2 | 📅 2015-03-16 - Contains useful information about Vert.x.
* [Issues](https://github.com/vert-x3/issues/issues) ⭐ 35 | 🐛 115 | 📅 2016-06-21 - Vert.x core issue tracker.
* [User Group](https://groups.google.com/forum/?fromgroups#!forum/vertx) - Discuss all user issues related to *using* Vert.x.
* [Developer Group](https://groups.google.com/forum/?fromgroups#!forum/vertx-dev) - A group for Vert.x core *developers* and *contributors*.
* [Discord Server](https://discord.gg/KzEMwP2) - Chat about any Vert.x-related topic.
* [Blog](http://vertx.io/blog/) - The official Vert.x blog containing many tutorials and other information.

## Articles

* [Embracing Reactive Applications on JVM: a Deep Dive into Modern I/O Models and Vert.x](https://www.infoq.com/articles/reactive-java-vertx-deep-dive/)
* [Going reactive with Eclipse Vert.x and RX Java](https://blogs.oracle.com/javamagazine/post/going-reactive-with-eclipse-vertx-and-rxjava)
* [Vert.x 3.3.0 Features Enhanced Networking Microservices, Testing and More](https://www.infoq.com/news/2016/06/Vert.x-3.3.0-release-features)
* [Interview with Tim Fox About Vert.x 3, the Original Reactive, Microservice Toolkit for the JVM](http://www.infoq.com/articles/vertx-3-tim-fox)

## Tutorials

* [Introduction to Vert.x](https://vertx.io/get-started/)

## Front-End

* [VertxUI](https://github.com/nielsbaloe/vertxui) ⚠️ Archived - A pure Java front-end toolkit with descriptive fluent views-on-models, POJO traffic, JUnit testing on the virtual DOM or mixed-language on a real DOM, and more.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
