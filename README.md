# Automation Arsenal
---
**What is the purpose of this list?**
> To gather in one place up-to-date list of popular **Java** and **Kotlin** frameworks, libraries and tools directly (on indirectly) related to software testing, quality assurance and adjacent processes automation. Basically speaking everything related to [engineering productivity](https://saucelabs.com/blog/qa-is-not-enough-you-need-to-engineer-productivity).

**Why?**
> First of all - to have reference to all commonly used modern tools (and not so obvious things that can be handy or just good to know) in one place. Because it usually takes a little bit more then general Selenium knowledge to build reliable and flexible automated testing infrastructure. Another reason was to provide some guidance to those who are at the beginning of their journey - so categories are as focused as possible, keeping dead and 'vintage' libraries out of scope.

**Find this list helpful? Show some support:**
>![GitHub followers](https://img.shields.io/github/followers/dkorobtsov.svg?style=social&label=Follow)
[![GitHub forks](https://img.shields.io/github/forks/dkorobtsov/automation-arsenal.svg?style=social&label=Fork)](https://github.com/dkorobtsov/automation-arsenal/fork)
[![GitHub stars](https://img.shields.io/github/stars/dkorobtsov/automation-arsenal.svg?style=social&label=Star)](https://github.com/dkorobtsov/automation-arsenal)
[![Twitter Follow](https://img.shields.io/twitter/follow/dkorobtsov.svg?style=social&label=Follow)](https://twitter.com/dkorobtsov)

---

# [Table of Contents](#table-of-contents)
- [Automation Arsenal](#table-of-contents)
	- [Java Libraries](https://github.com/dkorobtsov/automation-arsenal/tree/master/java#table-of-contents)
	- [Kotlin Libraries](https://github.com/dkorobtsov/automation-arsenal/tree/master/kotlin#table-of-contents)
	- [Tools](#tools)
		- [API](#api)
		- [Build Tools](#build-tools)
		- [Artifacts Handling](#artifacts-handling)
		- [CI /](#ci-)
		- [Code Coverage](#code-coverage)
		- [Code Quality](#code-quality)
		- [Console](#console)
		- [Chrome extensions](#chrome-extensions)
		- [Containers](#containers)
		- [Git](#git)
		- [Goodies](#goodies)
		- [IDE](#ide)
		- [IntelliJ Plugins](#intellij-plugins)
		- [JSON](#json)
		- [Logging](#logging)
		- [Mobile](#mobile)
		- [Performance Testing](#performance-testing)
		- [Remote Management](#remote-management)
		- [Team](#team)
		- [Testing](#testing)
	- [Cheat Sheets](#cheat-sheets)
	- [Reading](#reading)
		- [General principles](#general-principles)
		- [Practical advices](#practical-advices)
		- [Must Read Books](#must-read-books)
		- [Useful Read](#useful-read)
	- [Events](#events)

---

## Tools

### API
[&uarr;](#table-of-contents)
* [Google API Explorer](https://developers.google.com/apis-explorer/#p/) - Explorer for APIs provided by Google.
* [Swagger](https://swagger.io/) - Way to go when designing APIs.
* [Postman](https://www.getpostman.com/) One of the best tools available for working with API.
* [Programmable Web](https://www.programmableweb.com/apis/directory) - Largest API Directory on the Web. To answer typical question - if there are any sandboxes for API testing practice. Any public API will do. :)

### Build Tools
[&uarr;](#table-of-contents)
* [Gradle](https://gradle.org/) - New projects tend to use Gradle. Flexible configuration DSL.
* [Maven](https://maven.apache.org/) - Most widely used build tool at the moment.

### Artifacts Handling
[&uarr;](#table-of-contents)
* [Artifact Listener](https://www.artifact-listener.org/) - Get notified when followed library gets an update.
* [Gradle, Please](https://gradleplease.appspot.com/#selenide) - Nice little tool to search for Gradle dependencies.
* [Maven Central](http://search.maven.org/) - Search engine for Maven Central repository.

### CI /
[&uarr;](#table-of-contents)
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
[&uarr;](#table-of-contents)
* [Coveralls](https://coveralls.io/) - Code coverage solution. Free for open source projects.

### Code Quality
[&uarr;](#table-of-contents)
* [Diffy](https://github.com/twitter/diffy) - Tool for finding potential bugs by running old and new code versions side by side.
* [SonarQube](https://github.com/SonarSource/sonarqube) - Continuous quality inspection.
* [SonarCloud](https://sonarcloud.io) - Basically, SonarQube as a service. Free for open source projects.

### Console
[&uarr;](#table-of-contents)
* [Brew](https://github.com/Homebrew/brew) - Command line package manager for MacOS.
* [iTerm2](https://www.iterm2.com/features.html) - MacOS terminal with lots of useful features.
* [Powerline Shell](https://github.com/b-ryan/powerline-shell) - Popular prompt generator for Bash, ZSH, Fish, and tcsh:
* [Scoop](https://github.com/lukesampson/scoop) - A command-line installer for Windows. Works similar to Brew in MacOs.
* [The Fuck](https://github.com/nvbn/thefuck) - Small handy util which corrects your previous console command.

### Chrome extensions
[&uarr;](#table-of-contents)
* [AndroidSDKSearchExtension](https://github.com/romannurik/AndroidSDKSearchExtension) - A Chrome extension that adds an 'ad' omnibox command and view source links for the Android SDK.
* [Bug Magnet](https://github.com/gojko/bugmagnet) - Browser assistant for web page manual testing.
* [ChroPath](https://chrome.google.com/webstore/detail/chropath/ljngjbnaijcbncmcnjfhigebomdlkcjo?hl=en) - Chrome Dev panel extension for working with Selenium locators. Pretty useful.
* [Json Viewer](https://github.com/tulios/json-viewer) - Convenient Chrome extension for printing JSON files.

### Containers
[&uarr;](#table-of-contents)
* [Docker](https://www.docker.com/) - De facto standard for apps execution in containers.

### Git
[&uarr;](#table-of-contents)
* [Git](https://github.com/git/git) - Obviously should be in the list.
* [Sourcetree](https://www.sourcetreeapp.com/) - Convenient VCS client from Atlassian with git, subversion (via git-svn) and mercurial support. Configuration for work with hosted Gitlab instance can be a little bit tricky.
* [GitKraken](https://www.gitkraken.com/) - Awesome VCS client. Hosted GitLab repositories are supported in paid version only.

### Goodies
[&uarr;](#table-of-contents)
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
[&uarr;](#table-of-contents)
* [IntelliJ IDEA](https://www.jetbrains.com/idea/download) - Best Java IDE. For testing purposes Community Edition is more then enough.

### IntelliJ Plugins
[&uarr;](#table-of-contents)
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
* [String Manipulation](https://github.com/krasa/StringManipulation) - Adds String manipulation options to right click menu

### JSON
[&uarr;](#table-of-contents)
* [Json Schema 2 Pojo](https://github.com/joelittlejohn/jsonschema2pojo) - Extremely useful tool for quickly consuming an API. Just copy and [paste](http://www.jsonschema2pojo.org/) response, get Java class, attach convertor (like Moshi for example) and get an object on a next Retrofit call.

### Logging
[&uarr;](#table-of-contents)
* [LogViewer](https://github.com/satyagraha/logviewer) - Browser based client for reading logs from most commonly used web servers.

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

### Performance Testing
[&uarr;](#table-of-contents)
* [Gatling](https://github.com/gatling/gatling) - Popular tool for Performance testing. Written in Scala. Read "The Art Of Destroying Your App With Gatling" blog [post](https://gatling.io/2018/03/07/the-art-of-destroying-your-web-app/) on official website.
* [Yellow Lab Tools](https://github.com/gmetais/YellowLabTools/) - Great open source tool for auditing web pages.

### Remote Management
[&uarr;](#table-of-contents)
* [Royal TS](https://www.royalapplications.com/ts/mac/features) - Awesome Remote Management Solution. Supports RDC, SSH, FTP etc. Free to use for up to 10 connections.

### Team
[&uarr;](#table-of-contents)
* [Instant Terminal Sharing](https://tmate.io/) - Can be useful in certain situations.
* [Recordit](http://recordit.co/) - Nice little tool for recording and sharing screencasts.

### Testing
[&uarr;](#table-of-contents)
* [HAR Viewer](http://www.softwareishard.com/blog/har-viewer/) - Online tool for HTTP Archive files visualization
* [XPath Generation](http://xpathify.herokuapp.com/) - Small web utility for XPath generation.
* [UI Testing Playground](https://the-internet.herokuapp.com/) - Good for practicing UI automation techniques.

---

## Cheat Sheets
[&uarr;](#table-of-contents)
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

---

## Reading

### General principles
[&uarr;](#table-of-contents)
* [DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself) - Don't repeat yourself. Say no to code duplication.
* [YAGNI](https://testing.googleblog.com/2017/08/code-health-eliminate-yagni-smells.html) - You aren't gonna need it. Implement only features you actually need. Delete all code that is not in use.
* [KISS](https://people.apache.org/~fhanik/kiss.html) - Keep it simple, Stupid. Keep code as simple as possible.
* [SOLID](https://en.wikipedia.org/wiki/SOLID) - Five design principles to make code more understandable, flexible and maintainable.

### Practical advices
[&uarr;](#table-of-contents)
* [Fluent Interface](https://www.martinfowler.com/bliki/FluentInterface.html) - Fluent Interfaces explained. Consider it as one of the building blocks when creating internal testing DSL.
* [Reduce Nesting](https://testing.googleblog.com/2017/06/code-health-reduce-nesting-reduce.html) - Good example how to reduce nesting and improve readability.
* [Tell Don't Ask Principle](https://martinfowler.com/bliki/TellDontAsk.html) - Useful article from Martin Fowler. Could be really helpful when designing Page Object Model.
* [To Comment or Not to Comment?](https://testing.googleblog.com/2017/07/code-health-to-comment-or-not-to-comment.html) - Article about comments in code.

### Must Read Books
[&uarr;](#table-of-contents)
* [Clean Code](https://www.goodreads.com/book/show/3735293-clean-code) by Uncle Bob. Must read. Period. Badly written code is a total mess. At certain point maintenance will consume all the time you have.
* [xUnit Test Patterns: Refactoring Test Code](https://www.goodreads.com/book/show/337302.xUnit_Test_Patterns) by Gerard Meszaros. Bible of unit testing. Same principles are applicable to any automated tests. Another must read.

### Useful Read
[&uarr;](#table-of-contents)
* [Android Testing Guide](https://github.com/ravidsrk/android-testing-guide) - Worth reading, pretty good guide.
* [Google Testing Blog](https://testing.googleblog.com/) - Google Testing Blog. Quite a few updates recently, but in general lots of useful ideas. In general makes also sense to read "[How Google Tests Software](https://books.google.com/books/about/How_Google_Tests_Software.html?id=vHlTOVTKHeUC)" - some ideas are really useful.
* [Java 8 Tutorial](https://github.com/winterbe/java8-tutorial) - Pretty good guide for Java 8 features.
* [Software Testing Anti-patterns](http://blog.codepipes.com/testing/software-testing-antipatterns.html) - Just good article. Makes sense to read.
* [Test Smells](http://xunitpatterns.com/Test%20Smells.html) - Parts of the book xUnit Test Patterns. Most of the presentations explaining bad test design are just an illustration of this list.
* [Yegor's Blog](https://www.yegor256.com/) - Always a good read.


## Events
[&uarr;](#table-of-contents)
* [Software Testing Conferences](https://testingconferences.org/) - Live calendar for incoming Software testing conferences.
* [IT Conference Top](https://itconference.top/) - Best Developer Conferences to attend in Europe.
