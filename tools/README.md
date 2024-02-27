# Automation Arsenal - Tools

---

## [Table of Contents](#table-of-contents)
- [Automation Arsenal](https://github.com/dkorobtsov/automation-arsenal#table-of-contents)
  - [Java Libraries](https://github.com/dkorobtsov/automation-arsenal/tree/master/java#table-of-contents)
  - [Kotlin Libraries](https://github.com/dkorobtsov/automation-arsenal/tree/master/kotlin#table-of-contents)
  - [Tools](#tools)
  	- [API](#api)
  	- [API Testing](#api-testing)
  	- [Build Tools](#build-tools)
  	- [Artifacts Handling](#artifacts-handling)
  	- [Certificates](#certificates)
  	- [CI / CD](#ci--cd)
  	- [Code Coverage](#code-coverage)
  	- [Code Quality](#code-quality)
  	- [Console](#console)
  	- [Chrome Extensions](#chrome-extensions)
  	- [Containers](#containers)
  	- [Database](#database)
  	- [ElasticSearch](#elk)
  	- [Git](#git)
  	- [Goodies](#goodies)
  	- [IDE](#ide)
  	- [IntelliJ Plugins](#intellij-plugins)
  	- [JSON](#json)
  	- [HTTP](#http)
  	- [Logging](#logging)
  	- [Mail](#mail)
  	- [Mobile](#mobile)
  	- [Monitoring](#monitoring)
  	- [Performance Testing](#performance-testing)
  	- [Profiling](#profiling)
  	- [Provisioning](#provisioning)
  	- [Remote Management](#remote-management)
  	- [Test Reporting](#test-reporting)
  	- [Test Data](#test-data)
  	- [Team Collaboration](#team-collaboration)
  	- [Triggers](#triggers)
  	- [Web Testing](#web-testing)
  - [Cheat Sheets](https://github.com/dkorobtsov/automation-arsenal/tree/master/resources#cheat-sheets)
  - [Reading](https://github.com/dkorobtsov/automation-arsenal/tree/master/resources#reading)
  - [Events](https://github.com/dkorobtsov/automation-arsenal/tree/master/resources#events)
  - [Video](https://github.com/dkorobtsov/automation-arsenal/tree/master/resources#video)

---

## Tools

### API
[&uarr;](#table-of-contents)
* [Google API Explorer](https://developers.google.com/apis-explorer/#p/) - Explorer for APIs provided by Google.
* [Swagger](https://swagger.io/) - Way to go when designing API.
* [Programmable Web](https://www.programmableweb.com/apis/directory) - Largest API Directory on the Web. To answer typical question - if there are any sandboxes for API testing practice. Any public API will do. :)

### API Testing
[&uarr;](#table-of-contents)
* [Swagger Code Generator](https://github.com/swagger-api/swagger-codegen) - Tool to generate API clients and server stubs in different languages by parsing OpenAPI / Swagger definition.
* [Open Api Generator](https://github.com/OpenAPITools/openapi-generator) - Community fork of Swagger Codegen. Not a big difference at the moment, but this one looks more promising.
* [Postman](https://www.getpostman.com/) One of the best tools available for working with API.
* [All things Postman](https://github.com/DannyDainton/All-Things-Postman) - Api testing with Postman - quick start with examples.

### Build Tools
[&uarr;](#table-of-contents)
* [Gradle](https://gradle.org/) - New projects tend to use Gradle. Flexible configuration DSL.
* [Maven](https://maven.apache.org/) - Most widely used build tool at the moment.
* [Mainframer](https://github.com/buildfoundation/mainframer) - Tool for remote builds. Sync project to remote machine, execute command, sync back.

### Artifacts Handling
[&uarr;](#table-of-contents)
* [Artifact Listener](https://www.artifact-listener.org/) - Get notified when followed library gets an update.
* [Dependabot](https://dependabot.com/) - Useful tool for handling GitHub repository dependencies.
* [Gradle, Please](https://gradleplease.appspot.com/#selenide) - Nice little tool to search for Gradle dependencies.
* [Maven Central](http://search.maven.org/) - Search engine for Maven Central repository.

### Certificates
[&uarr;](#table-of-contents)
* [Mkcert](https://github.com/FiloSottile/mkcert) - A simple zero-config tool to make locally trusted development certificates with any names you'd like.

### CI / CD
[&uarr;](#table-of-contents)
* [Fastlane](https://github.com/fastlane/fastlane) - The easiest way to automate building and releasing iOS and Android apps.
* [Gaia](https://github.com/gaia-pipeline/gaia) - Tool for building pipelines in any programming language. Currently Alpha, but makes sense to keep it on watchlist.
* [Hygieia](https://github.com/capitalone/Hygieia) - Customizable DevOps console - to put all data like Static Code Analysis, Unit and E2E test results, Deployment status etc. in one place.
* [Jenkins](https://jenkins.io/) - Most popular CI Server at the moment.
* [Jenkins Job DSL plugin](https://github.com/jenkinsci/job-dsl-plugin) - A Groovy DSL for Jenkins Jobs.
* [Rultor](https://github.com/yegor256/rultor) - Code merging bot.
* [Snyk](https://github.com/snyk/snyk) - CLI and build-time tool to find & fix known vulnerabilities in open-source dependencies
* [Travis CI](https://travis-ci.org/) - Out of the box CI solution for GitHub hosted projects.
* [Webhook](https://github.com/adnanh/webhook) - Lightweight webserver with configurable webhooks. Allows to execute shell commands on remote servers.
* [Wercker](http://www.wercker.com) - Cloud CI solution from Oracle. Easily integrates with GitHub. Free plan is limited to 2 simultaneous builds.

### Code Coverage
[&uarr;](#table-of-contents)
* [Coveralls](https://coveralls.io/) - Code coverage solution. Free for open source projects.

### Code Quality
[&uarr;](#table-of-contents)
* [AET](https://github.com/Cognifide/aet) - Automated Exploratory Testing - detects changes on web sites and performs basic page health check. Haven't tried it myself yet, but looks interesting.
* [Diffy](https://github.com/twitter/diffy) - Tool for finding potential bugs by running old and new code versions side by side.
* [Infer](https://github.com/facebook/infer) - A static analyzer for Java, C, C++, and Objective-C by Facebook.
* [SonarQube](https://github.com/SonarSource/sonarqube) - Continuous quality inspection.
* [SonarCloud](https://sonarcloud.io) - Basically, SonarQube as a service. Free for open source projects.

### Console
[&uarr;](#table-of-contents)
* [Brew](https://github.com/Homebrew/brew) - Command line package manager for MacOS.
* [iTerm2](https://www.iterm2.com/features.html) - MacOS terminal with lots of useful features.
* [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) - Open source, community-driven framework for managing zsh configuration. Check [this](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) article for installation guide and some useful links.
* [Powerline Shell](https://github.com/b-ryan/powerline-shell) - Popular prompt generator for Bash, ZSH, Fish, and tcsh:
* [Scoop](https://github.com/lukesampson/scoop) - A command-line installer for Windows. Works similar to Brew in MacOS.
* [The Fuck](https://github.com/nvbn/thefuck) - Small handy utility which corrects your previous console command.

### Chrome extensions
[&uarr;](#table-of-contents)
* [AndroidSDKSearchExtension](https://github.com/romannurik/AndroidSDKSearchExtension) - A Chrome extension that adds an 'ad' omnibox command and view source links for the Android SDK.
* [Bug Magnet](https://github.com/gojko/bugmagnet) - Browser assistant for web pages manual testing.
* [ChroPath](https://chrome.google.com/webstore/detail/chropath/ljngjbnaijcbncmcnjfhigebomdlkcjo?hl=en) - Chrome Dev panel extension for working with Selenium locators. Pretty useful.
* [Jedi](https://github.com/sbtqa/Jedi) - Chrome plugin for Page Objects auto generation.
* [Json Viewer](https://github.com/tulios/json-viewer) - Convenient Chrome extension for printing JSON files.
* [OctoLinker](https://github.com/OctoLinker/OctoLinker) - Converts language-specific module-loading statements like include, require or import into links.
* [OctoTree](https://github.com/ovity/octotree) - Adds easy to use navigation to Github. Must have for open source contributors.

### Containers
[&uarr;](#table-of-contents)
* [Docker](https://www.docker.com/) - De facto standard for apps execution in containers.
* [Docker Traffic Control](https://github.com/lukaszlach/docker-tc) - Network rate limiting, emulating delays, losses, duplicates, corrupts and reorders of network packets using only container labels or a command-line interface.
* [Dive](https://github.com/wagoodman/dive) - A tool for exploring a Docker image, layer contents, and discovering ways to shrink image size.
* [Kubernetes](https://github.com/kubernetes/kubernetes) - Production-Grade Container Scheduling and Management.
* [Kubernetes clusters for the hobbyist](https://github.com/hobby-kube/guide) - This guide answers the question of how to setup and operate a fully functional, secure Kubernetes cluster on a cloud provider such as Hetzner Cloud, DigitalOcean or Scaleway. 
* [Minicube](https://github.com/kubernetes/minikube) - Tool that makes it easy to run Kubernetes locally.

### Database
[&uarr;](#table-of-contents)
* [FlyWay](https://github.com/flyway/flyway) - Database Migrations Made Easy.
* [Liquibase](https://github.com/liquibase/liquibase) - Basically Source Code Control for Databases.

### ELK
[&uarr;](#table-of-contents)
* [Beats](https://github.com/elastic/beats) - Lightweight shippers for sending operational data to Elasticsearch, either directly or via Logstash, so it can be visualized with Kibana.
* [Logstash](https://github.com/elastic/logstash) - Part of ELK (ElasticSearch, Logstash, Kibana) logging stack, responsible for transport part.
* [Kibana](https://github.com/elastic/kibana) - Search and Analytics Dashboard for ElasticSearch.
* [Rally](https://github.com/elastic/rally) - Benchmarking framework for Elasticsearch.

### Git
[&uarr;](#table-of-contents)
* [Git](https://github.com/git/git) - Obviously should be in the list.
* [Sourcetree](https://www.sourcetreeapp.com/) - Convenient VCS client from Atlassian with git, subversion (via git-svn) and mercurial support. Configuration for work with hosted GitLab instance can be a little bit tricky.
* [GitKraken](https://www.gitkraken.com/) - Awesome VCS client. NB: Hosted GitLab repositories are supported in paid version only.

### Goodies
[&uarr;](#table-of-contents)
* [Atom](https://github.com/atom/atom) - Highly customizable text editor.
* [Coggle](https://coggle.it/) - Convenient tool for creating mindmaps.
* [Gif For Cli](https://github.com/google/gif-for-cli) - Library by Google for converting gifs or small videos to ASCII animations.
* [Kali](https://www.kali.org/) - Linux distribution with pre-installed collection of pentesting tools.
* [Logoly](https://github.com/bestony/logoly) - A Pornhub Flavour Logo Generator (easily generates website logos).
* [Mimic](https://github.com/reinderien/mimic) - [ab]using Unicode to create tragedy (basically corrupts source code by replacing random chars with unicode analogues).
* [Phone Number Parser](https://libphonenumber.appspot.com/) - Small utility for phone numbers validation. Utilizing [Libphonenumber](https://github.com/googlei18n/libphonenumber) library.
* [Shodan](https://www.shodan.io/) - Search engine for Internet of Things. Never know you can find.
* [Sourcerer App](https://github.com/sourcerer-io/sourcerer-app) - Developer profile generation tool. Consumes git or GitHub repositories and returns full overview of languages and technologies used. Check [example](https://sourcerer.io/dkorobtsov).
* [Toggl](https://toggl.com/) - Excellent time management tool.
* [Zuppit](https://zuppit.co.uk/) - Free tool for website availability monitoring.

### IDE
[&uarr;](#table-of-contents)
* [IntelliJ IDEA](https://www.jetbrains.com/idea/download) - Best Java IDE. For testing purposes Community Edition is more then enough.
* [Gradle IntelliJ Plugin](https://github.com/JetBrains/gradle-intellij-plugin) - Plugin for building plugins for IntelliJ IDEs. Adds several Gradle tasks simplifying IntelliJ plugins development and testing.

### IntelliJ Plugins
[&uarr;](#table-of-contents)
* [Advanced Java Folding](https://plugins.jetbrains.com/plugin/9320-advanced-java-folding) This plugin extends the IDE’s folding features to emulate some of these modern languages’ features helping fight verbosity. In other words - after applying this plugin you Java code will look like mix of Scala, Groovy and Kotlin.
* [Awesome Console](https://github.com/anthraxx/intellij-awesome-console) - Open source, file and url links right from console.
* [AWS Toolkit](https://github.com/aws/aws-toolkit-jetbrains) - AWS Toolkit for JetBrains - a plugin for interacting with AWS from JetBrains IDEs.
* [Docker Integration](https://www.jetbrains.com/help/idea/docker.html) - Work with Docker from IDE.
* [Grep Console](https://github.com/krasa/GrepConsole) - Convenient console logs filtering.
* [Infinitest](https://github.com/infinitest/infinitest) - (Eclipse/IntelliJ) IDE Plugin for TDD Jedi's. Basically it detects changes in class and runs related unit tests. TDD assistant, so to say.
* [IntelliJ KeyPromoter X](https://github.com/halirutan/IntelliJ-Key-Promoter-X) - Plugin assisting to learn IDE shortcuts. Can be very annoying, I know.
* [.gitignore](https://github.com/hsz/idea-gitignore) - Git ignore support.
* [JsonToKotlinClass](https://github.com/wuseal/JsonToKotlinClass) - Plugin for Android Studio And IntelliJ Idea to generate Kotlin data class code from JSON text
* [Lombok Support](https://github.com/mplushnikov/lombok-intellij-plugin) - IntelliJ Lombok plugin.
* [Markdown Navigator](https://github.com/vsch/idea-multimarkdown) - Markdown support. Adds markdown editor to IDE.
* [Statistic](https://plugins.jetbrains.com/plugin/4509-statistic) - Shows project statistic.
* [String Manipulation](https://github.com/krasa/StringManipulation) - Adds String manipulation options to right click menu

### JSON
[&uarr;](#table-of-contents)
* [Json Schema 2 Pojo](https://github.com/joelittlejohn/jsonschema2pojo) - Extremely useful tool for quickly consuming an API. Just copy and [paste](http://www.jsonschema2pojo.org/) response, get Java class, attach convertor (like Moshi for example) and get an object on a next Retrofit call.

### HTTP
[&uarr;](#table-of-contents)
* [HTTP Status](http://httpstat.us/) - Simple service for generating different HTTP response codes. Can be useful for quick scripts validation.
* [HTTP Bin](https://github.com/postmanlabs/httpbin) - A simple HTTP Request & Response Service. Can be useful for HTTP client testing.
* [Bad SSL](https://badssl.com/) - Convenient service for testing various SSL certificate problems. 

### Logging
[&uarr;](#table-of-contents)
* [Greylog 2](https://github.com/Graylog2/graylog2-server) - Free and open source log management.
* [LogViewer](https://github.com/satyagraha/logviewer) - Browser based client for reading logs from most commonly used web servers.
* [Loki](https://github.com/grafana/loki) - Log aggregation system inspired by Prometheus. 

### Mail
[&uarr;](#table-of-contents)
* [Inbucket](https://github.com/jhillyerd/inbucket) - Email testing service; it will accept messages for any email address and make them available via web, REST and POP3.
* [MailHog](https://github.com/mailhog/MailHog) - MailHog is an email testing tool for developers. 

### Mobile
[&uarr;](#table-of-contents)
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

### Monitoring
[&uarr;](#table-of-contents)
* [Grafana](https://github.com/grafana/grafana) - The tool for monitoring and metric analytics & dashboards for Graphite, InfluxDB & Prometheus & More
* [Telegraf](https://github.com/influxdata/telegraf) - The plugin-driven server agent for collecting & reporting metrics. 

### Performance Testing
[&uarr;](#table-of-contents)
* [Gatling](https://github.com/gatling/gatling) - Popular tool for Performance testing. Written in Scala. Read "The Art Of Destroying Your App With Gatling" blog [post](https://gatling.io/2018/03/07/the-art-of-destroying-your-web-app/) on official website.
* [Gatling Gradle plugin](https://github.com/lkishalmi/gradle-gatling-plugin) - Gatling Plugin for Gradle.
* [Gatling Real-Time Monitoring Example](https://github.com/marufaytekin/gatling-grafana-influxdb) - Gatling real time monitoring with Grafana, InfluxDB and Graphite.
* [Yandex Tank](https://github.com/yandex/yandex-tank) - Load and performance benchmark tool from Yandex (includes backend analytics services: [Overload](https://overload.yandex.net/login/?next=/)).
* [Yellow Lab Tools](https://github.com/gmetais/YellowLabTools/) - Great open source tool for auditing web pages.
* [k6](https://github.com/loadimpact/k6) - Another popular load testing tool, using Go and JavaScript.
* [Locust](https://github.com/locustio/locust) - Scalable user load testing tool written in Python.
* [Performance Testing Framework](https://github.com/serputko/performance-testing-framework) - Ready to use performance testing solution example.
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library.
* [wrk](https://github.com/wg/wrk) - Modern HTTP benchmarking tool.

### Profiling
[&uarr;](#table-of-contents)
* [FlameViewer](https://github.com/kornilova-l/FlameViewer) - Tool for Flame Graphs visualization and Java instrumentation profiler (for IntelliJ IDEA).
* [Java Flame Graphs](https://github.com/cykl/hprof2flamegraph) - Flame Graph visualization for Java (HPROF, Honest-profiler). More information about Flame Graphs can be found [here](http://www.brendangregg.com/flamegraphs.html).

### Provisioning
* [Ansible](https://github.com/ansible/ansible) - IT automation system. Handles configuration-management, application deployment, cloud provisioning, ad-hoc task-execution, and multinode orchestration.
* [Ansible Best Practices](https://github.com/enginyoyen/ansible-best-practises) - A project structure that outlines some best practises of using Ansible
* [Ansible Semaphore](https://github.com/ansible-semaphore/semaphore) - Open source Web UI solution for launching Ansible tasks.
* [Ansible Examples](https://github.com/ansible/ansible-examples) - A few starter examples of Ansible playbooks, to show features and how they work together.
* [Terraform](https://github.com/hashicorp/terraform) - Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently.
* [Vagrant](https://github.com/hashicorp/vagrant) - Vagrant is a tool for building and distributing development environments.

### Remote Management
[&uarr;](#table-of-contents)
* [Royal TS](https://www.royalapplications.com/ts/mac/features) - Awesome Remote Management Solution. Supports RDC, SSH, FTP etc. Free to use for up to 10 connections.

### Test Reporting
[&uarr;](#table-of-contents)
* [Allure 2](https://github.com/allure-framework/allure2) - Test reports. Good looking, flexible and easy to use. Easily integrates with most of the  popular testing frameworks. Lots of plugins. Looking forward to see a third version. Any bets it will be released at all?
* [Report Portal](https://github.com/reportportal/reportportal) - Great solution for aggregating all your test run results into single highly customizable dashboard. Provides good insight on how automated testing projects are doing under the hood. Requires stand-alone server, installs as a group of dockerized microservices.
* [Zafira](https://github.com/qaprosoft/zafira) - Yet another test reporting solution. Haven't tried it myself yet, but project looks promising.
* [Testomat.io](https://testomat.io/) - Modern TCMS allows sync the manual and automated tests in one place. Real-time reporting. Rich analytics dashboard with value testing metrics.

### Team Collaboration
[&uarr;](#table-of-contents)
* [Instant Terminal Sharing](https://tmate.io/) - Can be useful in certain situations.
* [Recordit](http://recordit.co/) - Nice little tool for recording and sharing screencasts.

### Test Data
[&uarr;](#table-of-contents)
* [GoReplay](https://github.com/buger/goreplay) - Network monitoring tool which can record live traffic, and use it for shadowing, load testing, monitoring and detailed analysis.
* [StreamSets](https://github.com/streamsets/datacollector) - Data migration Library, but can also be used for Test Data Sets generation.

### Triggers
[&uarr;](#table-of-contents)
* [Huginn](https://github.com/huginn/huginn) - Create agents that monitor and act on your behalf. Hackable self-hosted version of IFTTT on Steroids.
* [StackStorm](https://github.com/StackStorm/st2) - Aka "IFTTT for Ops". StackStorm is a platform for integration and automation across services and tools with a particular focus on taking actions in response to events.

### Web Testing
[&uarr;](#table-of-contents)
* [Selenium IDE](https://github.com/SeleniumHQ/selenium-ide) - New Life of Selenium IDE UI tests record and playback tool.
* [HAR Viewer](http://www.softwareishard.com/blog/har-viewer/) - Online tool for HTTP Archive files visualization
* [UI Testing Playground](https://the-internet.herokuapp.com/) - Good for practicing UI automation techniques.

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
