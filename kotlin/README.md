# Automation Arsenal - Kotlin Libraries

---

## [Table of Contents](#table-of-contents)
- [Automation Arsenal](https://github.com/dkorobtsov/automation-arsenal#table-of-contents)
  - [Java Libraries](https://github.com/dkorobtsov/automation-arsenal/tree/master/java#table-of-contents)
  - [Kotlin Libraries](#kotlin-libraries)
  	- [Assertions](#assertions)
  	- [Build](#build)
  	- [Code Quality](#code-quality)
  	- [Configuration and Properties](#configuration-and-properties)
  	- [CLI](#cli)
  	- [Database](#database)
  	- [Dependency Injection](#dependency-injection)
  	- [ElasticSearch](#elasticsearch)
  	- [Framework](#framework)
  	- [JSON](#json)
  	- [HowTo](#howto)
  	- [HTML](#html)
  	- [HTTP](#http)
  	- [Language extensions](#language-extensions)
  	- [Mocking](#mocking)
  	- [Mobile](#mobile)
  	- [Logging](#logging)
  	- [Reactive](#reactive)
  	- [Scripting](#scripting)
  	- [Source Code Utilities](#source-code-utilities)
  	- [Test Data](#test-data)
  	- [WebDriver](#webdriver)
  	- [WebSockets](#websockets)
  - [Tools](https://github.com/dkorobtsov/automation-arsenal/tree/master/tools#table-of-contents)
  - [Cheat Sheets](https://github.com/dkorobtsov/automation-arsenal/tree/master/resources#cheat-sheets)
  - [Reading](https://github.com/dkorobtsov/automation-arsenal/tree/master/resources#reading)
  - [Events](https://github.com/dkorobtsov/automation-arsenal/tree/master/resources#events)
  - [Video](https://github.com/dkorobtsov/automation-arsenal/tree/master/resources#video)

---

## Kotlin Libraries
### Assertions
[&uarr;](#table-of-contents)
* [Kluent](https://github.com/MarkusAmshove/Kluent) - Fluent Assertion-Library for Kotlin.
* [Assertk](https://github.com/willowtreeapps/assertk) - Yet another Kotlin assertions inspired by AssertJ.
* [Hamkrest](https://github.com/npryce/hamkrest) - Hamcrest remake for Kotlin.

### Build
[&uarr;](#table-of-contents)
* [Kotlin DSL](https://github.com/gradle/kotlin-dsl) - Kotlin language support for Gradle build scripts.

### Code Quality
[&uarr;](#table-of-contents)
* [Detekt](https://github.com/arturbosch/detekt) - Static code analysis for Kotlin.
* [KtLint](https://github.com/shyiko/ktlint) - Linter for Kotlin projects.
* [Gradle Code Quality Tools Plugin](https://github.com/vanniktech/gradle-code-quality-tools-plugin) - Gradle plugin generating ErrorProne, Findbugs, Checkstyle, PMD, CPD, Lint, Detekt & Ktlint Tasks for every subproject.

### Configuration and Properties
[&uarr;](#table-of-contents)
* [Config4K](https://github.com/config4k/config4k) - Lightweight [Typesafe Config](https://github.com/lightbend/config) wrapper for Kotlin.

### CLI
[&uarr;](#table-of-contents)
* [Clikt](https://github.com/ajalt/clikt) - Library for easy creation of CLI based applications.

### Database
[&uarr;](#table-of-contents)
* [Exposed](https://github.com/JetBrains/Exposed) - Lightweight SQL framework from JetBrains, uses JDBC driver under the hood, supports most popular database engines (Oracle, MySql, Postgre etc).

### Dependency Injection
[&uarr;](#table-of-contents)
* [Koin](https://github.com/InsertKoinIO/koin) - LightWeight Dependency Injection framework. Still not sure if it makes sense to use DI in test automation unless you are into unit testing, but this library sure worth mentioning.

### ElasticSearch
[&uarr;](#table-of-contents)
* [ES Kotlin](https://github.com/mbuhot/eskotlin) - Elasticsearch Query DSL for Kotlin.
* [ES Kotlin Wrapper](https://github.com/jillesvangurp/es-kotlin-wrapper-client) - Basically Kotlin wrapper for ES High Level HTTP Client.

### Framework
[&uarr;](#table-of-contents)
* [Kotlintest](https://github.com/kotlintest/kotlintest) - Flexible Kotlin testing framework.

### JSON
[&uarr;](#table-of-contents)
* [Kotshi](https://github.com/ansman/kotshi) - An annotations processor that generates Moshi adapters from immutable Kotlin data classes.

### HowTo
[&uarr;](#table-of-contents)
* [GOF in Kotlin](https://github.com/lmller/gof-in-kotlin) - Most popular design pattern examples in Kotlin.

### HTML
[&uarr;](#table-of-contents)
* [Kotlinx.html](https://github.com/Kotlin/kotlinx.html) - Kotlin DSL for HTML.

### HTTP
[&uarr;](#table-of-contents)
* [Fuel](https://github.com/kittinunf/Fuel) - Advertised as the easiest HTTP networking library for Kotlin/Android.

### Language extensions
[&uarr;](#table-of-contents)
* [Arrow](https://github.com/arrow-kt/arrow) - Functional companion to Kotlin's Standard Library.

### Mocking
[&uarr;](#table-of-contents)
* [Mockk](https://github.com/mockk/mockk) - Mocking library for unit tests.
* [Mockito Kotlin](https://github.com/nhaarman/mockito-kotlin) - Mockito adaptation for Kotlin.
* [Spark Kotlin](https://github.com/perwendel/spark-kotlin) - A Spark DSL in Kotlin, allows easy and fast web servers creation.

### Mobile
[&uarr;](#table-of-contents)
* [Kakao](https://github.com/agoda-com/Kakao) - Nice and simple DSL for Espresso in Kotlin. Allows writing Espresso tests that does not look ugly and much easier to maintain.
* [Marathon](https://github.com/Malinskiy/marathon) - Cross-platform test runner written for Android and iOS projects.

### Logging
[&uarr;](#table-of-contents)
* [OkLog](https://github.com/simonpercic/OkLog) - Yet another OkHttp traffic logging interceptor. Intercepts requests and generates link to view response details in browser. Looks awesome if you don't mind leaving IDE.
* [Kotlin Logging](https://github.com/MicroUtils/kotlin-logging) - Small Kotlin logging library. Using slf4j under the hood.
* [Log4j2 Kotlin API](https://logging.apache.org/log4j/kotlin/) - Kotlin logging facade based on Log4j2. Power of Log4j2 adapted for Kotlin projects.

### Reactive
[&uarr;](#table-of-contents)
* [RxTest](https://github.com/RubyLichtenstein/RxTest) - Kotlin DSL for easier RxJava testing.

### Scripting
[&uarr;](#table-of-contents)
* [KScript](https://github.com/holgerbrandl/kscript) - Enchanted Kotlin scripting support on *nix-based systems.

### Source Code Utilities
[&uarr;](#table-of-contents)
* [Kotlin Poet](https://github.com/square/kotlinpoet) - library with fluent interface for generating .kt files.

### Test Data
[&uarr;](#table-of-contents)
* [FakeIt](https://github.com/square/kotlinpoet) - Kotlin Fake Data Generator Library.

### WebDriver
[&uarr;](#table-of-contents)
* [Kirk](https://github.com/SergeyPirogov/kirk) - Selenium wrapper written in Kotlin. Nice idea, but project is no longer maintained.

### WebSockets
[&uarr;](#table-of-contents)
- [Scarlet](https://github.com/Tinder/Scarlet) - A Retrofit inspired WebSocket client by Tinder for Kotlin, Java, and Android.

&nbsp;

---

**Find this list helpful? Show some support:**
>[![GitHub followers](https://img.shields.io/github/followers/dkorobtsov.svg?style=social&label=Follow)](https://github.com/dkorobtsov)
[![GitHub forks](https://img.shields.io/github/forks/dkorobtsov/automation-arsenal.svg?style=social&label=Fork)](https://github.com/dkorobtsov/automation-arsenal/fork)
[![GitHub stars](https://img.shields.io/github/stars/dkorobtsov/automation-arsenal.svg?style=social&label=Star)](https://github.com/dkorobtsov/automation-arsenal)
[![Twitter Follow](https://img.shields.io/twitter/follow/dkorobtsov.svg?style=social&label=Follow)](https://twitter.com/dkorobtsov)

&nbsp;

**Interested in contributing?**

Contributions are welcome! Read [contribution guidelines](https://github.com/dkorobtsov/automation-arsenal/tree/master/contributing#contribution-guidelines).

### License

[![CC-BY-SA-4.0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
