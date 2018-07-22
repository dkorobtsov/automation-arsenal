# Automation Arsenal

**What is the purpose of this list?** To gather in one place up-to-date list of popular Java and Kotlin frameworks, libraries and tools directly (on indirectly) related to software testing, quality assurance and adjacent processes automation. Basically speaking everything related to [engineering productivity](https://saucelabs.com/blog/qa-is-not-enough-you-need-to-engineer-productivity).

**Why?** First of all - to have reference to all commonly used modern tools (and not so obvious things that can be handy or just good to know) in one place. Because it usually takes a little bit more then general Selenium knowledge to build reliable and flexible automated testing infrastructure. Another reason was to provide some guidance to those who are at the beginning of their journey - so categories are as focused as possible, keeping dead and 'vintage' libraries out of scope.

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:0 orderedList:0 -->

- [Table of Contents](#automation-arsenal)
	- [Java](#java)
		- [AOP](#aop)
		- [Alexa](#alexa)
		- [Asserts](#asserts)
		- [AWS](#aws)
		- [BDD](#bdd)
		- [Bots](#bots)
		- [Code Coverage](#code-coverage)
		- [Code Security](#code-security)
		- [Code Quality](#code-quality)
		- [CLI](#cli)
		- [Configuration and Properties](#configuration-and-properties)
		- [Dependency Injection](#dependency-injection)
		- [Environment](#environment)
		- [ElasticSearch](#elasticsearch)
		- [I/O](#io)
		- [Image Based](#image-based)
		- [JSON](#json)
		- [HowTo](#howto)
		- [HTML](#html)
		- [HTTP](#http)
		- [Language extensions](#language-extensions)
		- [Logging](#logging)
		- [Localisation](#localisation)
		- [Mobile](#mobile)
		- [Mail](#mail)
		- [Mocks](#mocks)
		- [Reflection](#reflection)
		- [Reactive](#reactive)
		- [Reporting](#reporting)
		- [REST](#rest)
		- [Serverless](#serverless)
		- [SSH](#ssh)
		- [Source Code Utils](#source-code-utils)
		- [SQL](#sql)
		- [Telephony](#telephony)
		- [Text Utilities](#text-utilities)
		- [Test Data](#test-data)
		- [xUnit Framework](#xunit-framework)
		- [WebDriver](#webdriver)
		- [XML](#xml)
	- [Kotlin](#kotlin)
		- [Assertions](#assertions)
		- [Build](#build)
		- [Code Quality](#code-quality)
		- [Configuration and Properties](#configuration-and-properties)
		- [CLI](#cli)
		- [Dependency Injection](#dependency-injection)
		- [Framework](#framework)
		- [JSON](#json)
		- [HTTP](#http)
		- [Language extensions](#language-extensions)
		- [Mocking](#mocking)
		- [Mobile Automation](#mobile-automation)
		- [Mutation](#mutation)
		- [Logging](#logging)
		- [Scripting](#scripting)
		- [Source Code Utils](#source-code-utils)
		- [SQL](#sql)
		- [Reactive](#reactive)
		- [HowTo](#howto)
		- [WebDriver](#webdriver)
	- [Tools](#tools)
		- [API](#api)
		- [Build Tools](#build-tools)
		- [Artifacts Handling](#artifacts-handling)
		- [CI / CD](#ci-cd)
		- [Code Coverage](#code-coverage)
		- [Code Quality](#code-quality)
		- [Console](#console)
		- [Chrome extensions](#chrome-extensions)
		- [Containers](#containers)
		- [Git](#git)
		- [Goodies](#goodies)
		- [IDE](#ide)
		- [IntelliJ Plugins](#intellij-plugins)
		- [Logging](#logging)
		- [Mobile](#mobile)
		- [Performance Testing](#performance-testing)
		- [Remote Management](#remote-management)
		- [Team Collaboration](#team-collaboration)
		- [Testing](#testing)
	- [Cheat Sheets](#cheat-sheets)
	- [Reading](#reading)
		- [General principles](#general-principles)
		- [Must Read Books](#must-read-books)
		- [Useful Read](#useful-read)
	- [Events](#events)

<!-- /TOC -->

## Java

### AOP
* [AspectJ](https://github.com/eclipse/org.aspectj) - Adds some magic to Java code by introducing aspects. Actively used by Allure Reporting Framework under the hood.
* [Gradle Plugin Android_AspectJX](https://github.com/HujiangTechnology/gradle_plugin_android_aspectjx) - Gradle plugin enabling AspectJ support for Android builds. Documentation is in Chinese but there is no alternatives available around.

### Alexa
* [Alexa Skills Kit Java SDK](https://github.com/alexa/alexa-skills-kit-sdk-for-java) - SDK kit for developing custom Alexa skills.
* [Alexa Skills Kit Testing Framework](https://github.com/KayLerch/alexa-skills-kit-tester-java) Testing Framework for custom Alexa skills validation.

### Asserts
* [Assertj](https://github.com/joel-costigliola/assertj-core) - Fluent Assertions for Java.
* [Java Hamcrest](https://github.com/hamcrest/JavaHamcrest) - Popular matchers library.

### AWS
* [AWS SDK Java](https://github.com/aws/aws-sdk-java) - Official Java SDK for controlling Amazon Web Services.
* [AWS Java Sample](https://github.com/aws-samples/aws-java-sample) - Sample project illustrating usage of the AWS SDK for Java.

### BDD
* [Сucumber JVM](https://github.com/cucumber/cucumber-jvm) - Executable Specification styled testing Framework.
* [Cucumber Java Skeleton](https://github.com/cucumber/cucumber-java-skeleton) - Demo project to get acquainted with Cucumber.
* [Spock](https://github.com/spockframework/spock) - Another popular executable specification framework. Actually tests have to be written in Groovy but is sure worth mentioning.

### Bots
* [JBot](https://github.com/rampatra/jbot) - Library for creating Slack and Facebook bots
* [Simple Slack Api](https://github.com/Ullink/simple-slack-api) -  Java Slack client library
* [Java Telegram Bot Api](https://github.com/pengrad/java-telegram-bot-api) - Telegram Bot API for Java
* [TelegramBots](https://github.com/rubenlagus/TelegramBots) - Java library to create bots using Telegram Bots API (With some examples).

### Code Coverage
* [JaCoCo](https://github.com/jacoco/jacoco) - Code Coverage Library.

### Code Security
* [DependencyCheck](https://github.com/jeremylong/DependencyCheck) - Checks project dependencies for publicly disclosed vulnerabilities.

### Code Quality
* [Android Check 2](https://github.com/stoyicker/android-check-2) - Static code analysis plugin for Android projects.
* [Error Prone](https://github.com/google/error-prone) - Static analysis tool catching common programming mistakes at compile-time.
* [Gradle Quality Plugin](https://github.com/xvik/gradle-quality-plugin) - Static code analysis for Java and Groovy projects using Checkstyle, PMD, SpotBugs (FindBugs) and CodeNarc.
* [Style Guide](https://github.com/google/styleguide) - Google collection of importable code style configuration files for most popular languages and IDEs.
*  [Qulice](https://github.com/teamed/qulice) - Maven quality control plugin. Qulice [explained](https://www.yegor256.com/2014/08/13/strict-code-quality-control.html).

### CLI
* [Picocli](https://github.com/remkop/picocli) - Java library for creating command line applications.
* [JCommander](https://github.com/cbeust/jcommander) - Command line parsing framework for Java.

### Configuration and Properties
* [Config](https://github.com/lightbend/config) - A type-safe configuration library for JVM languages.
* [Owner](https://github.com/lviggiano/owner) - Convenient library for properties handling. Greatly reduces boilerplate.

### Dependency Injection
* [Dagger 2](https://github.com/google/dagger) - modern and fast DI framework. Can be pretty [useful](https://medium.com/@fabioCollini/android-testing-using-dagger-2-mockito-and-a-custom-junit-rule-c8487ed01b56) for unit testing.
* [DaggerMock](https://github.com/fabioCollini/DaggerMock) - A JUnit rule to easily override Dagger 2 objects.

### Environment
* [Testcontainers Java](https://github.com/testcontainers/testcontainers-java) - Java 8 library providing lightweight, throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container. Good blog [post](https://zeroturnaround.com/rebellabs/java-integration-testing-with-testcontainers/) on topic.

### ElasticSearch
* [ElasticSearch REST High Level Client](https://github.com/elastic/elasticsearch/tree/master/client/rest-high-level) - Official Java REST client for managing ElasticSearch instance. Docs are available [here](https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/java-rest-high.html). ES is extremely useful in certain situations, but is known for steep learning curve. Makes sense to start with [videos](https://egghead.io/courses/get-started-with-elasticsearch).
* [Logstash](https://github.com/elastic/logstash) - Part of ELK (ElasticSearch, Logstash, Kibana) logging stack, responsible for transport part.
* [Kibana](https://github.com/elastic/kibana) - Search and Analytics Dashboard for ElasticSearch. Probably it should be in the Tools section, but it's better to keep here with related products.

### I/O
* [Okio](https://github.com/square/okio) - Popular [Square](http://square.github.io/) library: I/O operations made easy.

### Image Based
* [SikuliX2](https://github.com/RaiMan/SikuliX2) - massive redesign of popular SikuliX library. Promised to be released in October. So, let in be here, say "in watch list". One of the announced 'killer features' is an option to perform screenshot based testing of mobile apps.
* [Ashot](https://github.com/yandex-qatools/ashot) - Useful library from Yandex for operating screenshots. Screenshot based testing etc.
* [Screenshot Tests For Android](https://github.com/facebook/screenshot-tests-for-android) - Popular screenshot based mobile devices testing solution from Facebook.

### JSON
* [JSONAssert](https://github.com/skyscreamer/JSONassert) - Library simplifying assertion of Json documents.
* [Moshi](https://github.com/square/moshi) - modern JSON library for Android and Java, works really well with other [Square](http://square.github.io/) libraries.
* [Moshi Lazy Adapters](https://github.com/serj-lotutovici/moshi-lazy-adapters) - A collection of simple JsonAdapters for Moshi.

### HowTo
* [Java Design Patterns](https://github.com/iluwatar/java-design-patterns) - Extensive collection of Design Pattern examples.

### HTML
* [Jsoup](https://github.com/jhy/jsoup) - Java library for working with real-world HTML. It provides a very convenient API for extracting and manipulating data. Extremely useful. Works directly with html, without need of WebDriver. In certain cases pairs really well with WebDriver based library, greatly speeding up test execution - especially when it's needed to read huge amount of data from the UI.

### HTTP
* [OkHttp](https://github.com/square/okhttp) - Popular HTTP client by [Square](http://square.github.io/).
* [Parallec](https://github.com/eBay/parallec) - Lightning fast Parallel Async HTTP/SSH/TCP/UDP/Ping Client Java Library. Allows requesting thousands of remote endpoints, collect results and forward them elsewhere.
* [LoggingInterceptor](https://github.com/dkorobtsov/LoggingInterceptor) My own version of popular Android [library](https://github.com/ihsanbal/LoggingInterceptor) adapted for use with popular Java loggers - basically OkHttp interceptor, with pretty  requests/responses output to console. Useful when writing API tests or developing REST client.
* [Retrofit](https://github.com/square/retrofit) - Type-safe HTTP client for Android and Java by Square. Working with REST API's made easy and simple.
* [Feign](https://github.com/OpenFeign/feign) - Another popular HTTP client library. Quite similar to Retrofit.

### Language extensions
* [Auto](https://github.com/google/auto) - A collection of source code generators for Java.
* [Lombok](https://github.com/rzwitserloot/lombok) - Annotation processing library, greatly reducing Java boilerplate. Check out list of [features](https://projectlombok.org/features/all).
* [Vavr](https://github.com/vavr-io/vavr) - functional Java 8+ extension, adds some useful features - Scala-like switches, tuples, immutable data structures. Greatly reduces boilerplate.
* [FreeBuilder](https://github.com/inferred/FreeBuilder) - Automatic generation of the Builder pattern.
* [Manifold](https://github.com/manifold-systems/manifold) - yet another Java extension framework. Probably not yet ready for production, but it's definitely in a watchlist. Just check the [demo](https://manifold.systems/images/JsonDemo.mp4) to see some black magic.

### Logging
* [Log4j2](https://github.com/apache/logging-log4j2) - one of the most popular Java logging frameworks. Endless customization options, though could be a little bit complicated to perform initial configuration.
* [Slf4j](https://github.com/qos-ch/slf4j) - Simple Logging Facade for Java
* [Tinylog](https://github.com/pmwmedia/tinylog) - Minimalistic logging framework for Java and Android.

### Localisation
* [Language Detector](https://github.com/optimaize/language-detector) - Library taking text as input as returning language it was written in. Should admit returns quite a lot of false positives for short strings, but still - extremely useful for fast localization checks.
* [Languagetool](https://github.com/languagetool-org/languagetool) - Style and Grammar Checker supporting 25+ Languages. Check official [docs](https://languagetool.org/dev) for usage details.

### Mobile
* [Appium](https://github.com/appium/appium) - Most popular tool for mobile devices UI automation. Note that out of the box it rarely does something useful. Heavy customization is needed for particular use case. Works really well when paired with [Selenide](#selenide).
* [Appium Espresso Driver](https://github.com/appium/appium-espresso-driver) - Not yet ready for production. Looks promising, so let it be in watch list.
* [Appium Test Distribution](https://github.com/saikrishna321/AppiumTestDistribution) - Ready solution for tests distribution on multiple mobile devices. Based on Appium and TestNG. This is what I meant saying that out of the box Appium is pretty useless. You'll have to write your own solution or use this one (at least as an example).
* [Android JUnit5 plugin](https://github.com/mannodermaus/android-junit5) - Library providing JUnit5 support for Android projects
* [Espresso](https://developer.android.com/training/testing/espresso/) - Google own testing framework for Android UI testing. Question is open which one is better option. In general, if you want flexibility - use Appium, if speed is a priority - go with Espresso.
* [Espresso Samples](https://github.com/chiuki/espresso-samples) - Demo Project displaying various techniques for using Espresso library.
* [JADB](https://github.com/vidstige/jadb) - ADB client in Java.
* [Leak Canary](https://github.com/square/leakcanary) - A memory leak detection library for Android and Java. Extremely useful for finding leaks.
* [Spoon](https://github.com/square/spoon) - Tool for distributing Android instrumentation tests across multiple devices.

### Mail
* [jcabi-email](https://github.com/jcabi/jcabi-email) - Email Sending Java SDK.
* [Greenmail](https://github.com/greenmail-mail-test/greenmail) - Mail Testing Library.
* [Gmail API Client Library for Java](https://developers.google.com/api-client-library/java/apis/gmail/v1) Gmail itself can be pretty useful for testing e-mails. Especially combined with + [trick](https://www.thewindowsclub.com/gmail-address-tricks).

### Mocks
* [JMockit](https://github.com/jmockit/jmockit1) - Library for creating test mocks. Not so famous as Mockito, but definitely just as good. Just a matter of taste which one to choose.
* [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java) - Java bindings for [Hoverfly](https://hoverfly.io/) - proxy for http services simulation. Flexible DSL.
* [Mockito](https://github.com/mockito/mockito) - Most popular Mocking framework for Java
* [MockWebServer](https://github.com/square/okhttp/tree/master/mockwebserver) - OkHttp client own library for mocking web server responses.
* [OkReplay](https://github.com/airbnb/okreplay) - Yet another approach to testing web services. Just record you app network traffic, then replay it in tests. No longer need to worry about 3rd services downtime. NB. Intended for using with OkHTTP client.
* [Spark](https://github.com/perwendel/spark) - Simple Web Framework. Why it's here? Sometimes it's easier and faster to create Web Server then to mock it :)
* [RESTMock](https://github.com/andrzejchm/RESTMock) - HTTP server for Android instrumentation tests. Works on top of MockWebServer, pairs really well with Hamcrest matchers.
* [Wiremock](https://github.com/tomakehurst/wiremock) - Yet another tool for mocking HTTP services.

### Reflection
* [Reflections](https://github.com/ronmamo/reflections) - Java runtime metadata analysis.

### Reactive
* [RxJava](https://github.com/ReactiveX/RxJava) - Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM. Since it's practically a standard in modern Android applications, good no know how to use it. Read "Building a Reactive Mindset" [blog post](https://upday.github.io/blog/reactive_mindset_burgers/) for comprehensive explanation.
* [Awaitility](https://github.com/awaitility/awaitility) - Small Java DSL for testing asynchronous operations.

### Reporting
* [Allure 2](https://github.com/allure-framework/allure2) Test reports. Good looking, flexible and easy to use. Easily integrates with most of the  popular testing frameworks. Lots of plugins. Looking forward to see a third version. Any bets it will be released at all?
* [Allure Java](https://github.com/allure-framework/allure-java) Collection of small libraries (most of them contains just a single class) to integrate Allure with popular Java frameworks.
* [Report Portal](https://github.com/reportportal/reportportal) Great solution for aggregating all your tests run results into single highly customizable dashboard. Provides good insight on how automated testing projects are doing under the hood. Requires stand alone server, installs as a group of dockerized microservices.

### REST
* [REST-assured](https://github.com/rest-assured/rest-assured) - Most popular library for REST services testing. Personally however, I prefer Retrofit / OkHttp / Moshi / AssertJ combination. But should admit that both approaches have pros and cons.

### Serverless
* [Docker In AWS Lambda](https://github.com/vladgolubev/docker-in-aws-lambda) - illustration for [this](https://medium.com/@vladholubiev/how-did-i-hack-aws-lambda-to-run-docker-containers-7184dc47c09b) blog post.
* [Lambda](https://github.com/iron-io/lambda) - Set of tools and libraries for converting Lambdas to Docker images.
* [Lambda-Selenium](https://github.com/blackboard/lambda-selenium)  - Demo project, displaying how to run Selenium tests using AWS Lambda
* [Lambdium](https://github.com/smithclay/lambdium) - yet another library for running webdriver tests in AWS Lambda

### SSH
* [JSch](https://github.com/is/jsch) - Java SSH interface. Allows to manage remote *nix servers programmatically.

### Source Code Utils
* [Javapoet](https://github.com/square/javapoet) - Library with fluent interface for generating .java files.

### SQL
* [jdbi](https://github.com/jdbi/jdbi) - Jdbi provides convenient, idiomatic access to relational databases in Java.
* [Requery](https://github.com/requery/requery) - Modern SQL based query & persistence for Java / Kotlin / Android.
* [RxJava JDBC](https://github.com/davidmoten/rxjava-jdbc) - Efficient execution and functional composition of database calls using JDBC and RxJava Observables.
* [SQLDelight](https://github.com/square/sqldelight) - Generates Java models from CREATE TABLE statements.

### Telephony
* [Asterisk REST Interface](https://github.com/l3nz/ari4java) -  [Asterisk](https://www.asterisk.org/) ARI interface bindings for Java. Was researching ways for telecom automation. This one looks promising.
* [Twilio Java](https://github.com/twilio/twilio-java) - Way to go if you up to sms and calling automation. But be ready to pay.
* [Libphone Number](https://github.com/googlei18n/libphonenumber) - Google's common Java, C++ and JavaScript library for parsing, formatting, and validating international phone numbers.

### Text Utilities
* [Apache Commons Text](https://github.com/apache/commons-text) - Collection of utils for working with strings. May be a little bit unexpected library in this list, but in almost every project I've seen there is own string utilities collection doing mostly same things.
* [JUnidecode](https://github.com/gcardone/junidecode) - Pretty useful library for handling text in exotic locales.

### Test Data
* [Fabricator](https://github.com/azakordonets/fabricator) - Fake data generator.
* [Java Faker](https://github.com/DiUS/java-faker) - Another useful library for fake Test Data generation.
* [SecLists](https://github.com/danielmiessler/SecLists) - Security tester's companion. It's a collection of multiple types of lists used during security assessments, collected in one place. Check big list of naughty strings!
* [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) - Library for injecting reproducible random data to unit tests. Heavily used by [Elastic](https://www.elastic.co/guide/en/elasticsearch/reference/current/randomized-testing.html) for ElasticSearch testing.

### xUnit Framework
* [JUnit4](https://github.com/junit-team/junit4) - Good old JUnit. In general there is no big difference at the moment which one to choose - JUnit4, JUnit or TestNG. Mostly it's a matter of taste.
* [JUnitParams](https://github.com/Pragmatists/JUnitParams) - JUnit4 extension for creating parameterised tests.
* [JUnit5](https://github.com/junit-team/junit5) - Next generation of JUnit with some interesting features.
* [Mastering JUnit5](https://github.com/bonigarcia/mastering-junit5) - Collection of code examples displaying how to use new JUnit5 features.
* [Test Data Supplier](https://github.com/sskorol/test-data-supplier) - Extended version of TestNG DataProvider.

### WebDriver
* [Selenide](https://github.com/codeborne/selenide) - Best UI testing library. Period. Technically it's a wrapper over Selenium, but who writes tests using pure Selenium nowadays? Check [wiki](https://github.com/codeborne/selenide/wiki/Selenide-vs-Selenium) for general comparison.
* [Selenium](https://github.com/SeleniumHQ/selenium) - Testing framework for web applications. Understanding how in works is a must since it's under the hood in almost all modern UI testing libraries, but keep in mind that writing tests with pure Selenium will be much slower because of the boilerplate.
* [Selenoid](https://github.com/aerokube/selenoid) - Modern library for running browsers within containers, Selenium Hub successor.
* [Selenoid UI](https://github.com/aerokube/selenoid-ui) - Graphical user interface for Selenoid project.
* [Go Grid Router](https://github.com/aerokube/ggr) - Load balancer for Selenium clusters.
* [WebDriver Manager](https://github.com/bonigarcia/webdrivermanager) - Automatic management of Selenium WebDriver binaries. NB: If you are using Selenide - don't bother looking at this library, it's already included under the hood.
* [Browsermob Proxy](https://github.com/lightbody/browsermob-proxy) utility to help web developers watch and manipulate network traffic from their AJAX applications. NB: In scope of UI tests since version [4.11](http://selenide.org/2018/04/02/selenide-4.11/) it's possible to use Selenide own proxy which is using Browsermob under the hood.
* [Video Recorder Java](https://github.com/SergeyPirogov/video-recorder-java) - Library for UI test execution process video recording. Just add some annotations, simple as that.

### XML
- [JAXB Converter](https://github.com/square/retrofit/tree/master/retrofit-converters/jaxb) - Retrofit Converter for serialization to and from XML.
- [XML Unit](https://github.com/xmlunit/xmlunit) - XML testing library.

## Kotlin
### Assertions
* [Kluent](https://github.com/MarkusAmshove/Kluent) - Fluent Assertion-Library for Kotlin.
* [Assertk](https://github.com/willowtreeapps/assertk) - Yet another Kotlin assertions inspired by AssertJ.
* [Hamkrest](https://github.com/npryce/hamkrest) - Hamcrest remake for Kotlin.

### Build
* [Kotlin DSL](https://github.com/gradle/kotlin-dsl) - Kotlin language support for Gradle build scripts. Looks promising, but at the moment for evaluation purposes only.

### Code Quality
* [Detekt](https://github.com/arturbosch/detekt) - Static code analysis for Kotlin.

### Configuration and Properties
* [Properlty](https://github.com/ufoscout/properlty) - Simple Kotlin and Java configuration library. Looks really convenient.

### CLI
* [Clikt](https://github.com/ajalt/clikt) - Library for easy creation of CLI based applications.

### Dependency Injection
* [Koin](https://github.com/InsertKoinIO/koin) - LightWeight Dependency Injection framework. Still not sure if it makes sense to use DI in test automation if you are not into unit testing, but this library sure worth mentioning.

### Framework
* [Kotlintest](https://github.com/kotlintest/kotlintest) - Flexible Kotlin testing framework.

### JSON
* [Kotshi](https://github.com/ansman/kotshi) - An annotations processor that generates Moshi adapters from immutable Kotlin data classes.

### HTTP
* [Fuel](https://github.com/kittinunf/Fuel) - Advertised as the easiest HTTP networking library for Kotlin/Android. Frankly speaking tried in scope of one project. Tastes good, but not that good to switch from Retrofit. Still, once again - just a matter of taste.

### Language extensions
* [Arrow](https://github.com/arrow-kt/arrow) - Functional companion to Kotlin's Standard Library.

### Mocking
* [Mockk](https://github.com/mockk/mockk) - Mocking library for unit tests.
* [Mockito Kotlin](https://github.com/nhaarman/mockito-kotlin) - Mockito adaptation for Kotlin.
* [Spark Kotlin](https://github.com/perwendel/spark-kotlin) - A Spark DSL in Kotlin, allows easy and fast web servers creation.

### Mobile Automation
* [Kakao](https://github.com/agoda-com/Kakao) - Nice and simple DSL for Espresso in Kotlin. Allows writing Espresso tests that does not look ugly and much easier to maintain.

### Mutation
* [Pitest aka PIT](https://github.com/hcoles/pitest) - Mutation testing system for Java and the JVM. In short - testing system for unit tests. Modifies your source code and checks if test will fail. If they won't you could be doing something wrong.

### Logging
* [OkLog](https://github.com/simonpercic/OkLog) - Yet another OkHttp traffic logging interceptor. Intercepts requests and generates link to view response details in browser. Looks awesome if you don't mind leaving IDE.
* [Kotlin Logging](https://github.com/MicroUtils/kotlin-logging) - Small Kotlin logging library. Using slf4j under the hood.

### Scripting
* [KScript](https://github.com/holgerbrandl/kscript) - Enchanted Kotlin scripting support on *nix-based systems.

### Source Code Utils
* [Kotlin Poet](https://github.com/square/kotlinpoet) - library with fluent interface for generating .kt files.

### SQL
* [Exposed](https://github.com/JetBrains/Exposed) - Lightweight SQL framework from JetBrains, Used JDBC driver under the hood, supports most popular database engines (Oracle, MySql, Postgre etc).

### Reactive
* [RxTest](https://github.com/RubyLichtenstein/RxTest) - Kotlin DSL for easier RxJava testing.

### HowTo
* [GOF in Kotlin](https://github.com/lmller/gof-in-kotlin) - Most Popular design patterns examples in Kotlin.

### WebDriver
* [Kirk](https://github.com/SergeyPirogov/kirk) - Selenium wrapper written in Kotlin.

## Tools

### API
* [Json Schema 2 Pojo](https://github.com/joelittlejohn/jsonschema2pojo) - Extremely useful tool for quickly consuming an API. Just copy and [paste](http://www.jsonschema2pojo.org/) response, get Java class, attach convertor (like Moshi for example) and get an object on a next Retrofit call.
* [Google API Explorer](https://developers.google.com/apis-explorer/#p/) - Explorer for APIs provided by Google.
* [Swagger](https://swagger.io/) - Way to go when designing APIs.
* [Postman](https://www.getpostman.com/) One of the best tools available for working with API.
* [Programmable Web](https://www.programmableweb.com/apis/directory) - Largest API Directory on the Web. To answer typical question - if there are any sandboxes for API testing practice. Any public API will do. :)

### Build Tools
* [Gradle](https://gradle.org/) - New projects tend to use Gradle. Flexible configuration DSL.
* [Maven](https://maven.apache.org/) - Most widely used build tool at the moment.

### Artifacts Handling
* [Artifact Listener](https://www.artifact-listener.org/) - Get notified when followed library gets an update.
* [Gradle, Please](https://gradleplease.appspot.com/#selenide) - Nice little tool to search for Gradle dependencies.
* [Maven Central](http://search.maven.org/) - Search engine for Maven Central repository.

### CI / CD
* [Ansible](https://github.com/ansible/ansible) IT automation system. Handles configuration-management, application deployment, cloud provisioning, ad-hoc task-execution, and multinode orchestration.
* [Ansible Semaphore](https://github.com/ansible-semaphore/semaphore) - Open source Web UI solution for launching Ansible tasks.
* [Fastlane](https://github.com/fastlane/fastlane) - The easiest way to automate building and releasing  iOS and Android apps.
* [Hygieia](https://github.com/capitalone/Hygieia) - Customizable DevOps console - to put all data like Static Code Analysis, Unit and E2E tests results, Deployment status etc in one place.
* [Jenkins](https://jenkins.io/) - Most popular CI Server at the moment.
* [Rultor](https://github.com/yegor256/rultor) - Code merging bot.
* [Snyk](https://github.com/snyk/snyk) - CLI and build-time tool to find & fix known vulnerabilities in open-source dependencies
* [Travis CI](https://travis-ci.org/) - Out of the box CI solution for GitHub hosted projects.
* [Webhook](https://github.com/adnanh/webhook) - Lightweight webserver with configurable webhooks. Allows to execute shell commands on remote servers.

### Code Coverage
* [Coveralls](https://coveralls.io/) - Code coverage solution. Free for open source projects.

### Code Quality
* [Diffy](https://github.com/twitter/diffy) - Tool for finding potential bugs by running old and new code versions side by side.
* [SonarQube](https://github.com/SonarSource/sonarqube) - Continuous quality inspection.
* [SonarCloud](https://sonarcloud.io) - Basically, SonarQube as a service. Free for open source projects.

### Console
* [Brew](https://github.com/Homebrew/brew) - Command line package manager for MacOS.
* [iTerm2](https://www.iterm2.com/features.html) - MacOS terminal with lots of useful features.
* [Powerline Shell](https://github.com/b-ryan/powerline-shell) - Popular prompt generator for Bash, ZSH, Fish, and tcsh:
* [Scoop](https://github.com/lukesampson/scoop) - A command-line installer for Windows. Works similar to Brew in MacOs.
* [The Fuck](https://github.com/nvbn/thefuck) - Small handy util which corrects your previous console command.

### Chrome extensions
* [AndroidSDKSearchExtension](https://github.com/romannurik/AndroidSDKSearchExtension) - A Chrome extension that adds an 'ad' omnibox command and view source links for the Android SDK.
* [Bug Magnet](https://github.com/gojko/bugmagnet) - Browser assistant for web page manual testing.
* [ChroPath](https://chrome.google.com/webstore/detail/chropath/ljngjbnaijcbncmcnjfhigebomdlkcjo?hl=en) - Chrome Dev panel extension for working with Selenium locators. Pretty useful.
* [Json Viewer](https://github.com/tulios/json-viewer) - Convenient Chrome extension for printing JSON files.

### Containers
* [Docker](https://www.docker.com/) - De facto standard for apps execution in containers.

### Git
* [Git](https://github.com/git/git) - Obviously should be in the list.
* [Sourcetree](https://www.sourcetreeapp.com/) - Convenient VCS client from Atlassian with git, subversion (via git-svn) and mercurial support. Configuration for work with hosted Gitlab instance can be a little bit tricky.
* [GitKraken](https://www.gitkraken.com/) - Awesome VCS client. Hosted GitLab repositories are supported in paid version only.

### Goodies
* [Atom](https://github.com/atom/atom) - Highly customisable text editor.
* [Coggle](https://coggle.it/) - Convinient tool for creating mindmaps.
* [Gif For Cli](https://github.com/google/gif-for-cli) - Library by Google for converting gifs or small videos to ASCII animations.
* [Kali](https://www.kali.org/) - Kali is Linux distribution with pre-installed collection of pentesting tools.
* [Phone Number Parser](https://libphonenumber.appspot.com/) - Small util for phone numbers validation. Utilising [Libphonenumber](https://github.com/googlei18n/libphonenumber) library.
* [Shodan](https://www.shodan.io/) - Search engine for Internet of Things. Never know you can find.
* [Sourcerer App](https://github.com/sourcerer-io/sourcerer-app) - Developer profile generation tool. Consumes git or Github repositories and returns full overview of languages and technologies used.
* [Toggl](https://toggl.com/) - Excellent time management tool.
* [Zuppit](https://zuppit.co.uk/) - Free tool for website availability monitoring.

### IDE
* [IntelliJ IDEA](https://www.jetbrains.com/idea/download) - Best Java IDE. For testing purposes Community Edition is more then enough.

### IntelliJ Plugins
* [Advanced Java Folding](https://plugins.jetbrains.com/plugin/9320-advanced-java-folding) This plugin extends the IDE’s folding features to emulate some of these modern languages’ features helping fight verbosity. In other words - after applying this plugin you Java code will look like mix of Scala, Groovy and Kotlin.
* [Awesome Console](https://github.com/anthraxx/intellij-awesome-console) - Open source, file and url links right from console.
* [Docker Integration](https://www.jetbrains.com/help/idea/docker.html) - Work with Docker from IDE.
* [Grep Console](https://github.com/krasa/GrepConsole) - Convenient console logs filtering.
* [Infinitest](https://github.com/infinitest/infinitest) - (Eclipse/IntelliJ) IDE Plugin for TDD Jedi's. Basically it detects changes in class and runs related unit tests. TDD assistant, so to say.
* [IntelliJ KeyPromoter X](https://github.com/halirutan/IntelliJ-Key-Promoter-X) - Plugin assisting to learn IDE shortcuts. Can be very annoying, I know.
* [.gitignore](https://github.com/hsz/idea-gitignore) - Git ignore support.
* [JsonToKotlinClass](https://github.com/wuseal/JsonToKotlinClass) - Plugin for Android Studio And IntelliJ Idea to generate Kotlin data class code from JSON text
* [Lombok Support](https://github.com/mplushnikov/lombok-intellij-plugin) - IntelliJ Lombok plugin.
* [Markdown Navigator](https://github.com/vsch/idea-multimarkdown) - Markdown support. Adds markdown editor to IDE.
* [Statistic](https://plugins.jetbrains.com/plugin/4509-statistic) - Shows project statistic.
* [String Manipulation](https://github.com/krasa/StringManipulation) - Adds String manipulation options to right click menu.

### Logging
* [LogViewer](https://github.com/satyagraha/logviewer) - Browser based client for reading logs from most commonly used web servers.

### Mobile
* [Appium Docker Android](https://github.com/appium/appium-docker-android) - Installing Appium environment (especially for a first time) is a little bit over-complicated. Alternative solution is to use pre-configured docker container.
* [Battery Historian](https://github.com/google/battery-historian) - Tool fro Google for analysing device battery consumers using Android "bugreport" files.
* [Droid at Screen](https://github.com/ribomation/DroidAtScreen1) - Little app which is extremely useful when you need to show video feed from Android device (say, during presentation on a big screen). Considered many alternatives. Per my perception it's a best one.
* [Droid Test Helper](https://github.com/KazuCocoa/DroidTestHelper) - Helper application to test android applications, handles some settings via adb broadcast. Personally used other solution more fit for my purposes, but this library looks quite handy as well.
* [IOS Device Server](https://github.com/badoo/ios-device-server) - A server for managing, booting, and controlling simulators and devices on remote host machines.
* [Flick](https://github.com/isonic1/flick) - A CLI to capture screenshots, video, logs, device info and device vitals(memory, cpu) for Android (Devices & Emulators) and iOS (Devices).
* [Manual Test Demultiplexer](https://github.com/eBay/mtdtool) - eBay authored tool providing interface for driving manual testing on multiple physical devices. Requires Android SDK. Haven't tried it myself, added to list just for code samples.
* [Stetho](https://github.com/facebook/stetho) Debug bridge for Android applications, enabling the powerful Chrome Developer Tools and much more, owned by Facebook.
* [Open STF](https://github.com/openstf/stf) - Smartphone Test Farm solution. If you don't want to use cloud services, here is on-prem solution.
* [Test Butler](https://github.com/linkedin/test-butler) - helper tool to make Android UI testing on emulators more stable and predictable.

### Performance Testing
* [Gatling](https://github.com/gatling/gatling) - Popular tool for Performance testing. Written in Scala. Read "The Art Of Destroying Your App With Gatling" blog [post](https://gatling.io/2018/03/07/the-art-of-destroying-your-web-app/) on official website.
* [Yellow Lab Tools](https://github.com/gmetais/YellowLabTools/) - Great open source tool for auditing web pages.

### Remote Management
* [Royal TS](https://www.royalapplications.com/ts/mac/features) - Awesome Remote Management Solution. Supports RDC, SSH, FTP etc. Free to use for up to 10 connections.

### Team Collaboration
* [Instant Terminal Sharing](https://tmate.io/) - Can be useful in certain situations.
* [Recordit](http://recordit.co/) - Nice little tool for recording and sharing screencasts.

### Testing
* [HAR Viewer](http://www.softwareishard.com/blog/har-viewer/) - Online tool for HTTP Archive files visualization
* [XPath Generation](http://xpathify.herokuapp.com/) - Small web utility for XPath generation.
* [UI Testing Playground](https://the-internet.herokuapp.com/) - Good for practicing UI automation techniques.


## Cheat Sheets
* [Android Shell Commands](https://github.com/cesards/AndroidShell) - Android shell commands cheat sheet.
* [CSS Selector Reference](https://www.w3schools.com/cssref/css_selectors.asp) Must learn for UI automation.
* [DevDocs](https://devdocs.io/) - Great collection of API documentation for most of major programming languages, databases and frameworks.
* [DevHints](https://devhints.io/) - Search engine for cheat sheets. TL; DR for developers.
* [Docker](http://files.zeroturnaround.com/pdf/zt_docker_cheat_sheet.pdf) - Docker Commands Cheat Sheet.
* [Every Programmer Should Know](https://github.com/mtdvio/every-programmer-should-know) - A collection of (mostly) technical things every software developer should know
* [Git](http://files.zeroturnaround.com/pdf/zt_git_cheat_sheet.pdf) - Git Commands Cheat Sheet.
* [Java Collections](http://files.zeroturnaround.com/pdf/zt_java_collections_cheat_sheet.pdf) - Java Collections Cheat Sheet.
* [Java Generics](http://files.zeroturnaround.com/pdf/zt_java_generics_cheatsheet.pdf) - Java Generics cheat sheet.
* [Java 8 Best Practices](http://files.zeroturnaround.com/pdf/zt_java8_best_practices.pdf) - Java 8 Best Practices.
* [Java 8 Streams](http://files.zeroturnaround.com/pdf/zt_java8_streams_cheat_sheet.pdf) - Java 8 Streams Cheat Sheet.
* [JUnit](http://files.zeroturnaround.com/pdf/zt_junit_cheat_sheet.pdf) - JUnit Cheat Sheet.
* [JVM Options](http://files.zeroturnaround.com/pdf/zt_JVM-options-cheat-sheet.pdf) JVM options Cheat Sheet.
* [Linux Commands](https://www.loggly.com/wp-content/uploads/2015/05/Linux-Cheat-Sheet-Sponsored-By-Loggly.pdf) - Most commonly used Linux commands.
* [Locators Cheat Sheet](http://www.cheat-sheets.org/saved-copy/Locators_table_1_0_2.pdf) - Selenium locators cheat sheet
* [Maven](http://files.zeroturnaround.com/pdf/Maven-cheat-sheet.pdf) - Maven cheat sheet.
* [Regex](http://files.zeroturnaround.com/pdf/zt_regular-expressions-cheat-sheet.pdf) - Regular expressions cheat sheet.
* [RxJava](http://files.zeroturnaround.com/pdf/zt-rxjava-cheat-sheet.pdf) - RxJava cheat sheet.
* [SQL](http://files.zeroturnaround.com/pdf/zt_sql_cheat_sheet.pdf) - SQL cheat Sheet.
* [Vim Visual Cheat Sheet](http://people.csail.mit.edu/vgod/vim/vim-cheat-sheet-en.png) - It's good to know how to exit vim without referring to [StackOverflow](https://stackoverflow.com/questions/11828270/how-to-exit-the-vim-editor).

## Reading

### General principles
* [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) - Don't repeat yourself. Say no to code duplication.
* [YAGNI](https://testing.googleblog.com/2017/08/code-health-eliminate-yagni-smells.html) - You aren't gonna need it. Implement only features you actually need. Delete all code that is not in use.
* [KISS](https://people.apache.org/~fhanik/kiss.html) - Keep it simple, Stupid. Keep code as simple as possible.
* [SOLID](https://en.wikipedia.org/wiki/SOLID) - Five design principles to make code more understandable, flexible and maintainable.

### Practical advices
* [Fluent Interface](https://www.martinfowler.com/bliki/FluentInterface.html) - Idea of Fluent Interfaces explained. Consider it as one of the building blocks for building internal testing DSL.
* [Reduce Nesting](https://testing.googleblog.com/2017/06/code-health-reduce-nesting-reduce.html) - Good example how to reduce nesting and improve readability.
* [Tell Don't Ask Principle](https://martinfowler.com/bliki/TellDontAsk.html) - Pretty useful article from Martin Fowler. Could be really helpful when designing Page Object Model.
* [To Comment or Not to Comment?](https://testing.googleblog.com/2017/07/code-health-to-comment-or-not-to-comment.html) - Article about comments in code.

### Must Read Books
* [Clean Code](https://www.goodreads.com/book/show/3735293-clean-code) by Uncle Bob. Must read. Period. Badly written code is a total mess. At certain point maintenance will consume all the time you have.
* [xUnit Test Patterns: Refactoring Test Code](https://www.goodreads.com/book/show/337302.xUnit_Test_Patterns) by Gerard Meszaros. Bible of unit testing. Same principles are applicable to any automated tests. Another must read.

### Useful Read
* [Android Testing Guide](https://github.com/ravidsrk/android-testing-guide) - Worth reading, pretty good guide.
* [Google Testing Blog](https://testing.googleblog.com/) - Google Testing Blog. Quite a few updates recently, but in general lots of useful ideas. In general makes also sense to read "[How Google Tests Software](https://books.google.com/books/about/How_Google_Tests_Software.html?id=vHlTOVTKHeUC)" - some ideas are really useful.
* [Java 8 Tutorial](https://github.com/winterbe/java8-tutorial) - Pretty good guide for Java 8 features.
* [Software Testing Anti-patterns](http://blog.codepipes.com/testing/software-testing-antipatterns.html) - Just good article. Makes sense to read.
* [Test Smells](http://xunitpatterns.com/Test%20Smells.html) - Parts of the book xUnit Test Patterns. Most of the presentations explaining bad test design are just an illustration of this list.
* [Yegor's Blog](https://www.yegor256.com/) - Always a good read.


## Events
* [Software Testing Conferences](https://testingconferences.org/) - Live calendar for incoming Software testing conferences.
* [IT Conference Top](https://itconference.top/) - Best Developer Conferences to attend in Europe.
