# NoSQL

<!-- toc -->

* [Visão Geral](#visão-geral)
* [Comparação](#comparação)
* [Chave e Valor](#chave-e-valor)
  * [LevelDB](#leveldb)
  * [Memcached](#memcached)
  * [Redis](#redis)
* [Grafo](#grafo)
* [Neo4j](#neo4j)
  * [Caso de Uso](#caso-de-uso)
* [Orientado a Documento](#orientado-a-documento)
  * [CouchDB](#couchdb)
  * [MongoDB](#mongodb)
    * [Aprendizado](#aprendizado)
    * [Schema Design](#schema-design)
    * [Dicas](#dicas)
    * [Ferramentas](#ferramentas)
    * [Palestras](#palestras)

<!-- toc stop -->


## Visão Geral

* [Bancos de dados não relacionais e o movimento NoSQL | Caelum](http://blog.caelum.com.br/bancos-de-dados-nao-relacionais-e-o-movimento-nosql/)

* [Recursos para aprender noSQL | iMasters](http://imasters.com.br/banco-de-dados/recursos-para-aprender-nosql/)

* [Devo usar NoSQL e MongoDB? | Leroy Merlin Techblog](http://tech.leroymerlin.com.br/devemos-usar-nosql-e-mongodb)

--

* [[YouTube] Configuring an LDAP Server](https://www.youtube.com/watch?v=KQdQ3ITG_Vg)

--

* [ArangoDB](http://www.arangodb.org/) - An open-source database with a flexible data model for documents, graphs, and key-values. Build high performance applications using a convenient sql-like query language or JavaScript/Ruby extensions

  * [ArangoDB Foxx](http://www.arangodb.org/foxx) - Lean Application Server for Single Page Applications

--

* [FoundationDB](https://foundationdb.com/)

  * [[GitHub] OptimalBits / fowl](https://github.com/OptimalBits/fowl) - A NodeJS Document Model and Query Layer for FoundationDB


## Comparação

* [Cassandra  vs MongoDB vs CouchDB vs Redis vs Riak vs HBase vs Couchbase vs Neo4j vs Hypertable vs ElasticSearch vs Accumulo vs VoltDB vs Scalaris  comparison](http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis)


## Chave e Valor

### LevelDB

* [LevelDB](https://code.google.com/p/leveldb/) - is a fast key-value storage library written at Google that provides an ordered mapping from string keys to string values.

* [Brincando com LevelDB | Underground WebDev](http://udgwebdev.com/brincando-com-leveldb/)


### Memcached

* [Memcached](http://memcached.org/) - Free & open source, high-performance, distributed memory object caching system.

* [Aplicando o memcached para aumentar o desempenho do site | iMasters](http://imasters.com.br/artigo/18042/software-livre/aplicando-o-memcached-para-aumentar-o-desempenho-do-site/)

* [Otimizando consultas MySQL com o Memcached | Thiago Belem](http://blog.thiagobelem.net/otimizando-consultas-mysql-com-o-memcached/)

* [MyBatis Memcached | Reference Documentation](http://www.mybatis.org/caches/memcached/)


### Redis

* [Redis.io](http://redis.io/)

* [Try Redis Online](http://try.redis.io/)

* [Redis Clients](http://redis.io/clients)

* [Redis Desktop Manager](http://redisdesktop.com/) - Open source GUI management tool for Redis

* [The Little Redis Book](http://openmymind.net/2012/1/23/The-Little-Redis-Book/)

* [Redis Weekly](https://redsmin.com/redisweekly/) - A free, once–weekly e-mail round-up of Redis news, articles, tools and libraries

* [Kicking ass with redis | SlideShare](http://www.slideshare.net/dvirsky/kicking-ass-with-redis)

* [Redis 101 | SlideShare](http://www.slideshare.net/phpguru/redis-101-10043219)

* [How to Install and Use Redis | DigitalOcean](https://www.digitalocean.com/community/articles/how-to-install-and-use-redis)

--

* [[GitHub] luin / medis](https://github.com/luin/medis) - is a beautiful, easy-to-use Mac database management application for Redis


##### Caso de Uso

* [Usando o banco de dados NoSQL Redis para otimizar sistemas de alta escalabilidade | boo-box](http://blog.boo-box.com/br/2010/usando-banco-de-dados-nosql-redis/)


##### Desenvolvimento


###### Java

* [Spring Data - Redis | SpringSource.org](http://www.springsource.org/spring-data/redis)

* [Using Redis with Spring | Architects Zone](http://architects.dzone.com/articles/using-redis-spring)

* [Desenvolvimento em Java 2.0: Redis para o mundo real | IBM developerWorks](http://www.ibm.com/developerworks/br/library/j-javadev2-22/)

* [[GitHub] xetorthio / johm](https://github.com/xetorthio/johm) - is a Object-hash mapping library for Java for storing objects in Redis

* [[GitHub] xetorthio / jedis](https://github.com/xetorthio/jedis) - A blazingly small and sane redis java client


###### doNet

* [Getting started with Redis in ASP.NET under Windows](http://maxivak.com/getting-started-with-redis-and-asp-net-mvc-under-windows/)

* [Using Redis with ASP.NET Web API | piotrwalat.net](http://www.piotrwalat.net/using-redis-with-asp-net-web-api/)

* [Using the ServiceStack.Redis Client | Michael Sarchet](http://michaelsarchet.com/using-the-servicestack-redis-client/)


###### Node.js

* [Using Redis for Caching in Node.js](http://blog.stevenlu.com/2013/03/07/using-redis-for-caching-in-nodejs/)

* [[GitHub] maritz / nohm](https://github.com/maritz/nohm) - node.js implementation of a redis object relations mapper (orm). High speed queries with this ODM for Redis

* [[GitHub] LearnBoost / kue](https://github.com/learnboost/kue) - Kue is a priority job queue backed by redis, built for node.js.


###### Python

* [[GitHub] vivekn / redis-simple-cache](https://github.com/vivekn/redis-simple-cache/) - Simple redis based cache for storing json encoded strings or html



## Grafo

* [Graph Databases, published by O'Reilly Media](http://graphdatabases.com/)

* [GraphBD Series: Modelagem de grafos | iMasters](http://imasters.com.br/banco-de-dados/graphbd-series-modelagem-de-grafos/)


## Neo4j

* [Neo4j](http://www.neo4j.org/) | [Aprender](http://www.neo4j.org/learn) | [Desenvolver](http://www.neo4j.org/develop)

* [[GitHub] neo4j / neo4j](https://github.com/neo4j/neo4j)

* [Spring Data Neo4j](http://www.springsource.org/spring-data/neo4j)


### Caso de Uso

* [GitMoon](http://www.gitmoon.com/) | [[GitHub] yaronn / gitmoon](https://github.com/yaronn/gitmoon) - Social analytics for node.js open source developers



## Orientado a Documento

* [11 OPEN NoSQL Document-Oriented Databases](http://architects.dzone.com/articles/11-open-nosql-document)

* [[GitHub] foursquare/fongo](https://github.com/foursquare/fongo) - faked out in-memory mongo for java


### CouchDB

* [CouchDB | Apache](https://couchdb.apache.org/)

  * [CouchDB: The Definitive Guide](http://guide.couchdb.org/draft/) - draft

* [CouchBase](http://www.couchbase.com/)

  * [Couchbase Lite | CouchBase](http://www.couchbase.com/communities/couchbase-lite) - The NoSQL Mobile Database

    * [Couchbase ‘JSON Anywhere’ Mobile Strategy - First NoSQL database for mobile | CouchBase](http://blog.couchbase.com/couchbase-json-anywhere-mobile-strategy-first-nosql-database-mobile)

    * [Couchbase Announces First NoSQL Database For Mobile Devices | Tools Journal](http://www.toolsjournal.com/mobile-articles/item/2242-couchbase-announces-first-nosql-database-for-mobile-devices)

* [[GitHub] damienklinnert / couchviews](https://github.com/damienklinnert/couchviews) - Store and load CouchDB views to / from your file system for easier setup of new databases


### MongoDB

* [MongoDB](http://www.mongodb.org/)

> **Sobre**
>
> Banco de Dados NoSQL (não relacional, sem esquema de dados fixo).
>
> Mantido pela empresa [10gen](http://www.10gen.com/), a qual fornece treinamentos e suporte pago ao MongoDB.
>
> * A empresa 10gen mudou de nome para MongoDB Inc. [MongoDB.com](https://www.mongodb.com/)
>
> [10gen Announces Company Name Change to MongoDB, Inc. | MongoDB](https://www.mongodb.com/press/10gen-announces-company-name-change-mongodb-inc)
>


#### Aprendizado

* [The MongoDB Manual | MongoDB](http://docs.mongodb.org/manual/)

* [SQL to Mongo Mapping Chart | MongoDB](http://docs.mongodb.org/manual/reference/sql-comparison/)

* [MongoDB - material de aprendizado inicial](http://mongly.com/)

* [The Little MongoDB Book](http://openmymind.net/2011/3/28/The-Little-MongoDB-Book/)

* [MongoDB in Action (free PDF)](http://effectif.com/mongodb/mongodb-in-action-free-pdf)

* [LearnMongo.com](http://learnmongo.com/)

* [Building scalable applications with mongoDB](http://lanyrd.com/2012/jazoon/swkpc/)

--

* [MongoDB Cheat Sheet - Quick Reference | MongoDB Spain](http://www.mongodbspain.com/2014/03/23/mongodb-cheat-sheet-quick-reference/)

--

* Getting Started with MongoDB | Nettuts+ : [Part 1](http://net.tutsplus.com/tutorials/databases/getting-started-with-mongodb/) | [Part 2](http://net.tutsplus.com/tutorials/databases/getting-started-with-mongodb-part-2/)

* [[YouTuve] Hangout - Iniciando com MongoDB | DevCast](https://www.youtube.com/watch?v=Ff4_DNKKPeo)

* [An introduction to MongoDB | IBM developerWorks](http://www.ibm.com/developerworks/offers/lp/demos/summary/j-jmongodb.html)


#### Schema Design

* [Data Model | MongoDB Docs](http://docs.mongodb.org/manual/data-modeling/)

* [Schema Desgin | MongoDB](http://www.mongodb.com/presentations/schema-design-6) - MongoDB’s basic unit of storage is a document. Documents can represent rich, schema-free data structures, meaning that we have several viable alternatives to the normalized, relational model. In this talk, we’ll discuss the tradeoff of various data modeling strategies in MongoDB using a library as a sample application. You will learn how to work with documents, evolve your schema, and common schema design patterns.

* [[Speaker Deck] MongoDB DC 2012: Schema Design by Example](https://speakerdeck.com/mongodb/mongodb-dc-2012-schema-design-by-example)

* [MongoDB Schema Design: Data as Documents | Effectif Development](http://effectif.com/mongodb/mongodb-schema-design)

* [Um pouco de schema design no MongoDB | Christiano Anderson](http://christiano.me/2013/11/30/um-pouco-de-schema-design-mongodb/)

* Nomadev : MongoDB - Como mudar seu jeito relacional de pensar

  * [Parte 1](http://nomadev.com.br/mongodb-como-mudar-seu-jeito-relacional-de-pensar/)

  * [Parte 2](http://nomadev.com.br/mongodb-como-mudar-seu-jeito-relacional-de-pensar-parte-2/)

* [[SlideShare] MongoDB Schema Design - Latinoware 2014](http://pt.slideshare.net/canderson/mongodb-schemadesign)

--

* 6 Rules of Thumb for MongoDB Schema Design | MongoDB

  * [Part 1 : One-to-N relationships in MongoDB](http://blog.mongodb.org/post/87200945828/6-rules-of-thumb-for-mongodb-schema-design-part-1)

  * [Part 2 : Two-way referencing and denormalization](http://blog.mongodb.org/post/87892923503/6-rules-of-thumb-for-mongodb-schema-design-part-2)

  * [Part 3 : Your guide through the rainbow](http://blog.mongodb.org/post/88473035333/6-rules-of-thumb-for-mongodb-schema-design-part-3)

--

* [Thinking in Documents (recorded webinar) | MongoDB](http://www.mongodb.com/presentations/webinar-back-basics-1-thinking-documents)

* [Schema Design for Time-Series Data (recorded webinar) | MongoDB](http://www.mongodb.com/presentations/webinar-time-series-data-mongodb)

--

* [MongoDB schema design pitfalls | Server Density Blog](https://blog.serverdensity.com/mongodb-schema-design-pitfalls/)


#### Dicas

> **Recomendação**
>
> Indicado para uma configuração inicial e básica, observar o uso de replica set do MongoDB
>

* [MongoDB Gotchas & How To Avoid Them](http://rsmith.co/2012/11/05/mongodb-gotchas-and-how-to-avoid-them/)

* [Top 5 syntactic weirdnesses to be aware of in MongoDB | Slava Kim](http://devblog.me/wtf-mongo)

* [[reddit] Find MongoDB Articles and News on the MongoDB Subreddit](http://www.reddit.com/r/mongodb/)

--

* [MongoDB Quick Start - Replica Sets and Sharding](http://alexyu.se/content/2012/04/mongodb-quick-start-replica-sets-and-sharding)

* [MongoDB scalability and high availability with Replica-Set](http://vparihar01.github.io/talks/2013/10/27/MongoDB-Scalability-and-High-Availabiltity-with-Replica-Sets/)

* [[SlideShare] Optimizing MongoDB: Lessons Learned at Localytics](http://www.slideshare.net/andrew311/optimizing-mongodb-lessons-learned-at-localytics)

* [The genius and folly of MongoDB - Bryce Nyeggen's Blog | Bryce Nyeggen](http://nyeggen.com/blog/2013/10/18/the-genius-and-folly-of-mongodb/)

* [How to Use MongoDB as a Pure In-memory DB (Redis Style) | Javalobby](http://java.dzone.com/articles/how-use-mongodb-pure-memory-db)

* [Data Science on MongoDB At Last!](http://blog.mongodb.org/post/35204064565/data-science-on-mongodb-at-last)

* [Realtime Analytics at Buffer with MongoDB](http://blog.tommoor.com/post/24059620728/realtime-analytics-at-buffer-with-mongodb)

* [Rapid Realtime App Development with Node.JS & MongoDB | MongoDB, Inc](http://www.mongodb.com/presentations/rapid-realtime-app-development-nodejs-mongodb)

* [[SlideShare] Building a Directed Graph with MongoDB](http://www.slideshare.net/fehguy/building-a-directed-graph-with-mongodb)

* [[SlideShare] MongoDB: Queries and Aggregation Framework with NBA Game Data](http://www.slideshare.net/vkarpov15/mongodb-queries-and-aggregation-framework-with-nba-game-data)

--

* [A quick start with MongoDB Geospatial Queries](http://www.siletto.it/blog/alessandro/2013/03/19/quick-start-mongodb-geospatial-queries)

* [[SlideShare] Geolocation in mongodb](http://www.slideshare.net/mongodb/geolocation-in-mongodb)

--

* [Map reduce and MongoDB | Boxed Ice Blog](http://blog.serverdensity.com/map-reduce-and-mongodb/)

* [Map Reduce | MongoDB Docs](http://docs.mongodb.org/manual/core/map-reduce/)

--

* [[SlideShare] Introduction to MongoDB and Hadoop](http://www.slideshare.net/spf13/introduction-to-mongodb-and-hadoop) - An Introduction to MongoDB + an Introduction to MongoDB + Hadoop. This presentation was given at the CT Java Users Group in March 2013.

* [Webinar: What's New with MongoDB Hadoop Integration | MongoDB](http://www.mongodb.com/presentations/webinar-whats-new-mongodb-hadoop-integration)

* [Partner Webinar: The Scaling Checklist for MongoDB - 100GB and beyond | MongoDB](http://www.mongodb.com/presentations/partner-webinar-scaling-checklist-mongodb-100gb-and-beyond)

* [Converting your data from MySQL to MongoDB | You are IT!](http://tamaspiros.co.uk/2013/09/03/converting-your-data-from-mysql-to-mongodb/)

* [Scaling MongoDB at Mailbox | Dropbox Tech Blog](https://tech.dropbox.com/2013/09/scaling-mongodb-at-mailbox/)

--

* [Intro to MongoDB on Node.js | OpenShift by Red Hat](https://www.openshift.com/blogs/intro-to-mongodb-on-nodejs)

* [How to use Go language and MongoDB | g33k talk](http://g33ktalk.com/10gen-how-we-use-go-and-mongodb-by-sam-helman/)

* [Using MongoDB as your primary Django database](http://staltz.github.io/djangoconfi-mongoengine/) - By Andre Medeiros at DjangoCon Finland 2013

--

* [7 Simple Speed Solutions for MongoDB | SitePoint](http://www.sitepoint.com/7-simple-speed-solutions-mongodb/) - 2016/02/17

* [10 tips to improve your MongoDB security | MongoDirector](http://blog.mongodirector.com/10-tips-to-improve-your-mongodb-security/)

--

* [How to start MongoDB automatically when starting your Mac OS X | alicoding](https://alicoding.com/how-to-start-mongodb-automatically-when-starting-your-mac-os-x/)

--

* [Raspberry Pi MongoDB Installation - The working guide! | Raspberry Pi | 512MB of Awesome](http://c-mobberley.com/wordpress/index.php/2013/10/14/raspberry-pi-mongodb-installation-the-working-guide/)

* [[GitHub] olebedev / cdn](https://github.com/olebedev/cdn) - Content Delivery Network over MongoDb GridFs

* [Log 4 Mongo](http://log4mongo.org/)

  * [Usando MongoDB para armazenar log de aplicações | iMasters](http://imasters.com.br/banco-de-dados/mongodb/usando-mongodb-para-armazenar-log-de-aplicacoes/)

* [Forward](http://getfwd.com/) - The open source platform for custom e-commerce — with MongoDB


#### Ferramentas

* [Admin UIs](http://docs.mongodb.org/ecosystem/tools/administration-interfaces/)

* [Genghis](http://genghisapp.com/) - The single-file MongoDB admin app

  * [[GitHub] bobthecow / genghis](https://github.com/bobthecow/genghis)

* [Robomongo](http://www.robomongo.org/) - Shell-centric cross-platform MongoDB management tool

  * [[GitHub] paralect / robomongo](https://github.com/paralect/robomongo)

* [[GitHub] officert / mongotron](https://github.com/officert/mongotron) - Cross platform Mongo DB management


#### Palestras

* [Métricas na web em tempo real com MongoDB | InfoQ Br](http://www.infoq.com/br/presentations/web-analytics-MongoDB) - Uma solução simples utilizando MongoDB para tracking de visitas em páginas web em tempo real, mostrando também como com o MongoDB isso pode ser expandido para o rastreamento de outras métricas personalizadas, quando é necessário ou interessante exibi-las em tempo real.

* [Um estudo de caso do MongoDB | InfoQ Br](http://www.infoq.com/br/presentations/mongodb-no-ingressecom) - Essa palestra apresenta um caso de uso do MongoDB na empresa [ingresse.com](http://ingresse.com), uma introdução rápida ao MongoDB e dificuldades na sua adoção.
