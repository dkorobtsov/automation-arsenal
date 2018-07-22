## [Table of Contents](#table-of-contents)
<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->
  - [Java Libraries](#java-libraries)
    - [AOP](#aop)
    - [Alexa](#alexa)
    - [Assertions](#assertions)
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
    - [Mutation](#mutation)
    - [Reflection](#reflection)
    - [Reactive](#reactive)
    - [Reporting](#reporting)
    - [REST](#rest)
    - [Serverless](#serverless)
    - [SSH](#ssh)
    - [Source Code Utilities](#source-code-utilities)
    - [SQL](#sql)
    - [Telephony](#telephony)
    - [Text Utilities](#text-utilities)
    - [Test Data](#test-data)
    - [xUnit Framework](#xunit-framework)
    - [WebDriver](#webdriver)
    - [XML](#xml)
  - [Kotlin Libraries](#kotlin-libraries)
  - [Tools](#tools)
  - [Cheat Sheets](#cheat-sheets)
  - [Reading](#reading)
  - [Events](#events)
<!-- /TOC -->

## Java Libraries

### AOP
[&uarr;](#table-of-contents)
* [AspectJ](https://github.com/eclipse/org.aspectj) - Adds some magic to Java code by introducing aspects. Actively used by Allure Reporting Framework under the hood.
* [Gradle Plugin Android_AspectJX](https://github.com/HujiangTechnology/gradle_plugin_android_aspectjx) - Gradle plugin enabling AspectJ support for Android builds. Documentation is in Chinese but there is no alternatives available around.

### Alexa
[&uarr;](#table-of-contents)
* [Alexa Skills Kit Java SDK](https://github.com/alexa/alexa-skills-kit-sdk-for-java) - SDK kit for developing custom Alexa skills.
* [Alexa Skills Kit Testing Framework](https://github.com/KayLerch/alexa-skills-kit-tester-java) Testing Framework for custom Alexa skills validation.

### Assertions
[&uarr;](#table-of-contents)
* [Assertj](https://github.com/joel-costigliola/assertj-core) - Fluent Assertions for Java
* [Truth](https://github.com/google/truth) - Fluent Assertions from Google
* [Java Hamcrest](https://github.com/hamcrest/JavaHamcrest) - Popular matchers library.

### AWS
[&uarr;](#table-of-contents)
* [AWS SDK Java](https://github.com/aws/aws-sdk-java) - Official Java SDK for controlling Amazon Web Services.
* [AWS Java Sample](https://github.com/aws-samples/aws-java-sample) - Sample project illustrating usage of the AWS SDK for Java.

### BDD
[&uarr;](#table-of-contents)
* [Сucumber JVM](https://github.com/cucumber/cucumber-jvm) - Executable Specification styled testing Framework.
* [Cucumber Java Skeleton](https://github.com/cucumber/cucumber-java-skeleton) - Demo project to get acquainted with Cucumber.
* [Spock](https://github.com/spockframework/spock) - Another popular executable specification framework. Actually tests have to be written in Groovy but is sure worth mentioning.

### Bots
[&uarr;](#table-of-contents)
* [JBot](https://github.com/rampatra/jbot) - Library for creating Slack and Facebook bots
* [Simple Slack Api](https://github.com/Ullink/simple-slack-api) -  Java Slack client library
* [Java Telegram Bot Api](https://github.com/pengrad/java-telegram-bot-api) - Telegram Bot API for Java
* [TelegramBots](https://github.com/rubenlagus/TelegramBots) - Java library to create bots using Telegram Bots API (With some examples).

### Code Coverage
[&uarr;](#table-of-contents)
* [JaCoCo](https://github.com/jacoco/jacoco) - Code Coverage Library.

### Code Security
[&uarr;](#table-of-contents)
* [DependencyCheck](https://github.com/jeremylong/DependencyCheck) - Checks project dependencies for publicly disclosed vulnerabilities.

### Code Quality
[&uarr;](#table-of-contents)
* [Android Check 2](https://github.com/stoyicker/android-check-2) - Static code analysis plugin for Android projects.
* [Error Prone](https://github.com/google/error-prone) - Static analysis tool catching common programming mistakes at compile-time.
* [Gradle Quality Plugin](https://github.com/xvik/gradle-quality-plugin) - Static code analysis for Java and Groovy projects using Checkstyle, PMD, SpotBugs (FindBugs) and CodeNarc.
* [Style Guide](https://github.com/google/styleguide) - Google collection of importable code style configuration files for most popular languages and IDEs.
*  [Qulice](https://github.com/teamed/qulice) - Maven quality control plugin. Qulice [explained](https://www.yegor256.com/2014/08/13/strict-code-quality-control.html).

### CLI
[&uarr;](#table-of-contents)
* [Picocli](https://github.com/remkop/picocli) - Java library for creating command line applications.
* [JCommander](https://github.com/cbeust/jcommander) - Command line parsing framework for Java.

### Configuration and Properties
[&uarr;](#table-of-contents)
* [Config](https://github.com/lightbend/config) - A type-safe configuration library for JVM languages.
* [Owner](https://github.com/lviggiano/owner) - Convenient library for properties handling. Greatly reduces boilerplate.

### Dependency
[&uarr;](#table-of-contents)
* [Dagger 2](https://github.com/google/dagger) - modern and fast DI framework. Can be pretty [useful](https://medium.com/@fabioCollini/android-testing-using-dagger-2-mockito-and-a-custom-junit-rule-c8487ed01b56) for unit testing.
* [DaggerMock](https://github.com/fabioCollini/DaggerMock) - A JUnit rule to easily override Dagger 2 objects.

### Environment
[&uarr;](#table-of-contents)
* [Testcontainers Java](https://github.com/testcontainers/testcontainers-java) - Java 8 library providing lightweight, throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container. Good blog [post](https://zeroturnaround.com/rebellabs/java-integration-testing-with-testcontainers/) on topic.

### ElasticSearch
[&uarr;](#table-of-contents)
* [ElasticSearch REST High Level Client](https://github.com/elastic/elasticsearch/tree/master/client/rest-high-level) - Official Java REST client for managing ElasticSearch instance. Docs are available [here](https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/java-rest-high.html). ES is extremely useful in certain situations, but is known for steep learning curve. Makes sense to start with [videos](https://egghead.io/courses/get-started-with-elasticsearch).
* [Logstash](https://github.com/elastic/logstash) - Part of ELK (ElasticSearch, Logstash, Kibana) logging stack, responsible for transport part.
* [Kibana](https://github.com/elastic/kibana) - Search and Analytics Dashboard for ElasticSearch. Probably it should be in the Tools section, but it's better to keep here with related products.

### I/O
[&uarr;](#table-of-contents)
* [Okio](https://github.com/square/okio) - Popular [Square](http://square.github.io/) library: I/O operations made easy.

### Image Based
[&uarr;](#table-of-contents)
* [SikuliX2](https://github.com/RaiMan/SikuliX2) - massive redesign of popular SikuliX library. Promised to be released in October. So, let in be here, say "in watch list". One of the announced 'killer features' is an option to perform screenshot based testing of mobile apps.
* [Ashot](https://github.com/yandex-qatools/ashot) - Useful library from Yandex for operating screenshots. Screenshot based testing etc.
* [Screenshot Tests For Android](https://github.com/facebook/screenshot-tests-for-android) - Popular screenshot based mobile devices testing solution from Facebook.

### JSON
[&uarr;](#table-of-contents)
* [JSONAssert](https://github.com/skyscreamer/JSONassert) - Library simplifying assertion of Json documents.
* [Moshi](https://github.com/square/moshi) - modern JSON library for Android and Java, works really well with other [Square](http://square.github.io/) libraries.
* [Moshi Lazy Adapters](https://github.com/serj-lotutovici/moshi-lazy-adapters) - A collection of simple JsonAdapters for Moshi.

### HowTo
[&uarr;](#table-of-contents)
* [Java Design Patterns](https://github.com/iluwatar/java-design-patterns) - Extensive collection of Design Pattern examples.

### HTML
[&uarr;](#table-of-contents)
* [Jsoup](https://github.com/jhy/jsoup) - Java library for working with real-world HTML. It provides a very convenient API for extracting and manipulating data. Extremely useful. Works directly with html, without need of WebDriver. In certain cases pairs really well with WebDriver based library, greatly speeding up test execution - especially when it's needed to read huge amount of data from the UI.

### HTTP
[&uarr;](#table-of-contents)
* [OkHttp](https://github.com/square/okhttp) - Popular HTTP client by [Square](http://square.github.io/).
* [Parallec](https://github.com/eBay/parallec) - Lightning fast Parallel Async HTTP/SSH/TCP/UDP/Ping Client Java Library. Allows requesting thousands of remote endpoints, collect results and forward them elsewhere.
* [LoggingInterceptor](https://github.com/dkorobtsov/LoggingInterceptor) My own version of popular Android [library](https://github.com/ihsanbal/LoggingInterceptor) adapted for use with popular Java loggers - basically OkHttp interceptor, with pretty  requests/responses output to console. Useful when writing API tests or developing REST client.
* [Retrofit](https://github.com/square/retrofit) - Type-safe HTTP client for Android and Java by Square. Working with REST API's made easy and simple.
* [Feign](https://github.com/OpenFeign/feign) - Another popular HTTP client library. Quite similar to Retrofit.

### Language extensions
[&uarr;](#table-of-contents)
* [Auto](https://github.com/google/auto) - A collection of source code generators for Java.
* [Lombok](https://github.com/rzwitserloot/lombok) - Annotation processing library, greatly reducing Java boilerplate. Check out list of [features](https://projectlombok.org/features/all).
* [Vavr](https://github.com/vavr-io/vavr) - functional Java 8+ extension, adds some useful features - Scala-like switches, tuples, immutable data structures. Greatly reduces boilerplate.
* [FreeBuilder](https://github.com/inferred/FreeBuilder) - Automatic generation of the Builder pattern.
* [Manifold](https://github.com/manifold-systems/manifold) - yet another Java extension framework. Probably not yet ready for production, but it's definitely in a watchlist. Just check the [demo](https://manifold.systems/images/JsonDemo.mp4) to see some black magic.

### Logging
[&uarr;](#table-of-contents)
* [Log4j2](https://github.com/apache/logging-log4j2) - one of the most popular Java logging frameworks. Endless customization options, though could be a little bit complicated to perform initial configuration.
* [Slf4j](https://github.com/qos-ch/slf4j) - Simple Logging Facade for Java
* [Tinylog](https://github.com/pmwmedia/tinylog) - Minimalistic logging framework for Java and Android.

### Localization
[&uarr;](#table-of-contents)
* [Language Detector](https://github.com/optimaize/language-detector) - Library taking text as input as returning language it was written in. Should admit returns quite a lot of false positives for short strings, but still - extremely useful for fast localization checks.
* [Languagetool](https://github.com/languagetool-org/languagetool) - Style and Grammar Checker supporting 25+ Languages. Check official [docs](https://languagetool.org/dev) for usage details.

### Mobile
[&uarr;](#table-of-contents)
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
[&uarr;](#table-of-contents)
* [jcabi-email](https://github.com/jcabi/jcabi-email) - Email Sending Java SDK.
* [Greenmail](https://github.com/greenmail-mail-test/greenmail) - Mail Testing Library.
* [Gmail API Client Library for Java](https://developers.google.com/api-client-library/java/apis/gmail/v1) Gmail itself can be pretty useful for testing e-mails. Especially combined with + [trick](https://www.thewindowsclub.com/gmail-address-tricks).

### Mocks
[&uarr;](#table-of-contents)
* [JMockit](https://github.com/jmockit/jmockit1) - Library for creating test mocks. Not so famous as Mockito, but definitely just as good. Just a matter of taste which one to choose.
* [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java) - Java bindings for [Hoverfly](https://hoverfly.io/) - proxy for http services simulation. Flexible DSL.
* [Mockito](https://github.com/mockito/mockito) - Most popular Mocking framework for Java
* [MockWebServer](https://github.com/square/okhttp/tree/master/mockwebserver) - OkHttp client own library for mocking web server responses.
* [OkReplay](https://github.com/airbnb/okreplay) - Yet another approach to testing web services. Just record you app network traffic, then replay it in tests. No longer need to worry about 3rd services downtime. NB. Intended for using with OkHTTP client.
* [Spark](https://github.com/perwendel/spark) - Simple Web Framework. Why it's here? Sometimes it's easier and faster to create Web Server then to mock it :)
* [RESTMock](https://github.com/andrzejchm/RESTMock) - HTTP server for Android instrumentation tests. Works on top of MockWebServer, pairs really well with Hamcrest matchers.
* [Wiremock](https://github.com/tomakehurst/wiremock) - Yet another tool for mocking HTTP services.

### Mutation
[&uarr;](#table-of-contents)
* [Pitest aka PIT](https://github.com/hcoles/pitest) - Mutation testing system for Java and the JVM. In short - testing system for unit tests. Modifies your source code and checks if test will fail. If they won't you could be doing something wrong.

### Reflection
[&uarr;](#table-of-contents)
* [Reflections](https://github.com/ronmamo/reflections) - Java runtime metadata analysis.

### Reactive
[&uarr;](#table-of-contents)
* [RxJava](https://github.com/ReactiveX/RxJava) - Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM. Since it's practically a standard in modern Android applications, good no know how to use it. Read "Building a Reactive Mindset" [blog post](https://upday.github.io/blog/reactive_mindset_burgers/) for comprehensive explanation.
* [Awaitility](https://github.com/awaitility/awaitility) - Small Java DSL for testing asynchronous operations.

### Reporting
[&uarr;](#table-of-contents)
* [Allure 2](https://github.com/allure-framework/allure2) Test reports. Good looking, flexible and easy to use. Easily integrates with most of the  popular testing frameworks. Lots of plugins. Looking forward to see a third version. Any bets it will be released at all?
* [Allure Java](https://github.com/allure-framework/allure-java) Collection of small libraries (most of them contains just a single class) to integrate Allure with popular Java frameworks.
* [Report Portal](https://github.com/reportportal/reportportal) Great solution for aggregating all your tests run results into single highly customizable dashboard. Provides good insight on how automated testing projects are doing under the hood. Requires stand alone server, installs as a group of dockerized microservices.

### REST
[&uarr;](#table-of-contents)
* [REST-assured](https://github.com/rest-assured/rest-assured) - Most popular library for REST services testing. Personally however, I prefer Retrofit / OkHttp / Moshi / AssertJ combination. But should admit that both approaches have pros and cons.

### Serverless
[&uarr;](#table-of-contents)
* [Docker In AWS Lambda](https://github.com/vladgolubev/docker-in-aws-lambda) - illustration for [this](https://medium.com/@vladholubiev/how-did-i-hack-aws-lambda-to-run-docker-containers-7184dc47c09b) blog post.
* [Lambda](https://github.com/iron-io/lambda) - Set of tools and libraries for converting Lambdas to Docker images.
* [Lambda-Selenium](https://github.com/blackboard/lambda-selenium)  - Demo project, displaying how to run Selenium tests using AWS Lambda
* [Lambdium](https://github.com/smithclay/lambdium) - yet another library for running webdriver tests in AWS Lambda

### SSH
[&uarr;](#table-of-contents)
* [JSch](https://github.com/is/jsch) - Java SSH interface. Allows to manage remote *nix servers programmatically.

### Source Code Utilities
[&uarr;](#table-of-contents)
* [Javapoet](https://github.com/square/javapoet) - Library with fluent interface for generating .java files.

### SQL
[&uarr;](#table-of-contents)
* [jdbi](https://github.com/jdbi/jdbi) - Jdbi provides convenient, idiomatic access to relational databases in Java.
* [Requery](https://github.com/requery/requery) - Modern SQL based query & persistence for Java / Kotlin / Android.
* [RxJava JDBC](https://github.com/davidmoten/rxjava-jdbc) - Efficient execution and functional composition of database calls using JDBC and RxJava Observables.
* [SQLDelight](https://github.com/square/sqldelight) - Generates Java models from CREATE TABLE statements.

### Telephony
[&uarr;](#table-of-contents)
* [Asterisk REST Interface](https://github.com/l3nz/ari4java) -  [Asterisk](https://www.asterisk.org/) ARI interface bindings for Java.
* [Twilio Java](https://github.com/twilio/twilio-java) - Way to go if you up to SMS and calling automation. But be ready to pay.
* [Libphone Number](https://github.com/googlei18n/libphonenumber) - Google's common Java, C++ and JavaScript library for parsing, formatting, and validating international phone numbers.

### Text Utilities
[&uarr;](#table-of-contents)
* [Apache Commons Text](https://github.com/apache/commons-text) - Collection of utils for working with strings. May be a little bit unexpected library in this list, but in almost every project I've seen there is own string utilities collection doing mostly same things.
* [JUnidecode](https://github.com/gcardone/junidecode) - Pretty useful library for handling text in exotic locales.

### Test Data
[&uarr;](#table-of-contents)
* [Fabricator](https://github.com/azakordonets/fabricator) - Fake data generator.
* [Java Faker](https://github.com/DiUS/java-faker) - Another useful library for fake Test Data generation.
* [SecLists](https://github.com/danielmiessler/SecLists) - Security tester's companion. It's a collection of multiple types of lists used during security assessments, collected in one place. Check big list of naughty strings!
* [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) - Library for injecting reproducible random data to unit tests. Heavily used by [Elastic](https://www.elastic.co/guide/en/elasticsearch/reference/current/randomized-testing.html) for ElasticSearch testing.

### xUnit Framework
[&uarr;](#table-of-contents)
* [JUnit4](https://github.com/junit-team/junit4) - Good old JUnit. In general there is no big difference at the moment which one to choose - JUnit4, JUnit or TestNG. Mostly it's a matter of taste.
* [JUnitParams](https://github.com/Pragmatists/JUnitParams) - JUnit4 extension for creating parameterised tests.
* [JUnit5](https://github.com/junit-team/junit5) - Next generation of JUnit with some interesting features.
* [Mastering JUnit5](https://github.com/bonigarcia/mastering-junit5) - Collection of code examples displaying how to use new JUnit5 features.
* [Test Data Supplier](https://github.com/sskorol/test-data-supplier) - Extended version of TestNG DataProvider.

### WebDriver
[&uarr;](#table-of-contents)
* [Selenide](https://github.com/codeborne/selenide) - Best UI testing library. Period. Technically it's a wrapper over Selenium, but who writes tests using pure Selenium nowadays? Check [wiki](https://github.com/codeborne/selenide/wiki/Selenide-vs-Selenium) for general comparison.
* [Selenium](https://github.com/SeleniumHQ/selenium) - Testing framework for web applications. Understanding how in works is a must since it's under the hood in almost all modern UI testing libraries, but keep in mind that writing tests with pure Selenium will be much slower because of the boilerplate.
* [Selenoid](https://github.com/aerokube/selenoid) - Modern library for running browsers within containers, Selenium Hub successor.
* [Selenoid UI](https://github.com/aerokube/selenoid-ui) - Graphical user interface for Selenoid project.
* [Go Grid Router](https://github.com/aerokube/ggr) - Load balancer for Selenium clusters.
* [WebDriver Manager](https://github.com/bonigarcia/webdrivermanager) - Automatic management of Selenium WebDriver binaries. NB: If you are using Selenide - don't bother looking at this library, it's already included under the hood.
* [Browsermob Proxy](https://github.com/lightbody/browsermob-proxy) utility to help web developers watch and manipulate network traffic from their AJAX applications. NB: In scope of UI tests since version [4.11](http://selenide.org/2018/04/02/selenide-4.11/) it's possible to use Selenide own proxy which is using Browsermob under the hood.
* [Video Recorder Java](https://github.com/SergeyPirogov/video-recorder-java) - Library for UI test execution process video recording. Just add some annotations, simple as that.

### XML
[&uarr;](#table-of-contents)
- [JAXB Converter](https://github.com/square/retrofit/tree/master/retrofit-converters/jaxb) - Retrofit Converter for serialization to and from XML.
- [XML Unit](https://github.com/xmlunit/xmlunit) - XML testing library.
