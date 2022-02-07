# data-intensive-app
Repository to hold a study with implementation related to data intensive apps.

# Overview
The data-intensive application I am refering to are those applications where there are near or more than 1 TB of data stored, and it is necessary to perform fast queries to reply to the user, less than 500ms.

This kind of challenge is growing with some specific types of business working online, such as social media, online stores, online banking, etc. These type of business have to usually store a lots os user information, either for fraud analisys, data analysis, or to allow the user to navigate through anytime on the history, such as old social media posts, all banking statements, previous purchages online on the online store.

# The implementation and this repository
The idea of this repository is to gather and apply some best practices related to data-intensive applications, addressing some common problems when dealing with data-intensive apps such as `caching`, `pagination`, `indexes`, `concurrency`, etc.

# Out of scope
The data-intensive app use case that will be developed on this repository will only consider some software layers to be able to contain more reproducable scenarios. So layers such as `infrastructure`, `cloud`, specific `cloud provider technology` will not be considered. 

Also some implementation not related with the intensive-data goal will not be considered, such as `authentication & authorization`, `payment methods`, `UX`, `well designed front end`.


# Application Use Cases
TBD

# Architecture
- Domain Driven Design
- Clean Architecture

# Stack
Backend
- App
    - NET 6
    - C# 10
    - Dapper
    - gRPC & REST
- Storage
   - redis
   - mySQL - TBD
   - MongoDB - TBD
- Performan Tests
   - Locust


# References
- [Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/) (2017) written by `Martin Kleppmann`
- [Clean Architecture: A Craftsman's Guide to Software Structure and Design](https://pearson.instructure.com/eportfolios/71582) (2017) by `Robert C. Martin` (Uncle Bob)
- [Clean Architecture with .NET Core & React+Redux](https://github.com/ivanpaulovich/clean-architecture-manga) (Open Source Software) by `Ivan Paulovich` and contributors