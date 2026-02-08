# Awesome Java [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

A curated list of awesome Java frameworks, libraries and software.

[Please find a different kind of layout here](https://github.com/akullpp/awesome-java/tree/test) ⭐ 46,952 | 🐛 2 | 📅 2026-02-07.

We are evaluating to make this the default, you can provide feedback here in [#1171](https://github.com/akullpp/awesome-java/issues/1171) ⭐ 46,952 | 🐛 2 | 📅 2026-02-07.

## Contents

* [Awesome Java](#awesome-java-)
  * [Contents](#contents)
  * [Projects](#projects)
    * [Architecture](#architecture)
    * [Artificial Intelligence](#artificial-intelligence)
    * [Bean Mapping](#bean-mapping)
    * [Build](#build)
    * [Bytecode Manipulation](#bytecode-manipulation)
    * [Caching](#caching)
    * [CLI](#cli)
      * [Argument Parsing](#argument-parsing)
      * [Text-Based User Interfaces](#text-based-user-interfaces)
    * [Cloud](#cloud)
    * [Code Analysis](#code-analysis)
    * [Code Coverage](#code-coverage)
    * [Code Generators](#code-generators)
    * [Compiler-compiler](#compiler-compiler)
    * [Computer Vision](#computer-vision)
    * [Configuration](#configuration)
    * [Constraint Satisfaction Problem Solver](#constraint-satisfaction-problem-solver)
    * [CSV](#csv)
    * [Data Structures](#data-structures)
    * [Database](#database)
    * [Date and Time](#date-and-time)
    * [Decentralization](#decentralization)
    * [Dependency Injection](#dependency-injection)
    * [Development](#development)
    * [Distributed Applications](#distributed-applications)
    * [Distributed Transactions](#distributed-transactions)
    * [Distribution](#distribution)
    * [Document Processing](#document-processing)
    * [Financial](#financial)
    * [Formal Verification](#formal-verification)
    * [Functional Programming](#functional-programming)
    * [Game Development](#game-development)
    * [Geospatial](#geospatial)
    * [GUI](#gui)
    * [High Performance](#high-performance)
    * [HTTP Clients](#http-clients)
    * [Hypermedia Types](#hypermedia-types)
    * [IDE](#ide)
    * [Imagery](#imagery)
    * [Introspection](#introspection)
    * [Job Scheduling](#job-scheduling)
    * [JSON](#json)
    * [JVM and JDK](#jvm-and-jdk)
    * [Logging](#logging)
    * [Machine Learning](#machine-learning)
    * [Messaging](#messaging)
    * [Microservice](#microservice)
    * [Miscellaneous](#miscellaneous)
    * [Mobile Development](#mobile-development)
    * [Monitoring](#monitoring)
    * [Native](#native)
    * [Natural Language Processing](#natural-language-processing)
    * [Networking](#networking)
    * [ORM](#orm)
    * [PaaS](#paas)
    * [Pathfinding](#pathfinding)
    * [PDF](#pdf)
    * [Performance analysis](#performance-analysis)
    * [Platform](#platform)
      * [Apache Commons](#apache-commons)
      * [Other](#other)
    * [Processes](#processes)
    * [Reactive libraries](#reactive-libraries)
    * [REST Frameworks](#rest-frameworks)
    * [Science](#science)
    * [Search](#search)
    * [Security](#security)
    * [Serialization](#serialization)
    * [Server](#server)
    * [Template Engine](#template-engine)
    * [Testing](#testing)
      * [Asynchronous](#asynchronous)
      * [BDD](#bdd)
      * [Fixtures](#fixtures)
      * [Frameworks](#frameworks)
      * [Matchers](#matchers)
      * [Miscellaneous](#miscellaneous-1)
      * [Mocking](#mocking)
    * [Utility](#utility)
    * [Version Managers](#version-managers)
    * [Web Crawling](#web-crawling)
    * [Web Frameworks](#web-frameworks)
    * [Workflow Orchestration Engines](#workflow-orchestration-engines)
  * [Resources](#resources)
    * [Related Awesome Lists](#related-awesome-lists)
    * [Communities](#communities)
    * [Frontends](#frontends)
    * [Influential Books](#influential-books)
    * [Podcasts and Screencasts](#podcasts-and-screencasts)
    * [People](#people)
      * [Socials](#socials)
    * [Websites](#websites)
  * [Contributing](#contributing)

## Projects

### Architecture

*Frameworks and libraries that help implementing and verifying design and architecture concepts.*

* [ArchUnit](https://github.com/TNG/ArchUnit) ⭐ 3,593 | 🐛 180 | 🌐 Java | 📅 2026-01-27 - Test library for specifying and asserting architecture rules.
* [jMolecules](https://github.com/xmolecules/jmolecules) ⭐ 1,502 | 🐛 19 | 🌐 Java | 📅 2026-02-03 - Annotations and interfaces to express design and architecture concepts in code.

### Artificial Intelligence

*Frameworks that help you to leverage LLMs and AI.*

* [LangChain4j](https://github.com/langchain4j/langchain4j) ⭐ 10,665 | 🐛 644 | 🌐 Java | 📅 2026-02-06 - Simplifies integration of LLMs with unified APIs and a comprehensive toolbox.
* [MCP Java SDK](https://github.com/modelcontextprotocol/java-sdk) ⭐ 3,148 | 🐛 312 | 🌐 Java | 📅 2026-02-06 - Enables applications to interact with AI models and tools through a standardized interface (i.e. Model Context Protocol), supporting both synchronous and asynchronous communication patterns.
* [simple-openai](https://github.com/sashirestela/simple-openai) ⭐ 372 | 🐛 15 | 🌐 Java | 📅 2025-09-17 - Library to use the OpenAI API (and compatible ones) in the simplest possible way.
* [Spring AI](https://spring.io/projects/spring-ai) - Application framework for AI engineering for Spring.

### Bean Mapping

*Frameworks that ease bean mapping.*

* [MapStruct](https://github.com/mapstruct/mapstruct) ⭐ 7,613 | 🐛 492 | 🌐 Java | 📅 2026-02-02 - Code generator that simplifies mappings between different bean types, based on a convention-over-configuration approach.
* [ModelMapper](https://github.com/modelmapper/modelmapper) ⭐ 2,346 | 🐛 257 | 🌐 Java | 📅 2025-11-11 - Intelligent object mapping library that automatically maps objects to each other.
* [Orika](https://github.com/orika-mapper/orika) ⭐ 1,316 | 🐛 161 | 🌐 Java | 📅 2024-10-14 - JavaBean-mapping framework that recursively copies (among other capabilities) data from one object to another.
* [JMapper](https://github.com/jmapper-framework/jmapper-core) ⭐ 242 | 🐛 37 | 🌐 Java | 📅 2023-10-25 - Uses byte code manipulation for lightning-fast mapping. Supports annotations and API or XML configuration.
* [Selma](https://github.com/xebia-france/selma) ⭐ 214 | 🐛 58 | 🌐 Java | 📅 2020-01-01 - Annotation processor-based bean mapper.
* [reMap](https://github.com/remondis-it/remap) ⭐ 126 | 🐛 19 | 🌐 Java | 📅 2025-10-12 - Lambda and method handle-based mapping which requires code and not annotations if objects have different names.
* [dOOv](https://github.com/doov-io/doov) ⭐ 100 | 🐛 14 | 🌐 Java | 📅 2023-01-04 - Provides fluent API for typesafe domain model validation and mapping. It uses annotations, code generation and a type safe DSL to make bean validation and mapping fast and easy.

### Build

*Tools that handle the build cycle and dependencies of an application.*

* [Apache Maven](https://maven.apache.org) - Declarative build and dependency management that favors convention over configuration. It might be preferable to Apache Ant, which uses a rather procedural approach and can be difficult to maintain.
* [Bazel](https://bazel.build) - Tool from Google that builds code quickly and reliably.
* [Buck2](https://github.com/facebook/buck2) ⭐ 4,246 | 🐛 342 | 🌐 Rust | 📅 2026-02-07 - Encourages the creation of small, reusable modules consisting of code and resources.
* [Gradle](https://gradle.org) - Incremental builds programmed via Groovy instead of declaring XML. Works well with Maven's dependency management.

### Bytecode Manipulation

*Libraries to manipulate bytecode programmatically.*

* [bytecode-viewer](https://github.com/Konloch/bytecode-viewer) ⭐ 15,409 | 🐛 100 | 🌐 Java | 📅 2026-01-07 - Java 8 Jar & Android APK reverse engineering suite. (GPL-3.0-only)
* [cglib](https://github.com/cglib/cglib) ⭐ 4,889 | 🐛 95 | 🌐 Java | 📅 2024-08-16 - Bytecode generation library.
* [Javassist](https://github.com/jboss-javassist/javassist) ⭐ 4,230 | 🐛 251 | 🌐 Java | 📅 2024-10-03 - Tries to simplify bytecode editing.
* [Mixin](https://github.com/SpongePowered/Mixin) ⭐ 1,664 | 🐛 111 | 🌐 Java | 📅 2024-08-05 - Manipulate bytecode at runtime using real Java code.
* [Perses](https://github.com/nicolasmanic/perses) ⚠️ Archived - Dynamically injects failure/latency at the bytecode level according to principles of chaos engineering.
* [Maker](https://github.com/cojen/maker) ⭐ 65 | 🐛 0 | 🌐 Java | 📅 2026-01-08 - Provides low level bytecode generation.
* [ASM](https://asm.ow2.io) - All-purpose, low-level bytecode manipulation and analysis.
* [Byte Buddy](https://bytebuddy.net) - Further simplifies bytecode generation with a fluent API.
* [Byteman](https://byteman.jboss.org) - Manipulate bytecode at runtime via DSL (rules); mainly for testing/troubleshooting. (LGPL-2.1-or-later)
* [Recaf](https://www.coley.software/Recaf/) - JVM reverse engineering toolkit, essentially an IDE for Java bytecode.

### Caching

*Libraries that provide caching facilities.*

* [cache2k](https://cache2k.org) - In-memory high performance caching library.
* [Caffeine](https://github.com/ben-manes/caffeine) ⭐ 17,454 | 🐛 2 | 🌐 Java | 📅 2026-02-05 - High-performance, near-optimal caching library.
* [Ehcache](http://www.ehcache.org) - Distributed general-purpose cache.
* [Infinispan](https://infinispan.org) - Highly concurrent key/value datastore used for caching.

### CLI

*Libraries for everything related to the CLI.*

#### Argument Parsing

*Libraries to assist with parsing command line arguments.*

* [JLine](https://github.com/jline/jline3) ⭐ 1,711 | 🐛 93 | 🌐 Java | 📅 2026-02-04 - Includes features from modern shells like completion or history.
* [jbock](https://github.com/jbock-java/jbock) ⭐ 89 | 🐛 1 | 🌐 Java | 📅 2026-01-15 - Reflectionless command line parser.
* [Airline](https://rvesse.github.io/airline/) - Annotation-based framework for parsing Git-like command-line arguments.
* [JCommander](http://jcommander.org) - Command-line argument-parsing framework with custom types and validation via implementing interfaces.
* [picocli](https://picocli.info) - ANSI colors and styles in usage help with annotation-based POSIX/GNU/any syntax, subcommands, strong typing for both options and positional args.

#### Text-Based User Interfaces

*Libraries that provide TUI frameworks, or building blocks related functions.*

* [Lanterna](https://github.com/mabe02/lanterna) ⭐ 2,527 | 🐛 103 | 🌐 Java | 📅 2025-07-18 - Easy console text-GUI library, similar to curses. (LGPL-3.0-only)
* [Jansi](https://github.com/fusesource/jansi) ⭐ 1,191 | 🐛 49 | 🌐 Java | 📅 2025-05-07 - ANSI escape codes to format console output.
* [Text-IO](https://github.com/beryx/text-io) ⭐ 352 | 🐛 17 | 🌐 Java | 📅 2023-11-02 - Aids the creation of full console-based applications.
* [Jexer](https://gitlab.com/AutumnMeowMeow/jexer) - Advanced console (and Swing) text user interface (TUI) library, with mouse-draggable windows, built-in terminal window manager, and sixel image support. Looks like [Turbo Vision](https://en.wikipedia.org/wiki/Turbo_Vision).

### Cloud

*Libraries to integrate or use cloud-specific features.*

* [AWS SDK for Java](https://github.com/aws/aws-sdk-java) ⭐ 4,196 | 🐛 1 | 🌐 Java | 📅 2026-01-05 - Provides Java APIs for interacting with Amazon Web Services.
* [Google Cloud Client Libraries](https://github.com/googleapis/google-cloud-java) ⭐ 2,012 | 🐛 143 | 🌐 Java | 📅 2026-02-07 - Client libraries for accessing Google Cloud services from Java applications.

### Code Analysis

*Tools that provide metrics and quality measurements.*

* [p3c](https://github.com/alibaba/p3c) ⭐ 30,823 | 🐛 186 | 🌐 Kotlin | 📅 2024-08-06 - Provides Alibaba's coding guidelines for PMD, IDEA and Eclipse.
* [Infer](https://github.com/facebook/infer) ⭐ 15,517 | 🐛 406 | 🌐 OCaml | 📅 2026-02-07 - Modern static analysis tool for verifying the correctness of code.
* [Checkstyle](https://github.com/checkstyle/checkstyle) ⭐ 8,850 | 🐛 935 | 🌐 Java | 📅 2026-02-08 - Static analysis of coding conventions and standards. (LGPL-2.1-or-later)
* [Error Prone](https://github.com/google/error-prone) ⭐ 7,133 | 🐛 463 | 🌐 Java | 📅 2026-02-06 - Catches common programming mistakes as compile-time errors.
* [PMD](https://github.com/pmd/pmd) ⭐ 5,314 | 🐛 616 | 🌐 Java | 📅 2026-02-05 - Source code analysis for finding bad coding practices.
* [NullAway](https://github.com/uber/NullAway) ⭐ 4,002 | 🐛 133 | 🌐 Java | 📅 2026-02-08 - Eliminates NullPointerExceptions with low build-time overhead.
* [Spotbugs](https://github.com/spotbugs/spotbugs) ⭐ 3,819 | 🐛 452 | 🌐 Java | 📅 2026-02-08 - Static analysis of bytecode to find potential bugs. (LGPL-2.1-only)
* [Spoon](https://github.com/INRIA/spoon) ⭐ 1,898 | 🐛 357 | 🌐 Java | 📅 2026-02-08 - Library for analyzing and transforming Java source code.
* [SonarJava](https://github.com/SonarSource/sonar-java) ⭐ 1,190 | 🐛 12 | 🌐 Java | 📅 2026-02-06 - Static analyzer for SonarQube & SonarLint. (LGPL-3.0-only)
* [RefactorFirst](https://github.com/jimbethancourt/RefactorFirst) ⭐ 508 | 🐛 62 | 🌐 Java | 📅 2026-01-15 - Identifies and prioritizes God Classes and Highly Coupled classes.
* [Error Prone Support](https://github.com/PicnicSupermarket/error-prone-support) ⭐ 232 | 🐛 52 | 🌐 Java | 📅 2026-02-08 - Error Prone extensions: extra bug checkers and a large battery of Refaster templates.
* [jQAssistant](https://jqassistant.org) - Static code analysis with Neo4J-based query language. (GPL-3.0-only)
* [ToolsHref](https://toolshref.com) - Online Java code analyzer and JSON-to-Mermaid visualization tool.

### Code Coverage

*Frameworks and tools that enable code coverage metrics collection for test suites.*

* [Clover](https://www.atlassian.com/software/clover) - Relies on source-code instrumentation instead of bytecode instrumentation.
* [Cobertura](https://cobertura.github.io/cobertura/) - Relies on offline (or static) bytecode instrumentation and class loading to collect code coverage metrics. (GPL-2.0-only)
* [JaCoCo](https://www.eclemma.org/jacoco/) - Framework that enables collection of code coverage metrics, using both offline and runtime bytecode instrumentation.

### Code Generators

*Tools that generate patterns for repetitive code in order to reduce verbosity and error-proneness.*

* [JHipster](https://github.com/jhipster/generator-jhipster) ⭐ 22,343 | 🐛 122 | 🌐 TypeScript | 📅 2026-02-07 - Yeoman source code generator for Spring Boot and AngularJS.
* [JavaPoet](https://github.com/square/javapoet) ⚠️ Archived - API to generate source files.
* [Auto](https://github.com/google/auto) ⭐ 10,550 | 🐛 86 | 🌐 Java | 📅 2026-02-03 - Generates factory, service, and value classes.
* [Record-Builder](https://github.com/Randgalt/record-builder) ⭐ 907 | 🐛 33 | 🌐 Java | 📅 2026-01-26 - Companion builder class, withers and templates for Java records.
* [FreeBuilder](https://github.com/inferred/FreeBuilder) ⚠️ Archived - Automatically generates the Builder pattern.
* [ADT4J](https://github.com/sviperll/adt4j) ⭐ 147 | 🐛 12 | 🌐 Java | 📅 2018-03-02 - JSR-269 code generator for algebraic data types.
* [Geci](https://github.com/verhas/javageci) ⭐ 135 | 🐛 2 | 🌐 Java | 📅 2026-01-26 - Discovers files that need generated code, updates automatically and writes to the source with a convenient API.
* [EasyEntityToDTO](https://github.com/Marcel091004/EasyEntityToDTO) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2026-02-06 - Annotation processor for automatic DTO and Mapper generation with zero boilerplate.
* [JSpecify Package-Info Generator](https://github.com/bcaillard/jspecify-packageinfo-generator) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2025-11-28 - Maven plugin that automatically generates package-info.java files with JSpecify annotations (@NullMarked and @NullUnmarked), helping you manage nullness boundaries in your Java projects without manual boilerplate.
* [Avaje Http Server](https://avaje.io/http/) - Generates Lightweight JAX-RS style http servers using Javalin or Helidon (Nima) SE.
* [Bootify ![c]](https://bootify.io) - Browser-based Spring Boot app generation with JPA model and REST API.
* [Immutables](https://immutables.github.io) - Annotation processors to generate simple, safe and consistent value objects.
* [Joda-Beans](https://www.joda.org/joda-beans/) - Small framework that adds queryable properties to Java, enhancing JavaBeans.
* [JPA Buddy ![c]](https://www.jpa-buddy.com) - Plugin for IntelliJ IDEA. Provides visual tools for generating JPA entities, Spring Data JPA repositories, Liquibase changelogs and SQL scripts. Offers automatic Liquibase/Flyway script generation by comparing model to DB, and reverse engineering JPA entities from DB tables.
* [Lombok](https://projectlombok.org) - Code generator that aims to reduce verbosity.
* [Telosys](https://www.telosys.org/) - Simple and light code generator available as an Eclipse Plugin and also as a CLI.

### Compiler-compiler

*Frameworks that help to create parsers, interpreters or compilers.*

* [ANTLR](https://www.antlr.org) - Complex full-featured framework for top-down parsing.
* [JavaCC](https://javacc.github.io/javacc/) - Parser generator that generates top-down parsers. Allows lexical state switching and permits extended BNF specifications.
* [JFlex](https://jflex.de) - Lexical analyzer generator.

### Computer Vision

*Libraries which seek to gain high level information from images and videos.*

* [BoofCV](https://boofcv.org) - Library for image processing, camera calibration, tracking, SFM, MVS, 3D vision, QR Code and much more.
* [ImageJ](https://imagej.net/ImageJ) - Medical image processing application with an API.
* [JavaCV](https://github.com/bytedeco/javacv) ⭐ 8,284 | 🐛 467 | 🌐 Java | 📅 2026-01-31 - Java interface to OpenCV, FFmpeg, and much more.

### Configuration

*Libraries that provide external configuration.*

* [config](https://github.com/lightbend/config) ⭐ 6,293 | 🐛 239 | 🌐 Java | 📅 2026-01-15 - Configuration library supporting Java properties, JSON or its human optimized superset HOCON.
* [owner](https://github.com/lviggiano/owner) ⭐ 932 | 🐛 135 | 🌐 Java | 📅 2026-02-02 - Reduces boilerplate of properties.
* [centraldogma](https://github.com/line/centraldogma) ⭐ 655 | 🐛 164 | 🌐 Java | 📅 2026-02-06 - Highly-available version-controlled service configuration repository based on Git, ZooKeeper and HTTP/2.
* [Configurate](https://github.com/SpongePowered/Configurate) ⭐ 454 | 🐛 42 | 🌐 Java | 📅 2026-02-06 - Configuration library with support for various configuration formats and transformations.
* [Gestalt](https://github.com/gestalt-config/gestalt) ⭐ 96 | 🐛 14 | 🌐 Java | 📅 2026-01-29 - Gestalt offers a comprehensive solution to the challenges of configuration management. It allows you to source configuration data from multiple inputs, merge them intelligently, and present them in a structured, type-safe manner.
* [KAConf](https://github.com/mariomac/kaconf) ⭐ 61 | 🐛 0 | 🌐 Java | 📅 2022-07-29 - Annotation-based configuration system for Java and Kotlin.
* [dotenv](https://github.com/shyiko/dotenv) ⭐ 50 | 🐛 0 | 🌐 Java | 📅 2018-02-07 - Twelve-factor configuration library which uses environment-specific files.
* [Externalized Properties](https://github.com/joel-jeremy/externalized-properties) ⭐ 45 | 🐛 5 | 🌐 Java | 📅 2026-02-05 - Simple, lightweight, yet powerful configuration library which supports resolution of properties from external sources such as files, databases, git repositories, and any custom sources, plus an extensible post-processing/conversion mechanism.
* [avaje config](https://avaje.io/config/) - Loads yaml and properties files, supports dynamic configuration, plugins, file-watching and config event listeners.
* [Curator Framework](https://curator.apache.org/) - High-level API for Apache ZooKeeper.
* [ini4j](http://ini4j.sourceforge.net) - Provides an API for handling Windows' INI files.
* [microconfig](https://microconfig.io) - Configuration system designed for microservices which helps to separate configuration from code. The configuration for different services can have common and specific parts and can be dynamically distributed.

### Constraint Satisfaction Problem Solver

*Libraries that help with implementing optimization and satisfiability problems.*

* [Choco](https://choco-solver.org) - Off-the-shelf constraint satisfaction problem solver that uses constraint programming techniques.
* [JaCoP](https://github.com/radsz/jacop) ⭐ 232 | 🐛 11 | 🌐 Java | 📅 2026-02-08 - Includes an interface for the FlatZinc language, enabling it to execute MiniZinc models. (AGPL-3.0)
* [OptaPlanner](https://www.optaplanner.org) - Business planning and resource scheduling optimization solver.
* [Timefold](https://timefold.ai/docs) - Flexible solver with Spring/Quarkus support and quickstarts for the Vehicle Routing Problem, Maintenance Scheduling, Employee Shift Scheduling and much more.

### CSV

*Frameworks and libraries that simplify reading/writing CSV data.*

* [uniVocity-parsers](https://github.com/uniVocity/univocity-parsers) ⭐ 932 | 🐛 103 | 🌐 Java | 📅 2024-08-17 - One of the fastest and most feature-complete parsers. Also comes with parsers for TSV and fixed-width records.
* [FastCSV](https://github.com/osiegmar/FastCSV) ⭐ 661 | 🐛 5 | 🌐 Java | 📅 2026-02-02 - Performance-optimized, dependency-free and RFC 4180 compliant.
* [jackson-dataformat-csv](https://github.com/FasterXML/jackson-dataformat-csv) ⚠️ Archived - Jackson extension for reading and writing CSV.
* [opencsv](http://opencsv.sourceforge.net) - Simple CSV parser.
* [Super CSV](https://super-csv.github.io/super-csv/) - Powerful CSV parser with support for Dozer, Joda-Time and Java 8.

### Data Structures

*Efficient and specific data structures.*

* [Protobuf](https://github.com/protocolbuffers/protobuf) ⭐ 70,655 | 🐛 229 | 🌐 C++ | 📅 2026-02-08 - Google's data interchange format.
* [Wire](https://github.com/square/wire) ⭐ 4,405 | 🐛 169 | 🌐 Kotlin | 📅 2026-02-05 - Clean, lightweight protocol buffers.
* [RoaringBitmap](https://github.com/RoaringBitmap/RoaringBitmap) ⭐ 3,816 | 🐛 75 | 🌐 Java | 📅 2026-01-23 - Fast and efficient compressed bitmap.
* [SBE](https://github.com/real-logic/simple-binary-encoding) ⭐ 3,387 | 🐛 36 | 🌐 Java | 📅 2026-01-30 - Simple Binary Encoding, one of the fastest message formats around.
* [Tape](https://github.com/square/tape) ⚠️ Archived - Lightning-fast, transactional, file-based FIFO.
* [Persistent Collection](https://github.com/hrldcpr/pcollections) ⭐ 784 | 🐛 21 | 🌐 Java | 📅 2025-07-23 - Persistent and immutable analogue of the Java Collections Framework.
* [Big Queue](https://github.com/bulldog2011/bigqueue) ⭐ 569 | 🐛 27 | 🌐 Java | 📅 2022-07-26 - Fast and persistent queue based on memory-mapped files.
* [Apache Avro](https://avro.apache.org) - Data interchange format with dynamic typing, untagged data, and absence of manually assigned IDs.
* [Apache Orc](https://orc.apache.org) - Fast and efficient columnar storage format for Hadoop-based workloads.
* [Apache Parquet](https://parquet.apache.org) - Columnar storage format based on assembly algorithms from Google's paper on Dremel.
* [Apache Thrift](https://thrift.apache.org) - Data interchange format that originated at Facebook.
* [HyperMinHash-java](https://github.com/LiveRamp/HyperMinHash-java) - Probabilistic data structure for computing union, intersection, and set cardinality in loglog space.

### Database

*Everything that simplifies interactions with the database.*

* [Redisson](https://github.com/redisson/redisson) ⭐ 24,241 | 🐛 295 | 🌐 Java | 📅 2026-02-05 - Allows for distributed and scalable data structures on top of a Redis server.
* [HikariCP](https://github.com/brettwooldridge/HikariCP) ⭐ 20,992 | 🐛 526 | 🌐 Java | 📅 2025-11-04 - High-performance JDBC connection pool.
* [Apache ShardingSphere](https://github.com/apache/shardingsphere) ⭐ 20,672 | 🐛 363 | 🌐 Java | 📅 2026-02-08 - Distributed SQL transaction & query engine that allows for data sharding, scaling, encryption, and more on any database.
* [QuestDB](https://github.com/questdb/questdb) ⭐ 16,652 | 🐛 797 | 🌐 Java | 📅 2026-02-08 - High-performance SQL database for time series. Supports InfluxDB line protocol, PostgreSQL wire protocol, and REST.
* [Jedis](https://github.com/xetorthio/jedis) ⭐ 12,275 | 🐛 98 | 🌐 Java | 📅 2026-02-05 - Small client for interaction with Redis, with methods for commands.
* [Realm](https://github.com/realm/realm-java) ⭐ 11,489 | 🐛 396 | 🌐 Java | 📅 2025-09-15 - Mobile database to run directly inside phones, tablets or wearables.
* [Leaf](https://github.com/Meituan-Dianping/Leaf) ⭐ 6,727 | 🐛 95 | 🌐 Java | 📅 2023-07-18 - Distributed ID generate service.
* [requery](https://github.com/requery/requery) ⭐ 3,121 | 🐛 176 | 🌐 Java | 📅 2022-03-08 - Modern, lightweight but powerful object mapping and SQL generator. Easily map to or create databases, or perform queries and updates from any Java-using platform.
* [Chronicle Map](https://github.com/OpenHFT/Chronicle-Map) ⭐ 2,937 | 🐛 23 | 🌐 Java | 📅 2026-01-29 - Efficient, in-memory (opt. persisted to disk), off-heap key-value store.
* [Jest](https://github.com/searchbox-io/Jest) ⚠️ Archived - Client for the Elasticsearch REST API.
* [Speedment](https://github.com/speedment/speedment) ⭐ 2,097 | 🐛 95 | 🌐 Java | 📅 2023-11-07 - Database access library that utilizes Java 8's Stream API for querying.
* [Xodus](https://github.com/JetBrains/xodus) ⭐ 1,252 | 🐛 0 | 🌐 Java | 📅 2025-12-01 - Highly concurrent transactional schema-less and ACID-compliant embedded database.
* [FlexyPool](https://github.com/vladmihalcea/flexy-pool) ⭐ 1,168 | 🐛 5 | 🌐 Java | 📅 2025-11-28 - Brings metrics and failover strategies to the most common connection pooling solutions.
* [Jinq](https://github.com/my2iu/Jinq) ⭐ 663 | 🐛 36 | 🌐 Java | 📅 2025-06-08 - Typesafe database queries via symbolic execution of Java 8 Lambdas (on top of JPA or jOOQ).
* [CosId](https://github.com/Ahoo-Wang/CosId) ⭐ 605 | 🐛 13 | 🌐 Java | 📅 2026-02-08 - Universal, flexible, high-performance distributed ID generator.
* [eXist](https://github.com/eXist-db/exist) ⭐ 460 | 🐛 599 | 🌐 Java | 📅 2026-02-07 - NoSQL document database and application platform. (LGPL-2.1-only)
* [OpenDJ](https://github.com/OpenIdentityPlatform/OpenDJ) ⭐ 427 | 🐛 5 | 🌐 Java | 📅 2026-02-04 - LDAPv3 compliant directory service, developed for the Java platform, providing a high performance, highly available, and secure store for the identities.
* [ArangoDB](https://github.com/arangodb/arangodb-java-driver) ⭐ 205 | 🐛 13 | 🌐 Java | 📅 2026-01-27 - ArangoDB Java driver.
* [jetcd](https://github.com/justinsb/jetcd) ⭐ 141 | 🐛 17 | 🌐 Java | 📅 2023-02-21 - Client library for etcd.
* [Spring Data JPA MongoDB Expressions](https://github.com/mhewedy/spring-data-jpa-mongodb-expressions) ⭐ 101 | 🐛 0 | 🌐 Java | 📅 2026-01-21 - Allows you to use MongoDB query language to query your relational database.
* [Spring Data Dynamic Query](https://github.com/tdilber/spring-data-dynamic-query) ⭐ 33 | 🐛 1 | 🌐 Java | 📅 2025-11-17 - Unified dynamic query interface for Spring Data JPA, MongoDB, and Elasticsearch, enabling advanced JOIN(s), OR logic, scoped conditions, powerful projections and advanced features with zero boilerplate.
* [QueryStream](https://github.com/querystream/querystream) ⭐ 20 | 🐛 0 | 🌐 HTML | 📅 2025-05-06 - Build JPA Criteria queries using a Stream-like API.
* [MariaDB4j](https://github.com/vorburger/MariaDB4j) ⭐ 15 | 🐛 0 | 🌐 Java | 📅 2026-01-02 - Launcher for MariaDB that requires no installation or external dependencies.
* [Modality](https://github.com/arkanovicz/modality) ⭐ 15 | 🐛 3 | 🌐 Java | 📅 2026-01-20 - Lightweight ORM with database reverse engineering features.
* [Apache Calcite](https://calcite.apache.org) - Dynamic data management framework. It contains many of the pieces that comprise a typical database management system.
* [Apache Drill](https://drill.apache.org) - Distributed, schema on-the-fly, ANSI SQL query engine for Big Data exploration.
* [Apache Phoenix](https://phoenix.apache.org) - High-performance relational database layer over HBase for low-latency applications.
* [Debezium](https://debezium.io/) - Low latency data streaming platform for change data capture.
* [druid](https://druid.apache.org) - High-performance, column-oriented, distributed data store.
* [Flyway](https://flywaydb.org) - Simple database migration tool.
* [H2](https://h2database.com) - Small SQL database notable for its in-memory functionality.
* [HSQLDB](https://hsqldb.org/) - HyperSQL 100% Java database.
* [JDBI](http://jdbi.org) - Convenient abstraction of JDBC.
* [jOOQ](https://www.jooq.org) - Generates typesafe code based on SQL schema.
* [Lettuce](https://lettuce.io/) - Lettuce is a scalable Redis client for building non-blocking Reactive applications.
* [Liquibase](http://www.liquibase.org) - Database-independent library for tracking, managing and applying database schema changes.
* [MapDB](http://www.mapdb.org) - Embedded database engine that provides concurrent collections backed on disk or in off-heap memory.
* [Querydsl](http://www.querydsl.com) - Typesafe unified queries.
* [Trino](https://trino.io) - Distributed SQL query engine for big data.
* [Vibur DBCP](https://www.vibur.org) - JDBC connection pool library with advanced performance monitoring capabilities.

### Date and Time

*Libraries related to handling date and time.*

* [iCal4j](https://github.com/ical4j/ical4j) ⭐ 826 | 🐛 159 | 🌐 Java | 📅 2026-01-24 - Parse and build iCalendar [RFC 5545](https://tools.ietf.org/html/rfc5545) data models.
* [Time4J](https://github.com/MenoData/Time4J) ⭐ 472 | 🐛 19 | 🌐 Java | 📅 2024-02-11 - Advanced date and time library. (LGPL-2.1-only)
* [ThreeTen-Extra](https://github.com/ThreeTen/threeten-extra) ⭐ 421 | 🐛 40 | 🌐 Java | 📅 2025-08-20 - Additional date-time classes that complement those in JDK 8.
* [Jollyday](https://github.com/svendiedrichsen/jollyday) ⭐ 193 | 🐛 36 | 🌐 Java | 📅 2024-05-01 - Determines the holidays for a given year, country/name and eventually state/region.

### Decentralization

*Libraries that handle decentralization tasks.*

* [java-tron](https://github.com/tronprotocol/java-tron) ⭐ 4,025 | 🐛 35 | 🌐 Java | 📅 2026-02-04 Implementation of the Tron Protocol, whic utilizes blockchains to develop decentralized applications.

### Dependency Injection

*Libraries that help to realize the [Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) paradigm.*

* [Guice](https://github.com/google/guice) ⭐ 12,726 | 🐛 359 | 🌐 Java | 📅 2026-02-03 - Lightweight and opinionated framework that completes Dagger.
* [Governator](https://github.com/Netflix/governator) ⭐ 827 | 🐛 11 | 🌐 Java | 📅 2025-12-17 - Extensions and utilities that enhance Google Guice.
* [Feather](https://github.com/zsoltherpai/feather) ⭐ 362 | 🐛 15 | 🌐 Java | 📅 2018-04-18 - Ultra-lightweight, JSR-330-compliant dependency injection library.
* [JayWire](https://github.com/vanillasource/jaywire) ⭐ 60 | 🐛 3 | 🌐 Java | 📅 2023-02-21 - Lightweight dependency injection framework. (LGPL-3.0-only)
* [Apache DeltaSpike](https://deltaspike.apache.org) - CDI extension framework.
* [Avaje Inject](https://avaje.io/inject/) - Microservice-focused compile-time injection framework without reflection.
* [Dagger](https://dagger.dev/) - Compile-time injection framework without reflection.
* [HK2](https://eclipse-ee4j.github.io/glassfish-hk2/) - Lightweight and dynamic dependency injection framework.

### Development

*Augmentation of the development process at a fundamental level.*

* [JavaParser](https://github.com/javaparser/javaparser) ⭐ 6,043 | 🐛 448 | 🌐 Java | 📅 2026-02-05 - Parse, modify and generate Java code.
* [Manifold](https://github.com/manifold-systems/manifold) ⭐ 2,703 | 🐛 107 | 🌐 Java | 📅 2026-02-03 - Re-energizes Java with powerful features like type-safe metaprogramming, structural typing and extension methods.
* [HotswapAgent](https://github.com/HotswapProjects/HotswapAgent) ⭐ 2,566 | 🐛 105 | 🌐 Java | 📅 2026-02-07 - Unlimited runtime class and resource redefinition. (GPL-2.0-only)
* [JavaSymbolSolver](https://github.com/javaparser/javasymbolsolver) ⚠️ Archived - Symbol solver.
* [Faux Pas](https://github.com/zalando/faux-pas) ⭐ 141 | 🐛 11 | 🌐 Java | 📅 2025-06-30 - Library that simplifies error handling by circumventing the issue that none of the functional interfaces in the Java Runtime is allowed by default to throw checked exceptions.
* [SneakyThrow](https://github.com/rainerhahnekamp/sneakythrow) ⭐ 79 | 🐛 0 | 🌐 Java | 📅 2019-10-24 - Ignores checked exceptions without bytecode manipulation. Can also be used inside Java 8 stream operations.
* [AspectJ](https://www.eclipse.org/aspectj/) - Seamless aspect-oriented programming extension.
* [DCEVM](https://dcevm.github.io) - JVM modification that allows unlimited redefinition of loaded classes at runtime. (GPL-2.0-only)
* [NoException](https://noexception.machinezoo.com) - Allows checked exceptions in functional interfaces and converts exceptions to Optional return.
* [Tail](https://nrktkt.github.io/tail/) - Enable infinite recursion using tail call optimization.

### Distributed Applications

*Libraries and frameworks for writing distributed and fault-tolerant applications.*

* [Zuul](https://github.com/Netflix/zuul) ⭐ 13,982 | 🐛 8 | 🌐 Java | 📅 2026-02-06 - Gateway service that provides dynamic routing, monitoring, resiliency, security, and more.
* [resilience4j](https://github.com/resilience4j/resilience4j) ⭐ 10,540 | 🐛 277 | 🌐 Java | 📅 2026-02-06 - Functional fault tolerance library.
* [Hazelcast](https://github.com/hazelcast/hazelcast) ⭐ 6,587 | 🐛 1,106 | 🌐 Java | 📅 2026-02-06 - Highly scalable in-memory datagrid with a free open-source version.
* [Failsafe](https://github.com/jhalterman/failsafe) ⭐ 4,302 | 🐛 74 | 🌐 Java | 📅 2025-12-28 - Simple failure handling with retries and circuit breakers.
* [ScaleCube Services](https://github.com/scalecube/scalecube-services) ⭐ 637 | 🐛 15 | 🌐 Java | 📅 2026-01-26 - Embeddable Cluster-Membership library based on SWIM and gossip protocol.
* [OpenIG](https://github.com/OpenIdentityPlatform/OpenIG) ⭐ 86 | 🐛 0 | 🌐 Java | 📅 2026-02-05 - High-performance reverse proxy server with specialized session management and credential replay functionality.
* [Dropwizard Circuit Breaker](https://github.com/mtakaki/dropwizard-circuitbreaker) ⭐ 45 | 🐛 2 | 🌐 Java | 📅 2026-01-26 - Circuit breaker design pattern for Dropwizard. (GPL-2.0-only)
* [Apache Geode](https://geode.apache.org) - In-memory data management system that provides reliable asynchronous event notifications and guaranteed message delivery.
* [Apache Storm](https://storm.apache.org) - Realtime computation system.
* [Apache ZooKeeper](https://zookeeper.apache.org) - Coordination service with distributed configuration, synchronization, and naming registry for large distributed systems.
* [Atomix](https://atomix.io) - Fault-tolerant distributed coordination framework.
* [Axon](https://axoniq.io) - Framework for creating CQRS applications.
* [JGroups](http://www.jgroups.org) - Toolkit for reliable messaging and cluster creation.
* [Quasar](http://docs.paralleluniverse.co/quasar/) - Lightweight threads and actors for the JVM.

### Distributed Transactions

*Distributed transactions provide a mechanism for ensuring consistency of data updates in the presence of concurrent access and partial failures.*

* [Seata](https://github.com/seata/seata) ⭐ 25,944 | 🐛 866 | 🌐 Java | 📅 2026-02-07 - Delivers high performance and easy to use distributed transaction services under a microservices architecture.
* [Bitronix](https://github.com/bitronix/btm) ⭐ 430 | 🐛 30 | 🌐 Java | 📅 2024-02-02 - Simple but complete implementation of the JTA 1.1 API.
* [Atomikos](https://www.atomikos.com) - Provides transactions for REST, SOA and microservices with support for JTA and XA.
* [Narayana](https://narayana.io) - Provides support for traditional ACID and compensation transactions, also complies with JTA, JTS and other standards. (LGPL-2.1-only)

### Distribution

*Tools that handle the distribution of applications in native formats.*

* [packr](https://github.com/libgdx/packr) ⭐ 2,624 | 🐛 33 | 🌐 C++ | 📅 2024-04-11 - Packs JARs, assets and the JVM for native distribution on Windows, Linux and macOS.
* [JavaPackager](https://github.com/fvarrui/JavaPackager) ⭐ 1,191 | 🐛 53 | 🌐 Java | 📅 2025-12-02 - Maven and Gradle plugin which provides an easy way to package Java applications in native Windows, macOS or GNU/Linux executables, and generate installers for them.
* [Capsule](https://github.com/puniverse/capsule) ⭐ 1,150 | 🐛 29 | 🌐 Java | 📅 2022-05-29 - Simple and powerful packaging and deployment. A fat JAR on steroids, or a "Docker for Java" that supports JVM-optimized containers.
* [Artipie](https://github.com/artipie/artipie) ⭐ 654 | 🐛 86 | 🌐 Java | 📅 2025-09-17 - Binary artifact management toolkit which hosts them on the file system or S3.
* [Getdown](https://github.com/threerings/getdown) ⭐ 530 | 🐛 49 | 🌐 Java | 📅 2025-01-07 - System for deploying Java applications to end-user computers and keeping them up to date. Developed as an alternative to Java Web Start.
* [really-executable-jars-maven-plugin](https://github.com/brianm/really-executable-jars-maven-plugin) ⭐ 133 | 🐛 1 | 🌐 Java | 📅 2023-11-01 - Maven plugin for making self-executing JARs.
* [jlink.online](https://github.com/AdoptOpenJDK/jlink.online) ⭐ 50 | 🐛 6 | 🌐 Go | 📅 2024-12-12 - Builds optimized runtimes over HTTP.
* [Boxfuse ![c]](https://boxfuse.com) - Deployment of JVM applications to AWS using the principles of immutable infrastructure.
* [Central Repository](https://search.maven.org) - Largest binary component repository available as a free service to the open-source community. Default used by Apache Maven, and available in all other build tools.
* [Cloudsmith ![c]](https://cloudsmith.io) - Fully managed package management SaaS with support for Maven/Gradle/SBT with a free tier.
* [IzPack](http://izpack.org) - Setup authoring tool for cross-platform deployments.
* [jDeploy](https://www.jdeploy.com) - Deploy desktop apps as native Mac, Windows or Linux bundles.
* [Nexus ![c]](https://www.sonatype.com) - Binary management with proxy and caching capabilities.

### Document Processing

*Libraries that assist with processing office document formats.*

* [fastexcel](https://github.com/dhatim/fastexcel) ⭐ 856 | 🐛 72 | 🌐 Java | 📅 2026-02-02 - High performance library to read and write large Excel (XLSX) worksheets.
* [zerocell](https://github.com/creditdatamw/zerocell) ⭐ 81 | 🐛 4 | 🌐 Java | 📅 2024-12-12 - Annotation-based API for reading data from Excel sheets into POJOs with focus on reduced overhead.
* [Apache POI](https://poi.apache.org) - Supports OOXML (XLSX, DOCX, PPTX) as well as OLE2 (XLS, DOC or PPT).
* [documents4j](https://documents4j.com/#/) - API for document format conversion using third-party converters such as MS Word.
* [docx4j](https://www.docx4java.org/trac/docx4j) - Create and manipulate Microsoft Open XML files.

### Financial

*Libraries related to the financial domain.*

* [ta4j](https://github.com/ta4j/ta4j) ⭐ 2,374 | 🐛 22 | 🌐 Java | 📅 2026-02-08 - Library for technical analysis.
* [Stripe](https://github.com/stripe/stripe-java) ⭐ 950 | 🐛 26 | 🌐 Java | 📅 2026-02-04 - Integration with the Stripe API.
* [Cassandre](https://github.com/cassandre-tech/cassandre-trading-bot) ⭐ 650 | 🐛 17 | 🌐 Java | 📅 2025-03-01 - Trading bot framework.
* [Parity](https://github.com/paritytrading/parity) ⚠️ Archived - Platform for trading venues.
* [Philadelphia](https://github.com/paritytrading/philadelphia) ⭐ 340 | 🐛 3 | 🌐 Java | 📅 2026-02-06 - Low-latency financial information exchange.
* [Square](https://github.com/square/connect-java-sdk) ⚠️ Archived - Integration with the Square API.

### Formal Verification

*Formal-methods tools: proof assistants, model checking, symbolic execution, etc.*

* [Java Path Finder (JPF)](https://github.com/javapathfinder/jpf-core) ⭐ 600 | 🐛 67 | 🌐 Java | 📅 2025-12-16 - JVM formal verification tool containing a model checker and more. Created by NASA.
* [CATG](https://github.com/ksen007/janala2) ⭐ 105 | 🐛 5 | 🌐 Java | 📅 2018-02-20 - Concolic unit testing engine. Automatically generates unit tests using formal methods.
* [Checker Framework](https://checkerframework.org) - Pluggable type systems. Includes nullness types, physical units, immutability types and more. (GPL-2.0-only WITH Classpath-exception-2.0)
* [Daikon](https://plse.cs.washington.edu/daikon/) - Detects likely program invariants and generates JML specs based on those invariants.
* [JMLOK 2.0](https://massoni.computacao.ufcg.edu.br/home/jmlok) - Detects inconsistencies between code and JML specification through feedback-directed random tests generation, and suggests a likely cause for each nonconformance detected. (GPL-3.0-only)
* [KeY](https://www.key-project.org) - Formal software development tool that aims to integrate design, implementation, formal specification, and formal verification of object-oriented software as seamlessly as possible. Uses JML for specification and symbolic execution for verification. (GPL-2.0-or-later)
* [OpenJML](http://www.openjml.org) - Translates JML specifications into SMT-LIB format and passes the proof problems implied by the program to backend solvers. (GPL-2.0-only)

### Functional Programming

*Libraries that facilitate functional programming.*

* [StreamEx](https://github.com/amaembo/streamex) ⭐ 2,279 | 🐛 19 | 🌐 Java | 📅 2025-08-30 - Enhances Java 8 Streams.
* [jOOλ](https://github.com/jOOQ/jOOL) ⭐ 2,122 | 🐛 45 | 🌐 Java | 📅 2024-08-01 - Extension to Java 8 that aims to fix gaps in lambda by providing numerous missing types and a rich set of sequential Stream API additions.
* [Cyclops](https://github.com/aol/cyclops) ⭐ 1,333 | 🐛 29 | 🌐 Java | 📅 2023-03-21 - Monad and stream utilities, comprehensions, pattern matching, functional extensions for all JDK collections, future streams, trampolines and much more.
* [derive4j](https://github.com/derive4j/derive4j) ⭐ 578 | 🐛 18 | 🌐 Java | 📅 2022-12-01 - Java 8 annotation processor and framework for deriving algebraic data types constructors, pattern-matching and morphisms. (GPL-3.0-only)
* [protonpack](https://github.com/poetix/protonpack) ⭐ 486 | 🐛 4 | 🌐 Java | 📅 2024-05-09 - Collection of stream utilities.
* [Packrat](https://github.com/jhspetersson/packrat) ⭐ 24 | 🐛 0 | 🌐 Java | 📅 2026-01-20 - Gatherers library for Java Stream API. Gatherers can enhance streams with custom intermediate operations.
* [Fugue](https://bitbucket.org/atlassian/fugue) - Functional extensions to Guava.
* [Functional Java](http://www.functionaljava.org) - Implements numerous basic and advanced programming abstractions that assist composition-oriented development.
* [Vavr](https://www.vavr.io) - Functional component library that provides persistent data types and functional control structures.

### Game Development

*Frameworks that support the development of games.*

* [vulkan4j](https://github.com/chuigda/vulkan4j) ⭐ 77 | 🐛 18 | 🌐 Kotlin | 📅 2025-07-28 - Vulkan, OpenGL ES2 and GLFW Memory Allocator bindings.
* [FXGL](https://almasb.github.io/FXGL/) - JavaFX Game Development Framework.
* [JBox2D](http://www.jbox2d.org/) - Port of the renowned C++ 2D physics engine.
* [jMonkeyEngine](https://jmonkeyengine.org) - Game engine for modern 3D development.
* [libGDX](https://libgdx.com) - All-round cross-platform, high-level framework.
* [Litiengine](https://litiengine.com/) - AWT-based, lightweight 2D game engine.
* [LWJGL](https://www.lwjgl.org) - Robust framework that abstracts libraries like OpenGL/CL/AL.
* [Mini2Dx](https://mini2dx.org) - Beginner-friendly, master-ready framework for rapidly prototyping and building 2D games.
* [Void2D](https://github.com/xzripper/Void2D) - High-level 2D game engine with built-in physics based on Swing.

### Geospatial

*Libraries for working with geospatial data and algorithms.*

* [GraphHopper](https://github.com/graphhopper/graphhopper) ⭐ 6,259 | 🐛 255 | 🌐 Java | 📅 2026-02-05 - Road-routing engine. Used as a Java library or standalone web service.
* [Mapsforge](https://github.com/mapsforge/mapsforge) ⭐ 1,336 | 🐛 2 | 🌐 Java | 📅 2026-01-26 - Map rendering based on OpenStreetMap data. (LGPL-3.0-only)
* [Spatial4j](https://github.com/locationtech/spatial4j) ⭐ 956 | 🐛 75 | 🌐 Java | 📅 2025-05-31 - General-purpose spatial/geospatial library.
* [Geo](https://github.com/davidmoten/geo) ⭐ 430 | 🐛 9 | 🌐 Java | 📅 2026-02-02 - GeoHash utilities in Java.
* [ArcGIS Maps SDK for Java ![c]](https://github.com/Esri/arcgis-maps-sdk-java-samples/) ⭐ 125 | 🐛 0 | 🌐 Java | 📅 2025-09-19 - JavaFX library for adding mapping and GIS functionality to desktop apps.
* [Apache SIS](https://sis.apache.org) - Library for developing geospatial applications.
* [GeoTools](https://geotools.org) - Library that provides tools for geospatial data. (LGPL-2.1-only)
* [H2GIS](http://www.h2gis.org) - Spatial extension of the H2 database. (LGPL-3.0-only)
* [Jgeohash](https://astrapi69.github.io/jgeohash/) - Library for using the GeoHash algorithm.

### GUI

*Libraries to create modern graphical user interfaces.*

* [SnapKit](https://github.com/reportmill/SnapKit) ⭐ 311 | 🐛 0 | 🌐 Java | 📅 2026-02-06 - Modern Java UI library for both desktop and web.
* [Sierra](https://github.com/HTTP-RPC/Sierra) ⭐ 137 | 🐛 0 | 🌐 Java | 📅 2026-02-07 - Lightwieght declarative DSL for rapid development of Swing applications.
* [JavaFX](https://wiki.openjdk.java.net/display/OpenJFX/Main) - Successor of Swing.
* [Scene Builder](https://gluonhq.com/products/scene-builder/) - Visual layout tool for JavaFX applications.
* [SWT](https://www.eclipse.org/swt/) - Graphical widget toolkit.

### High Performance

*Everything about high-performance computation, from collections to specific libraries.*

* [JCTools](https://github.com/JCTools/JCTools) ⭐ 3,799 | 🐛 54 | 🌐 Java | 📅 2026-02-04 - Concurrency tools currently missing from the JDK.
* [Agrona](https://github.com/real-logic/Agrona) ⭐ 3,148 | 🐛 2 | 🌐 Java | 📅 2026-02-07 - Data structures and utility methods that are common in high-performance applications.
* [Eclipse Collections](https://github.com/eclipse/eclipse-collections) ⭐ 2,612 | 🐛 176 | 🌐 Java | 📅 2026-01-28 - Collections framework inspired by Smalltalk.
* [Koloboke](https://github.com/leventov/Koloboke) ⭐ 1,024 | 🐛 40 | 🌐 Java | 📅 2017-02-01 - Carefully designed extension of the Java Collections Framework with primitive specializations and more.
* [Disruptor](https://lmax-exchange.github.io/disruptor/) - Inter-thread messaging library.
* [fastutil](http://fastutil.di.unimi.it) - Fast and compact type-specific collections.
* [HPPC](https://labs.carrotsearch.com/hppc.html) - Primitive collections.

### HTTP Clients

*Libraries that assist with creating HTTP requests and/or binding responses.*

* [Feign](https://github.com/OpenFeign/feign) ⭐ 9,789 | 🐛 239 | 🌐 Java | 📅 2026-02-07 - HTTP client binder inspired by Retrofit, JAXRS-2.0, and WebSocket.
* [Async Http Client](https://github.com/AsyncHttpClient/async-http-client) ⭐ 6,405 | 🐛 107 | 🌐 Java | 📅 2025-12-31 - Asynchronous HTTP and WebSocket client library.
* [Ribbon](https://github.com/Netflix/ribbon) ⭐ 4,624 | 🐛 217 | 🌐 Java | 📅 2025-12-17 - Client-side IPC library that is battle-tested in the cloud.
* [unirest-java](https://github.com/Kong/unirest-java) ⭐ 2,706 | 🐛 2 | 🌐 Java | 📅 2026-01-26 - Simplified, lightweight HTTP client library.
* [Google HTTP Client](https://github.com/googleapis/google-http-java-client) ⭐ 1,432 | 🐛 75 | 🌐 Java | 📅 2026-02-06 - Pluggable HTTP transport abstraction with support for java.net.HttpURLConnection, Apache HTTP Client, Android, Google App Engine, XML, Gson, Jackson and Protobuf.
* [Riptide](https://github.com/zalando/riptide) ⭐ 331 | 🐛 21 | 🌐 Java | 📅 2026-02-05 - Client-side response routing for Spring's RestTemplate.
* [methanol](https://github.com/mizosoft/methanol) ⭐ 289 | 🐛 16 | 🌐 Java | 📅 2026-01-31 - HTTP client extensions library.
* [Apache HttpComponents](https://hc.apache.org/) - Toolset of low-level Java components focused on HTTP and associated protocols.
* [Avaje Http Client](https://avaje.io/http-client) - Wrapper on JDK 11's HttpClient that adds Feign-like interface among other enhancements.
* [Retrofit](https://square.github.io/retrofit/) - Typesafe REST client.

### Hypermedia Types

*Libraries that handle serialization to hypermedia types.*

* [Spring HATEOAS](https://github.com/spring-projects/spring-hateoas) ⭐ 1,077 | 🐛 277 | 🌐 Java | 📅 2026-01-26 - Standalone and Spring support for building hypermedia-based APIs using HAL, HAL FORMS, Collection+JSON, ALPS and UBER.
* [JSON-LD](https://github.com/jsonld-java/jsonld-java) ⭐ 386 | 🐛 54 | 🌐 Java | 📅 2024-01-10 - JSON-LD implementation.
* [Siren4J](https://github.com/eserating-chwy/siren4j) ⭐ 28 | 🐛 7 | 🌐 Java | 📅 2024-05-03 - Library for the Siren specification.
* [hate](https://github.com/blackdoor/hate) ⭐ 25 | 🐛 2 | 🌐 Java | 📅 2023-11-14 - Builds hypermedia-friendly objects according to HAL specification.

### IDE

*Integrated development environments that try to simplify several aspects of development.*

* [Eclipse](https://www.eclipse.org) - Established open-source project with support for lots of plugins and languages.
* [IntelliJ IDEA ![c]](https://www.jetbrains.com/idea/) - Supports many JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.
* [jGRASP](https://www.jgrasp.org) - Created to provide software visualizations that work in conjunction with the debugger such as Control Structure Diagrams, UML class diagrams and Object Viewer.
* [NetBeans](https://netbeans.apache.org) - Provides integration for several Java SE and EE features, from database access to HTML5.
* [SnapCode](https://reportmill.com/SnapCode/) - Modern IDE for Java running in the browser, focused on education.
* [Visual Studio Code](https://code.visualstudio.com/docs/languages/java) - Provides Java support for lightweight projects with a simple, modern workflow by using extensions from the internal marketplace.

### Imagery

*Libraries that assist with the creation, evaluation or manipulation of graphical images.*

* [ZXing](https://github.com/zxing/zxing) ⭐ 33,841 | 🐛 9 | 🌐 Java | 📅 2026-02-04 - Multi-format 1D/2D barcode image processing library.
* [Thumbnailator](https://github.com/coobird/thumbnailator) ⭐ 5,386 | 🐛 53 | 🌐 Java | 📅 2026-01-08 - High-quality thumbnail generation library.
* [TwelveMonkeys](https://github.com/haraldk/TwelveMonkeys) ⭐ 2,091 | 🐛 62 | 🌐 Java | 📅 2026-02-05 - Collection of plugins that extend the number of supported image file formats.
* [Tess4J](https://github.com/nguyenq/tess4j) ⭐ 1,731 | 🐛 26 | 🌐 Java | 📅 2026-01-17 - JNA wrapper for Tesseract OCR API.
* [Imgscalr](https://github.com/rkalla/imgscalr) ⭐ 1,247 | 🐛 43 | 🌐 Java | 📅 2023-10-21 - Simple, efficient and hardware-accelerated image-scaling library implemented in pure Java 2D.
* [image-comparison](https://github.com/romankh3/image-comparison) ⭐ 388 | 🐛 34 | 🌐 Java | 📅 2025-06-11 - Library that compares 2 images with the same sizes and shows the differences visually by drawing rectangles. Some parts of the image can be excluded from the comparison.
* [vips-ffm](https://github.com/lopcode/vips-ffm) ⭐ 103 | 🐛 6 | 🌐 Java | 📅 2026-02-02 - Comprehensive bindings for libvips, using Java's "Foreign Function & Memory" API.
* [Barcode-Lib4J](https://github.com/vws-java/Barcode-Lib4J) ⭐ 9 | 🐛 0 | 🌐 Java | 📅 2025-12-23 - Generates QR Code, DataMatrix, and other 1D/2D barcodes as vector (PDF, EPS, SVG) and raster (PNG, BMP, JPG) images with DPI awareness, high precision, and CMYK color model support.
* [scrimage](https://sksamuel.github.io/scrimage) - Immutable, functional, and performant JVM library for manipulation of images.

### Introspection

*Libraries that help make the Java introspection and reflection API easier and faster to use.*

* [Reflections](https://github.com/ronmamo/reflections) ⭐ 4,775 | 🐛 122 | 🌐 Java | 📅 2024-06-17 - Reflections scans your classpath, indexes the metadata, allows you to query it on runtime and may save and collect that information for many modules within your project.
* [ClassGraph](https://github.com/classgraph/classgraph) ⭐ 2,955 | 🐛 44 | 🌐 Java | 📅 2025-10-10 - ClassGraph (formerly FastClasspathScanner) is an uber-fast, ultra-lightweight, parallelized classpath scanner and module scanner for Java, Scala, Kotlin and other JVM languages.
* [jOOR](https://github.com/jOOQ/jOOR) ⭐ 2,832 | 🐛 25 | 🌐 Java | 📅 2025-01-06 - jOOR stands for jOOR Object Oriented Reflection. It is a simple wrapper for the java.lang.reflect package.
* [ReflectASM](https://github.com/EsotericSoftware/reflectasm) ⭐ 1,545 | 🐛 17 | 🌐 Java | 📅 2025-06-05 - ReflectASM is a very small Java library that provides high performance reflection by using code generation.
* [Mirror](http://projetos.vidageek.net/mirror/mirror/) - Mirror was created to bring light to a simple problem, usually named ReflectionUtil, which is on almost all projects that rely on reflection to do advanced tasks.
* [Objenesis](http://objenesis.org) - Allows dynamic instantiation without default constructor, e.g. constructors which have required arguments, side effects or throw exceptions.

### Job Scheduling

*Libraries for scheduling background jobs.*

* [Quartz](https://github.com/quartz-scheduler/quartz) ⭐ 6,683 | 🐛 69 | 🌐 Java | 📅 2026-01-30 - Feature-rich, open source job scheduling library that can be integrated within virtually any Java application.
* [shedlock](https://github.com/lukas-krecan/ShedLock) ⭐ 4,092 | 🐛 22 | 🌐 Java | 📅 2026-02-06 - Makes sure that your scheduled tasks are executed at most once at the same time. If a task is being executed on one node, it acquires a lock which prevents execution of the same task from another node or thread.
* [JobRunr](https://github.com/jobrunr/jobrunr) ⭐ 2,855 | 🐛 5 | 🌐 Java | 📅 2026-02-06 - Job scheduling library which utilizes lambdas for fire-and-forget, delayed and recurring jobs. Guarantees execution by single scheduler instance using optimistic locking. Has features for persistence, minimal dependencies and is embeddable.
* [db-scheduler](https://github.com/kagkarlsson/db-scheduler) ⭐ 1,496 | 🐛 93 | 🌐 Java | 📅 2026-02-04 - Persistent and cluster-friendly scheduler.
* [easy-batch](https://github.com/j-easy/easy-batch) ⭐ 628 | 🐛 16 | 🌐 Java | 📅 2023-03-20 - Set up batch jobs with simple processing pipelines. Records are read in sequence from a data source, processed in pipeline and written in batches to a data sink.
* [Sundial](https://github.com/knowm/Sundial) ⭐ 275 | 🐛 13 | 🌐 Java | 📅 2024-07-15 - Lightweight framework to simply define jobs, define triggers and start the scheduler.
* [Wisp](https://github.com/Coreoz/Wisp) ⭐ 141 | 🐛 7 | 🌐 Java | 📅 2026-01-26 - Simple library with minimal footprint and straightforward API.

### JSON

*Libraries for serializing and deserializing JSON to and from Java objects.*

* [fastjson](https://github.com/alibaba/fastjson) ⚠️ Archived - Very fast processor with no additional dependencies and full data binding.
* [Gson](https://github.com/google/gson) ⭐ 24,336 | 🐛 332 | 🌐 Java | 📅 2026-02-01 - Serializes objects to JSON and vice versa. Good performance with on-the-fly usage.
* [Moshi](https://github.com/square/moshi) ⭐ 10,102 | 🐛 97 | 🌐 Kotlin | 📅 2026-02-05 - Modern JSON library, less opinionated and uses built-in types like List and Map.
* [Jackson](https://github.com/FasterXML/jackson) ⭐ 9,662 | 🐛 0 | 📅 2026-01-19 - Similar to GSON, but offers performance gains if you need to instantiate the library more often.
* [JsonPath](https://github.com/json-path/JsonPath) ⭐ 9,386 | 🐛 429 | 🌐 Java | 📅 2026-02-04 - Extract data from JSON using XPATH-like syntax.
* [LoganSquare](https://github.com/bluelinelabs/LoganSquare) ⭐ 3,191 | 🐛 83 | 🌐 Java | 📅 2021-12-07 - JSON parsing and serializing library based on Jackson's streaming API. Outperforms GSON & Jackson's library.
* [Jolt](https://github.com/bazaarvoice/jolt) ⭐ 1,661 | 🐛 409 | 🌐 Java | 📅 2025-07-12 - JSON to JSON transformation tool.
* [DSL-JSON](https://github.com/ngs-doo/dsl-json) ⭐ 1,061 | 🐛 42 | 🌐 Java | 📅 2024-12-03 - JSON library with advanced compile time databinding.
* [HikariJSON](https://github.com/brettwooldridge/HikariJSON) ⭐ 467 | 🐛 6 | 🌐 Java | 📅 2023-03-21 - High-performance JSON parser, 2x faster than Jackson.
* [jackson-modules-java8](https://github.com/FasterXML/jackson-modules-java8) ⭐ 417 | 🐛 17 | 🌐 Java | 📅 2026-01-19 - Set of Jackson modules for Java 8 datatypes and features.
* [JSON-io](https://github.com/jdereg/json-io) ⭐ 369 | 🐛 2 | 🌐 Java | 📅 2026-02-02 - Convert Java to JSON/TOON and back. Supports complex object graphs, cyclic references, and TOON format for 40-50% LLM token savings.
* [JsonSurfer](https://github.com/jsurfer/JsonSurfer) ⭐ 314 | 🐛 16 | 🌐 Java | 📅 2024-06-03 - Streaming JsonPath processor dedicated to processing big and complicated JSON data.
* [Jackson-datatype-money](https://github.com/zalando/jackson-datatype-money) ⚠️ Archived - Open-source Jackson module to support JSON serialization and deserialization of JavaMoney data types.
* [Yasson](https://github.com/eclipse-ee4j/yasson) ⭐ 215 | 🐛 136 | 🌐 Java | 📅 2025-07-13 - Binding layer between classes and JSON documents similar to JAXB.
* [Avaje Jsonb](https://avaje.io/jsonb/) - Reflection-free Json binding via source code generation with Jackson-like annotations.
* [Genson](http://genson.io) - Powerful and easy-to-use Java-to-JSON conversion library.
* [jsoniter](http://jsoniter.com) - Fast and flexible library with iterator and lazy parsing API.

### JVM and JDK

*Current implementations of the JVM/JDK.*

* [Graal](https://github.com/oracle/graal) ⭐ 21,453 | 🐛 809 | 🌐 Java | 📅 2026-02-07 - Polyglot embeddable JVM. (GPL-2.0-only WITH Classpath-exception-2.0)
* [Dragonwell8](https://github.com/alibaba/dragonwell8) ⭐ 4,318 | 🐛 172 | 🌐 Java | 📅 2026-02-06 - Downstream version of OpenJDK optimized for online e-commerce, financial, logistics applications.
* [OpenJ9](https://github.com/eclipse/openj9) ⭐ 3,502 | 🐛 3,012 | 🌐 Java | 📅 2026-02-07 - High performance, enterprise-calibre, flexibly licensed, openly-governed cross-platform JVM extending and augmenting the runtime technology components from the Eclipse OMR and OpenJDK project.
* [ParparVM](https://github.com/codenameone/CodenameOne/tree/master/vm) ⭐ 1,820 | 🐛 556 | 🌐 Java | 📅 2026-02-08 - VM with non-blocking, concurrent GC for iOS. (GPL-2.0-only WITH Classpath-exception-2.0)
* [Microsoft JDK](https://github.com/microsoft/openjdk) ⭐ 341 | 🐛 11 | 📅 2025-10-28 - Microsoft Build of OpenJDK, Free, Open Source, Freshly Brewed!
* [Which JDK](https://whichjdk.com/) - Overview of common JVMs with pros and cons.
* [Adopt Open JDK](https://adoptopenjdk.net) - Community-driven OpenJDK builds, including both HotSpot and OpenJ9.
* [Corretto](https://aws.amazon.com/corretto/) - No-cost, multiplatform, production-ready distribution of OpenJDK by Amazon. (GPL-2.0-only WITH Classpath-exception-2.0)
* [Liberica JDK](https://bell-sw.com) - Built from OpenJDK, thoroughly tested and passed the JCK. (GPL-2.0-only WITH Classpath-exception-2.0)
* [Open JDK](https://openjdk.java.net) - Open JDK community home. (GPL-2.0-only WITH Classpath-exception-2.0)
* [RedHat Open JDK](https://developers.redhat.com/products/openjdk/overview) - RedHat's OpenJDK distribution. (GPL-2.0-only WITH Classpath-exception-2.0)
* [SAP Machine](https://sap.github.io/SapMachine/) - SAP's no-cost, rigorously tested and JCK-verified OpenJDK friendly fork. (GPL-2.0-only WITH Classpath-exception-2.0)
* [Zulu](https://www.azul.com/products/zulu-community/) - OpenJDK builds for Windows, Linux, and macOS. (GPL-2.0-only WITH Classpath-exception-2.0)

### Logging

*Libraries that log the behavior of an application.*

* [p6spy](https://github.com/p6spy/p6spy) ⭐ 2,222 | 🐛 39 | 🌐 Java | 📅 2022-02-21 - Enables logging for all JDBC transactions without changes to the code.
* [Logbook](https://github.com/zalando/logbook) ⭐ 2,013 | 🐛 36 | 🌐 Java | 📅 2026-02-06 - Extensible, open-source library for HTTP request and response logging.
* [OpenTracing Toolbox](https://github.com/zalando/opentracing-toolbox) ⚠️ Archived - Collection of libraries that build on top of OpenTracing and provide extensions and plugins to existing instrumentations.
* [Echopraxia](https://github.com/tersesystems/echopraxia) ⭐ 58 | 🐛 2 | 🌐 Java | 📅 2025-02-20 - API designed around structured logging, rich context, and conditional logging. There are Logback and Log4J2 implementations, but Echopraxia's API is completely dependency-free, meaning it can be implemented with any logging API.
* [Apache Log4j 2](https://logging.apache.org/log4j/) - Complete rewrite with a powerful plugin and configuration architecture.
* [Graylog](https://www.graylog.org) - Open-source aggregator suited for extended role and permission management. (GPL-3.0-only)
* [Kibana](https://www.elastic.co/kibana) - Analyzes and visualizes log files. Some features require payment.
* [Logback](http://logback.qos.ch) - Robust logging library with interesting configuration options via Groovy.
* [Logstash](https://www.elastic.co/logstash) - Tool for managing log files.
* [SLF4J](http://www.slf4j.org) - Abstraction layer/simple logging facade.
* [tinylog](https://tinylog.org/v2/) - Lightweight logging framework with static logger class.
* [Flogger](https://google.github.io/flogger/) - Flogger is a fluent logging API for Java. It supports a wide variety of features, and has many benefits over existing logging APIs.

### Machine Learning

*Tools that provide specific statistical algorithms for learning from data.*

* [Smile](https://github.com/haifengl/smile) ⭐ 6,336 | 🐛 6 | 🌐 Java | 📅 2026-02-01 - Statistical Machine Intelligence and Learning Engine provides a set of machine learning algorithms and a visualization library.
* [m2cgen](https://github.com/BayesWitnesses/m2cgen) ⭐ 2,954 | 🐛 60 | 🌐 Python | 📅 2024-08-03 - CLI tool to transpile models into native code.
* [Oryx 2](https://github.com/OryxProject/oryx) ⚠️ Archived - Framework for building real-time, large-scale machine learning applications. Includes end-to-end applications for collaborative filtering, classification, regression, and clustering.
* [Siddhi](https://github.com/siddhi-io/siddhi) ⭐ 1,577 | 🐛 124 | 🌐 Java | 📅 2025-08-08 - Cloud native streaming and complex event processing engine.
* [JSAT](https://github.com/EdwardRaff/JSAT) ⭐ 800 | 🐛 15 | 🌐 Java | 📅 2022-12-16 - Algorithms for pre-processing, classification, regression, and clustering with support for multi-threaded execution. (GPL-3.0-only)
* [Neureka](https://github.com/Gleethos/neureka) ⭐ 85 | 🐛 2 | 🌐 Java | 📅 2026-01-25 - A lightweight, platform independent, OpenCL accelerated nd-array/tensor library.
* [Intelligent java](https://github.com/Barqawiz/IntelliJava) ⭐ 64 | 🐛 6 | 🌐 Java | 📅 2024-02-18 - Seamlessly integrate with remote deep learning and language models programmatically.
* [Apache Flink](https://flink.apache.org) - Fast, reliable, large-scale data processing engine.
* [Apache Mahout](https://mahout.apache.org) - Scalable algorithms focused on collaborative filtering, clustering and classification.
* [DatumBox](http://www.datumbox.com) - Provides several algorithms and pre-trained models for natural language processing.
* [Deeplearning4j](https://deeplearning4j.org) - Distributed and multi-threaded deep learning library.
* [DJL](https://djl.ai) - High-level and engine-agnostic framework for deep learning.
* [H2O ![c]](https://www.h2o.ai) - Analytics engine for statistics over big data.
* [oj! Algorithms](https://www.ojalgo.org/) - High-performance mathematics, linear algebra and optimisation needed for data science, machine learning and scientific computing.
* [Tribuo](https://tribuo.org/) - Provides tools for classification, regression, clustering, model development and interfaces with other libraries such as scikit-learn, pytorch and TensorFlow.
* [Weka](https://www.cs.waikato.ac.nz/ml/weka/) - Collection of algorithms for data mining tasks ranging from pre-processing to visualization. (GPL-3.0-only)

### Messaging

*Tools that help send messages between clients to ensure protocol independency.*

* [EventBus](https://github.com/greenrobot/EventBus) ⭐ 24,760 | 🐛 147 | 🌐 Java | 📅 2024-02-21 - Simple publish/subscribe event bus.
* [AutoMQ](https://github.com/AutoMQ/automq-for-kafka) ⭐ 9,472 | 🐛 80 | 🌐 Java | 📅 2026-02-06 - AutoMQ is a cloud-native, serverless reinvented Kafka that is easily scalable, manage-less and cost-effective.
* [Aeron](https://github.com/real-logic/Aeron) ⭐ 8,434 | 🐛 17 | 🌐 Java | 📅 2026-02-07 - Efficient, reliable, unicast and multicast message transport.
* [JeroMQ](https://github.com/zeromq/jeromq) ⭐ 2,441 | 🐛 101 | 🌐 Java | 📅 2025-11-30 - Implementation of ZeroMQ.
* [Smack](https://github.com/igniterealtime/Smack) ⭐ 2,416 | 🐛 33 | 🌐 Java | 📅 2025-12-02 - Cross-platform XMPP client library.
* [RabbitMQ Java client](https://github.com/rabbitmq/rabbitmq-java-client) ⭐ 1,297 | 🐛 21 | 🌐 Java | 📅 2026-02-06 - RabbitMQ client.
* [Nakadi](https://github.com/zalando/nakadi) ⚠️ Archived - Provides a RESTful API on top of Kafka.
* [NATS client](https://github.com/nats-io/nats.java) ⭐ 647 | 🐛 6 | 🌐 Java | 📅 2026-02-06 - NATS client.
* [Emissary](https://github.com/joel-jeremy/emissary) ⭐ 104 | 🐛 5 | 🌐 Java | 📅 2026-02-06 - Simple, lightweight, yet FAST messaging library for decoupling messages (requests and events) and message handlers.
* [Apache ActiveMQ](https://activemq.apache.org) - Message broker that implements JMS and converts synchronous to asynchronous communication.
* [Apache Camel](https://camel.apache.org) - Glues together different transport APIs via Enterprise Integration Patterns.
* [Apache Kafka](https://kafka.apache.org) - High-throughput distributed messaging system.
* [Apache Pulsar](https://pulsar.apache.org) - Distributed pub/sub-messaging system.
* [Apache RocketMQ](https://rocketmq.apache.org) - Fast, reliable, and scalable distributed messaging platform.
* [Apache Qpid](https://qpid.apache.org) - Apache Qpid makes messaging tools that speak AMQP and support many languages and platforms.
* [Hermes](http://hermes.allegro.tech) - Fast and reliable message broker built on top of Kafka.

### Microservice

*Tools for creating and managing microservices.*

* [Sentinel](https://github.com/alibaba/Sentinel) ⭐ 23,057 | 🐛 839 | 🌐 Java | 📅 2026-01-26 - Flow control component enabling reliability, resilience and monitoring for microservices.
* [Eureka](https://github.com/Netflix/eureka) ⭐ 12,697 | 🐛 137 | 🌐 Java | 📅 2026-01-23 - REST-based service registry for resilient load balancing and failover.
* [Armeria](https://github.com/line/armeria) ⭐ 5,070 | 🐛 707 | 🌐 Java | 📅 2026-02-05 - Asynchronous RPC/REST client/server library built on top of Java 8, Netty, HTTP/2, Thrift and gRPC.
* [OpenAI-Java](https://github.com/TheoKanning/openai-java) ⚠️ Archived - Java libraries for using OpenAI's GPT-3 API.
* [JDA](https://github.com/DV8FromTheWorld/JDA) ⭐ 4,624 | 🐛 60 | 🌐 Java | 📅 2026-02-07 - Wrapping of the Discord REST API and its WebSocket events.
* [kubernetes-client](https://github.com/fabric8io/kubernetes-client) ⭐ 3,616 | 🐛 102 | 🌐 Java | 📅 2026-02-04 - Client provides access to the full Kubernetes & OpenShift REST APIs via a fluent DSL.
* [consul-api](https://github.com/Ecwid/consul-api) ⭐ 424 | 🐛 71 | 🌐 Java | 📅 2023-05-05 - Client for the Consul API: a distributed, highly available and datacenter-aware registry/discovery service.
* [ActiveRPC](https://rpc.activej.io) - Lightweight and fast library for complex high-load distributed applications and Memcached-like solutions.
* [Helidon](https://helidon.io) - Two-style approach for writing microservices: Functional-reactive and as an implementation of MicroProfile.
* [KeenType](https://github.com/DaveJarvis/KeenType) - Modernized version of a Java-based implementation of the New Typesetting System, which was heavily based on Donald E. Knuth's original TeX.
* [Micronaut](https://micronaut.io) - Modern full-stack framework with focus on modularity, minimal memory footprint and startup time.
* [Nacos](https://nacos.io) - Dynamic service discovery, configuration and service management platform for building cloud native applications.
* [Quarkus](https://quarkus.io) - Kubernetes stack tailored for the HotSpot and Graal VM.

### Miscellaneous

*Everything else.*

* [Design Patterns](https://github.com/iluwatar/java-design-patterns) ⭐ 93,699 | 🐛 221 | 🌐 Java | 📅 2026-01-17 - Implementation and explanation of the most common design patterns.
* [FizzBuzz Enterprise Edition](https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition) ⭐ 23,218 | 🐛 538 | 🌐 Java | 📅 2024-07-15 - No-nonsense implementation of FizzBuzz made by serious businessmen for serious business purposes. (No explicit license)
* [Modern Java - A Guide to Java 8](https://github.com/winterbe/java8-tutorial) ⭐ 16,779 | 🐛 19 | 🌐 Java | 📅 2023-08-11 - Popular Java 8 guide.
* [J2ObjC](https://github.com/google/j2objc) ⭐ 6,037 | 🐛 96 | 🌐 Java | 📅 2026-02-05 - Java-to-Objective-C translator for porting Android libraries to iOS.
* [OctoLinker](https://github.com/OctoLinker/OctoLinker) ⭐ 5,351 | 🐛 62 | 🌐 HTML | 📅 2023-10-02 - Browser extension which allows to navigate through code on GitHub more efficiently.
* [Svix](https://github.com/svix/svix-webhooks/tree/main/java) ⭐ 3,096 | 🐛 57 | 🌐 Rust | 📅 2026-02-06 - Library for the Svix API to send webhooks and verify signatures.
* [Jimfs](https://github.com/google/jimfs) ⭐ 2,528 | 🐛 37 | 🌐 Java | 📅 2026-02-02 - In-memory file system.
* [webcam-capture](https://github.com/sarxos/webcam-capture) ⭐ 2,343 | 🐛 314 | 🌐 Java | 📅 2025-11-08 - Library for using built-in and external webcams directly in Java.
* [LittleProxy](https://github.com/adamfisk/LittleProxy) ⭐ 2,117 | 🐛 111 | 🌐 PHP | 📅 2024-07-08 - High performance HTTP proxy atop Netty's event-based networking library.
* [CQEngine](https://github.com/npgall/cqengine) ⭐ 1,768 | 🐛 81 | 🌐 Java | 📅 2023-12-27 - Ultra-fast, SQL-like queries on Java collections.
* [Maven Wrapper](https://github.com/takari/maven-wrapper) ⚠️ Archived - Analogue of Gradle Wrapper for Maven, allows building projects without installing maven.
* [jsweet](https://github.com/cincheo/jsweet) ⭐ 1,488 | 🐛 164 | 🌐 Java | 📅 2023-12-16 - Source transpiler to TypeScript/JavaScript.
* [FF4J](https://github.com/ff4j/ff4j) ⭐ 1,443 | 🐛 39 | 🌐 Java | 📅 2026-01-26 - Feature Flags for Java.
* [Simple Java Mail](https://github.com/bbottema/simple-java-mail) ⭐ 1,290 | 🐛 39 | 🌐 Java | 📅 2025-06-02 - Mailing with a clean and fluent API.
* [JBot](https://github.com/rampatra/jbot) ⭐ 1,204 | 🐛 78 | 🌐 Java | 📅 2025-10-08 - Framework for building chatbots. (GPL-3.0-only)
* [Polyglot for Maven](https://github.com/takari/polyglot-maven) ⭐ 916 | 🐛 46 | 🌐 Java | 📅 2025-11-20 - Extensions for Maven 3.3.1+ that allows writing the POM model in dialects other than XML.
* [TypeTools](https://github.com/jhalterman/typetools) ⭐ 628 | 🐛 24 | 🌐 Java | 📅 2023-04-12 - Tools for resolving generic types.
* [Membrane Service Proxy](https://github.com/membrane/service-proxy) ⭐ 557 | 🐛 25 | 🌐 Java | 📅 2026-02-07 - Open-source, reverse-proxy framework.
* [jOOX](https://github.com/jooq/joox) ⭐ 505 | 🐛 55 | 🌐 Java | 📅 2024-10-04 - Simple wrapper for the org.w3c.dom package, to allow for fluent XML document creation and manipulation with an API inspired by jQuery.
* [PipelinR](https://github.com/sizovs/pipelinr) ⭐ 484 | 🐛 0 | 🌐 Java | 📅 2025-08-27 - Small utility library for using handlers and commands with pipelines.
* [yGuard](https://github.com/yWorks/yGuard) ⭐ 456 | 🐛 14 | 🌐 Java | 📅 2025-06-17 - Obfuscation via renaming and shrinking.
* [Smooks](https://github.com/smooks/smooks) ⭐ 415 | 🐛 35 | 🌐 Java | 📅 2025-11-24 - Framework for fragment-based message processing. (Apache-2.0 OR LGPL-3.0-or-later)
* [Modernizer](https://github.com/gaul/modernizer-maven-plugin) ⭐ 385 | 🐛 21 | 🌐 Java | 📅 2026-02-01 - Detect uses of legacy Java APIs.
* [MinimalFTP](https://github.com/Guichaguri/MinimalFTP) ⭐ 185 | 🐛 1 | 🌐 Java | 📅 2025-06-15 - Lightweight, small and customizable FTP server.
* [JEmoji](https://github.com/felldo/JEmoji) ⭐ 104 | 🐛 2 | 🌐 Java | 📅 2026-02-03 - An auto-generated emoji library that provides type-safe direct access to emojis and alias support for Discord, Slack, GitHub and many more features.
* [XMLBeam](https://github.com/SvenEwald/xmlbeam) ⭐ 76 | 🐛 5 | 🌐 Java | 📅 2025-08-07 - Processes XML by using annotations or XPath within code.
* [RR4J](https://github.com/Kartikvk1996/RR4J) ⭐ 25 | 🐛 0 | 🌐 C++ | 📅 2022-03-24 - RR4J is a tool that records java bytecode execution and later allows developers to replay locally.
* [IP2Location.io Java SDK](https://github.com/ip2location/ip2location-io-java) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2025-12-31 - Wrapper for the IP2Location.io Geolocation API and the IP2WHOIS domain WHOIS API.
* [ISBN core](https://github.com/ladutsko/isbn-core) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2025-12-27 - A small library that contains a representation object of ISBN-10 and ISBN-13 and tools to parse, validate and format one.
* [JBake](https://jbake.org) - Static website generator.
* [JBang](https://www.jbang.dev/) - JBang makes it easy to use Java for scripting. It lets you use a single file for code and dependency management and allows you to run it directly.
* [JCuda](http://jcuda.org) - JCuda offers Java bindings for CUDA and CUDA-related libraries.
* [JObfuscator![c]](https://www.pelock.com/products/jobfuscator) - Source code obfuscator.
* [Joda-Money](https://www.joda.org/joda-money/) - Basic currency and money classes and algorithms not provided by the JDK.
* [JPad](http://jpad.io) - Snippet runner.
* [OpenRefine](http://openrefine.org) - Tool for working with messy data: cleaning, transforming, extending it with web services and linking it to databases.
* [Togglz](https://www.togglz.org) - Implementation of the Feature Toggles pattern.

### Mobile Development

*Tools for creating or managing mobile applications.*

* [Codename One](https://www.codenameone.com) - Cross-platform solution for writing native mobile apps. (GPL-2.0-only WITH Classpath-exception-2.0)
* [MobileUI](https://mobileui.dev) - Cross-platform framework for developing mobile apps with native UI in Java and Kotlin.
* [Multi-OS Engine](https://multi-os-engine.org) - Open-source, cross-platform engine to develop native mobile (iOS, Android, etc.) apps.

### Monitoring

*Tools that observe/monitor applications in production by providing telemetry.*

* [Pinpoint](https://github.com/naver/pinpoint) ⭐ 13,804 | 🐛 509 | 🌐 Java | 📅 2026-02-06 - Open-source APM tool.
* [Dropwizard Metrics](https://github.com/dropwizard/metrics) ⭐ 7,855 | 🐛 11 | 🌐 Java | 📅 2026-02-02 - Expose metrics via JMX or HTTP and send them to a database.
* [HertzBeat](https://github.com/dromara/hertzbeat) ⭐ 7,066 | 🐛 309 | 🌐 Java | 📅 2026-02-08 - Real-time monitoring system with custom-monitor and agentless.
* [hippo4j](https://github.com/opengoofy/hippo4j/blob/develop/README-EN.md) ⭐ 5,986 | 🐛 140 | 🌐 Java | 📅 2025-10-31 - Dynamic and observable thread pool framework.
* [Micrometer](https://github.com/micrometer-metrics/micrometer) ⭐ 4,801 | 🐛 286 | 🌐 Java | 📅 2026-02-07 - Vendor-neutral metrics/observability facade for the most popular metrics/observability libraries.
* [JavaMelody](https://github.com/javamelody/javamelody) ⭐ 3,034 | 🐛 46 | 🌐 Java | 📅 2026-02-02 - Performance monitoring and profiling.
* [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-java) ⭐ 2,353 | 🐛 173 | 🌐 Java | 📅 2026-02-06 - Instrument, generate, collect, and export telemetry data to help you analyze your software’s performance and behavior.
* [Prometheus](https://github.com/prometheus/client_java) ⭐ 2,264 | 🐛 129 | 🌐 Java | 📅 2026-02-08 - Provides a multi-dimensional data model, DSL, autonomous server nodes and much more.
* [jmxtrans](https://github.com/jmxtrans/jmxtrans) ⭐ 1,703 | 🐛 140 | 🌐 Java | 📅 2022-09-05 - Connect to multiple JVMs and query them for their attributes via JMX. Its query language is based on JSON, which allows non-Java programmers to access the JVM attributes. Supports different output writes, including Graphite, Ganglia, and StatsD.
* [Stagemonitor](https://github.com/stagemonitor/stagemonitor) ⚠️ Archived - Open-source performance monitoring and transaction tracing for JVM apps.
* [Sentry ![c]](https://github.com/getsentry/sentry-java) ⭐ 1,297 | 🐛 227 | 🌐 Kotlin | 📅 2026-02-06 - Integration with [Sentry](https://github.com/getsentry/sentry) ⭐ 43,116 | 🐛 2,045 | 🌐 Python | 📅 2026-02-08, an application error tracking and performance analysis platform.
* [Datadog ![c]](https://github.com/DataDog/dd-trace-java) ⭐ 690 | 🐛 311 | 🌐 Java | 📅 2026-02-07 - Modern monitoring & analytics.
* [Automon](https://github.com/stevensouza/automon) ⭐ 573 | 🐛 1 | 🌐 Java | 📅 2024-10-18 - Combines the power of AOP with monitoring and/or logging tools.
* [Jaeger client](https://github.com/jaegertracing/jaeger-client-java) ⚠️ Archived - Jaeger client.
* [Micrometer Tracing](https://github.com/micrometer-metrics/tracing) ⭐ 290 | 🐛 26 | 🌐 Java | 📅 2026-02-05 - Vendor-neutral distributed tracing facade for the most popular tracer libraries.
* [nudge4j](https://github.com/lorenzoongithub/nudge4j) ⭐ 163 | 🐛 2 | 🌐 Java | 📅 2020-04-12 - Remote developer console from the browser for Java 8 via bytecode injection.
* [Sysmon](https://github.com/palantir/Sysmon) ⚠️ Archived - Lightweight platform monitoring tool for Java VMs.
* [Failsafe Actuator](https://github.com/zalando/failsafe-actuator) ⚠️ Archived - Out of the box monitoring of Failsafe Circuit Breaker in Spring-Boot environment.
* [SPM ![c]](https://github.com/sematext/sematext-agent-java) ⭐ 24 | 🐛 17 | 🌐 Java | 📅 2026-02-06 - Performance monitor with distributing transaction tracing for JVM apps.
* [Apitally](https://github.com/apitally/apitally-java) ⭐ 5 | 🐛 1 | 🌐 Java | 📅 2026-02-07 - Simple, privacy-focused API monitoring, analytics and request logging for Spring Boot apps.
* [Boot Usage Spring Boot Starter](https://github.com/dhruv-15-03/boot-usage) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2026-01-21 - Spring Boot Actuator extension providing application startup and runtime metrics including JVM uptime, memory usage, and CPU load.
* [Glowroot](https://glowroot.org) - Open-source Java APM.
* [inspectIT](https://www.inspectit.rocks) - Captures detailed run-time information via hooks that can be changed on the fly. It supports tracing over multiple systems via the OpenTracing API and can correlate the data with end user monitoring.
* [Instrumental ![c]](https://instrumentalapp.com) - Real-time Java application performance monitoring. A commercial service with free development accounts.
* [Jolokia](https://jolokia.org) - JMX over REST.
* [zipkin](https://zipkin.io) - Distributed tracing system which gathers timing data needed to troubleshoot latency problems in microservice architectures.

### Native

*For working with platform-specific native libraries.*

* [JNA](https://github.com/java-native-access/jna) ⭐ 8,886 | 🐛 119 | 🌐 Java | 📅 2026-01-01 - Work with native libraries without writing JNI. Also provides interfaces to common system libraries.
* [JavaCPP](https://github.com/bytedeco/javacpp) ⭐ 4,686 | 🐛 110 | 🌐 Java | 📅 2025-12-09 - Provides efficient and easy access to native C++.
* [JNR](https://github.com/jnr/jnr-ffi) ⭐ 1,318 | 🐛 97 | 🌐 Java | 📅 2025-10-24 - Work with native libraries without writing JNI. Also provides interfaces to common system libraries. Same goals as JNA, but faster, and serves as the basis for the upcoming [Project Panama](http://openjdk.java.net/projects/panama).
* [Aparapi](https://github.com/Syncleus/aparapi) ⭐ 483 | 🐛 60 | 🌐 Java | 📅 2022-09-30 - Converts bytecode to OpenCL which allows execution on GPUs.
* [native-lib-loader](https://github.com/scijava/native-lib-loader) ⭐ 216 | 🐛 9 | 🌐 Java | 📅 2024-10-20 - Native library loader for extracting and loading native libraries from Java.

### Natural Language Processing

*Libraries that specialize in processing text.*

* [CogCompNLP](https://github.com/CogComp/cogcomp-nlp) ⭐ 480 | 🐛 200 | 🌐 Java | 📅 2023-07-07 - Provides common annotators for plain text input. (Research and Academic Use License)
* [Hypherator](https://github.com/ejossev/hypherator-java) ⭐ 3 | 🐛 0 | 🌐 Java | 📅 2025-06-30 - Java hyphenation library with iterator-like interface. Can be used out-of-the box - dictionaries for multiple languages are bundled in.
* [CoreNLP](https://nlp.stanford.edu/software/corenlp.shtml) - Provides a set of fundamental tools for tasks like tagging, named entity recognition, and sentiment analysis. (GPL-3.0-or-later)
* [DKPro](https://dkpro.github.io) - Collection of reusable NLP tools for linguistic pre-processing, machine learning, lexical resources, etc.
* [LingPipe](http://alias-i.com/lingpipe/) - Toolkit for tasks ranging from POS tagging to sentiment analysis.

### Networking

*Libraries for building network servers.*

* [Dubbo](https://github.com/apache/dubbo) ⭐ 41,721 | 🐛 912 | 🌐 Java | 📅 2026-02-05 - High-performance RPC framework.
* [gRPC-java](https://github.com/grpc/grpc-java) ⭐ 11,968 | 🐛 509 | 🌐 Java | 📅 2026-02-06 - RPC framework based on protobuf and HTTP/2.
* [sshj](https://github.com/hierynomus/sshj) ⭐ 2,632 | 🐛 280 | 🌐 Java | 📅 2025-05-14 - Programmatically use SSH, SCP or SFTP.
* [KryoNet](https://github.com/EsotericSoftware/kryonet) ⭐ 1,849 | 🐛 69 | 🌐 Java | 📅 2021-02-22 - Provides a clean and simple API for efficient TCP and UDP client/server network communication using NIO and Kryo.
* [ServiceTalk](https://github.com/apple/servicetalk) ⭐ 1,018 | 🐛 74 | 🌐 Java | 📅 2026-02-06 - Framework built on Netty with APIs tailored to specific protocols and support for multiple programming paradigms.
* [Comsat](https://github.com/puniverse/comsat) ⭐ 596 | 🐛 34 | 🌐 Java | 📅 2017-11-27 - Integrates standard Java web-related APIs with Quasar fibers and actors.
* [Drift](https://github.com/airlift/drift) ⭐ 246 | 🐛 8 | 🌐 Java | 📅 2025-09-11 - Easy-to-use, annotation-based library for creating Thrift clients and serializable types.
* [TLS Channel](https://github.com/marianobarrios/tls-channel) ⭐ 208 | 🐛 3 | 🌐 Java | 📅 2026-02-06 - Implements a ByteChannel interface over SSLEngine, enabling easy-to-use (socket-like) TLS.
* [Fluency](https://github.com/komamitsu/fluency) ⭐ 163 | 🐛 14 | 🌐 Java | 📅 2026-01-20 - High throughput data ingestion logger to Fluentd and Fluent Bit.
* [urnlib](https://github.com/slub/urnlib) ⭐ 34 | 🐛 1 | 🌐 Java | 📅 2025-12-30 - Represent, parse and encode URNs, as in RFC 2141. (GPL-3.0-only)
* [Commons-networking](https://github.com/CiscoSE/commons-networking) ⭐ 20 | 🐛 0 | 🌐 Java | 📅 2022-02-08 - Client for server-sent events (SSE).
* [Grizzly](https://javaee.github.io/grizzly/) - NIO framework. Used as a network layer in Glassfish.
* [MINA](https://mina.apache.org) - Abstract, event-driven async I/O API for network operations over TCP/IP and UDP/IP via Java NIO.
* [Netty](https://netty.io) - Framework for building high-performance network applications.
* [Undertow](http://undertow.io) - Web server providing both blocking and non-blocking APIs based on NIO. Used as a network layer in WildFly. (LGPL-2.1-only)

### ORM

*APIs that handle the persistence of objects.*

* [MyBatis](https://github.com/mybatis/mybatis-3) ⭐ 20,377 | 🐛 200 | 🌐 Java | 📅 2026-02-07 - Couples objects with stored procedures or SQL statements.
* [MyBatis-Plus](https://github.com/baomidou/mybatis-plus) ⭐ 17,295 | 🐛 104 | 🌐 Java | 📅 2026-02-07 - A powerful enhanced toolkit of MyBatis for simplifying development.
* [ObjectiveSql](https://github.com/braisdom/ObjectiveSql) ⭐ 1,260 | 🐛 18 | 🌐 Java | 📅 2024-05-06 - ActiveRecord ORM for rapid development and convention over configuration.
* [Doma](https://github.com/domaframework/doma) ⭐ 493 | 🐛 3 | 🌐 Java | 📅 2026-02-08 - Database access framework that verifies and generates source code at compile time using annotation processing as well as native SQL templates called two-way SQL.
* [SimpleFlatMapper](https://github.com/arnaudroger/SimpleFlatMapper) ⭐ 455 | 🐛 158 | 🌐 Java | 📅 2025-09-21 - Simple database and CSV mapper.
* [Permazen](https://github.com/permazen/permazen) ⭐ 423 | 🐛 9 | 🌐 HTML | 📅 2025-10-04 - Language-natural persistence layer.
* [Apache Cayenne](https://cayenne.apache.org) - Provides a clean, static API for data access. Also includes a GUI Modeler for working with database mappings, and DB reverse engineering and generation.
* [Ebean](https://ebean.io) - Provides simple and fast data access.
* [EclipseLink](https://www.eclipse.org/eclipselink/) - Supports a number of persistence standards: JPA, JAXB, JCA and SDO.
* [Hibernate](http://hibernate.org/orm/) - Robust and widely used, with an active community. (LGPL-2.1-only)

### PaaS

*Java platform as a service.*

* [AWS Elastic Beanstalk ![c]](https://aws.amazon.com/elasticbeanstalk/) - AWS-based, with support for Tomcat and Jetty.
* [AWS Lambda ![c]](https://aws.amazon.com/lambda/) - Serverless computation.
* [Google Cloud ![c]](https://cloud.google.com) - Google's cloud infrastructure.
* [Heroku ![c]](https://www.heroku.com) - Abstract computing environments.
* [Microsoft Azure ![c]](https://azure.microsoft.com/en-us/) - Microsoft's cloud infrastructure.
* [OpenShift ![c]](https://www.openshift.com) - Provides additionally an on-premise solution.

### Pathfinding

*Algorithms and libraries for finding routes in graphs and spatial environments.*

* [Pathetic](https://github.com/bsommerfeld/pathetic) ⭐ 241 | 🐛 0 | 🌐 Java | 📅 2026-02-02 - A highly configurable 3D A\* pathfinding library that uses specific optimizations for high performance.

### PDF

*Tools to help with PDF files.*

* [OpenPDF](https://github.com/LibrePDF/OpenPDF) ⭐ 4,174 | 🐛 162 | 🌐 Java | 📅 2025-10-27 - Open-source iText fork. (LGPL-3.0-only & MPL-2.0)
* [flyingsaucer](https://github.com/flyingsaucerproject/flyingsaucer) ⭐ 2,195 | 🐛 40 | 🌐 Java | 📅 2026-02-06 - XML/XHTML and CSS 2.1 renderer. (LGPL-2.1-or-later)
* [Tabula](https://github.com/tabulapdf/tabula-java) ⭐ 2,003 | 🐛 194 | 🌐 Java | 📅 2025-03-19 - Extracts tables from PDF files.
* [DynamicReports](https://github.com/dynamicreports/dynamicreports) ⭐ 241 | 🐛 39 | 🌐 Java | 📅 2026-01-29 - Simplifies JasperReports. (LGPL-3.0-only)
* [Open HTML to PDF](https://github.com/openhtmltopdf/openhtmltopdf) ⭐ 228 | 🐛 58 | 🌐 Java | 📅 2026-01-21 - Properly supports modern PDF standards based on flyingsaucer and Apache PDFBox.
* [Apache FOP](https://xmlgraphics.apache.org/fop/) - Creates PDFs from XSL-FO.
* [Apache PDFBox](https://pdfbox.apache.org) - Toolbox for creating and manipulating PDFs.
* [Dynamic Jasper](https://intive-fdv.github.io/DynamicJasper/) - Abstraction layer to JasperReports. (LGPL-3.0-only)
* [Eclipse BIRT](https://www.eclipse.org/birt) - Report engine for creating PDF and other formats (DOCX, XLSX, HTML, etc) using Eclipse-based visual editor.
* [iText ![c]](https://itextpdf.com/en) - Creates PDF files programmatically.
* [JasperReports](https://community.jaspersoft.com/project/jasperreports-library) - Complex reporting engine. (LGPL-3.0-only)

### Performance analysis

*Tools for performance analysis, profiling and benchmarking.*

* [JITWatch](https://github.com/AdoptOpenJDK/jitwatch) ⭐ 3,270 | 🐛 17 | 🌐 Java | 📅 2025-12-28 - Analyze the JIT compiler optimisations made by the HotSpot JVM.
* [honest-profiler](https://github.com/jvm-profiling-tools/honest-profiler) ⭐ 1,254 | 🐛 64 | 🌐 Java | 📅 2023-12-05 - Low-overhead, bias-free sampling profiler.
* [jHiccup](https://github.com/giltene/jHiccup) ⭐ 697 | 🐛 15 | 🌐 Java | 📅 2026-02-05 - Logs and records platform JVM stalls.
* [LatencyUtils](https://github.com/LatencyUtils/LatencyUtils) ⭐ 466 | 🐛 5 | 🌐 Java | 📅 2024-05-05 - Utilities for latency measurement and reporting.
* [fastThread ![c]](https://fastthread.io) - Analyze and visualize thread dumps with a free cloud-based upload interface.
* [GCeasy ![c]](https://gceasy.io) - Tool to analyze and visualize GC logs. It provides a free cloud-based upload interface.
* [JMH](http://openjdk.java.net/projects/code-tools/jmh/) - Harness for building, running, and analysing nano/micro/milli/macro benchmarks written in Java and other languages targeting the JVM. (GPL-2.0 only WITH Classpath-exception-2.0)

### Platform

*Frameworks that are suites of multiple libraries encompassing several categories.*

#### Apache Commons

* [BCEL](http://commons.apache.org/proper/commons-bcel/) - Byte Code Engineering Library - analyze, create, and manipulate Java class files.
* [BeanUtils](http://commons.apache.org/proper/commons-beanutils/) - Easy-to-use wrappers around the Java reflection and introspection APIs.
* [BeanUtils2](http://commons.apache.org/sandbox/commons-beanutils2/) - Redesign of Commons BeanUtils.
* [BSF](http://commons.apache.org/proper/commons-bsf/) - Bean Scripting Framework - interface to scripting languages, including JSR-223.
* [Chain](http://commons.apache.org/proper/commons-chain/) - Chain of Responsibility pattern implementation.
* [ClassScan](http://commons.apache.org/sandbox/commons-classscan/) - Find Class interfaces, methods, fields, and annotations without loading.
* [CLI](http://commons.apache.org/proper/commons-cli/) - Command-line arguments parser.
* [CLI2](http://commons.apache.org/sandbox/commons-cli2/) - Redesign of Commons CLI.
* [Codec](http://commons.apache.org/proper/commons-codec/) - General encoding/decoding algorithms, e.g. phonetic, base64 or URL.
* [Collections](http://commons.apache.org/proper/commons-collections/) - Extends or augments the Java Collections Framework.
* [Compress](http://commons.apache.org/proper/commons-compress/) - Defines an API for working with tar, zip and bzip2 files.
* [Configuration](http://commons.apache.org/proper/commons-configuration/) - Reading of configuration/preferences files in various formats.
* [Convert](http://commons.apache.org/sandbox/commons-convert/) - Commons-Convert aims to provide a single library dedicated to the task of converting an object of one type to another.
* [CSV](http://commons.apache.org/proper/commons-csv/) - Component for reading and writing comma separated value files.
* [Daemon](http://commons.apache.org/proper/commons-daemon/) - Alternative invocation mechanism for unix-daemon-like java code.
* [DBCP](http://commons.apache.org/proper/commons-dbcp/) - Database connection pooling services.
* [DbUtils](http://commons.apache.org/proper/commons-dbutils/) - JDBC helper library.
* [Digester](http://commons.apache.org/proper/commons-digester/) - XML-to-Java-object mapping utility.
* [Email](http://commons.apache.org/proper/commons-email/) - Library for sending e-mail from Java.
* [Exec](http://commons.apache.org/proper/commons-exec/) - API for dealing with external process execution and environment management in Java.
* [FileUpload](http://commons.apache.org/proper/commons-fileupload/) - File upload capability for your servlets and web applications.
* [Finder](http://commons.apache.org/sandbox/commons-finder/) - Java library inspired by the UNIX find command.
* [Flatfile](http://commons.apache.org/sandbox/commons-flatfile/) - Java library for working with flat data structures.
* [Functor](http://commons.apache.org/proper/commons-functor/) - Function that can be manipulated as an object, or an object representing a single, generic function.
* [Graph](http://commons.apache.org/sandbox/commons-graph/) - General purpose graph APIs and algorithms.
* [I18n](http://commons.apache.org/sandbox/commons-i18n/) - Adds the feature of localized message bundles that consist of one or many localized texts that belong together.
* [Id](http://commons.apache.org/sandbox/commons-id/) - Id is a component used to generate identifiers.
* [Imaging](http://commons.apache.org/proper/commons-imaging/) - Image library.
* [IO](http://commons.apache.org/proper/commons-io/) - Collection of I/O utilities.
* [Javaflow](http://commons.apache.org/sandbox/commons-javaflow/) - Continuation implementation to capture the state of the application.
* [JCI](http://commons.apache.org/proper/commons-jci/) - Java Compiler Interface.
* [JCS](http://commons.apache.org/proper/commons-jcs/) - Java Caching System.
* [Jelly](http://commons.apache.org/proper/commons-jelly/) - XML based scripting and processing engine.
* [Jexl](http://commons.apache.org/proper/commons-jexl/) - Expression language which extends the Expression Language of the JSTL.
* [JNet](http://commons.apache.org/sandbox/commons-jnet/) - JNet allows to use dynamically register url stream handlers through the java.net API.
* [JXPath](http://commons.apache.org/proper/commons-jxpath/) - Utilities for manipulating Java Beans using the XPath syntax.
* [Lang](http://commons.apache.org/proper/commons-lang/) - Provides extra functionality for classes in java.lang.
* [Logging](https://commons.apache.org/proper/commons-logging/) - Wrapper around a variety of logging API implementations.
* [Math](http://commons.apache.org/proper/commons-math/) - Lightweight, self-contained mathematics and statistics components.
* [Monitoring](http://commons.apache.org/sandbox/commons-monitoring/) - Monitoring aims to provide a simple but extensible monitoring solution for Java applications.
* [Nabla](http://commons.apache.org/sandbox/commons-nabla/) - Nabla provides automatic differentiation classes that can generate derivative of any function implemented in the Java language.
* [Net](http://commons.apache.org/proper/commons-net/) - Collection of network utilities and protocol implementations.
* [OGNL](http://commons.apache.org/proper/commons-ognl/) - Object-graph navigation language.
* [OpenPGP](http://commons.apache.org/sandbox/commons-openpgp/) - Interface to signing and verifying data using OpenPGP.
* [Performance](http://commons.apache.org/sandbox/commons-performance/) - Small framework for microbenchmark clients, with implementations for Commons DBCP and Pool.
* [Pipeline](http://commons.apache.org/sandbox/commons-pipeline/) - Provides a set of pipeline utilities designed around work queues that run in parallel to sequentially process data objects.
* [Pool](http://commons.apache.org/proper/commons-pool/) - Generic object pooling component.
* [Proxy](http://commons.apache.org/proper/commons-proxy/) - Library for creating dynamic proxies.
* [RDF](https://commons.apache.org/proper/commons-rdf/) - Common implementation of RDF 1.1 that could be implemented by systems on the JVM.
* [RNG](https://commons.apache.org/proper/commons-rng/) - Commons Rng provides implementations of pseudo-random numbers generators.
* [SCXML](http://commons.apache.org/proper/commons-scxml/) - Implementation of the State Chart XML specification aimed at creating and maintaining a Java SCXML engine.
* [Validator](http://commons.apache.org/proper/commons-validator/) - Framework to define validators and validation rules in an xml file.
* [VFS](http://commons.apache.org/proper/commons-vfs/) - Virtual File System component for treating files, FTP, SMB, ZIP and such like as a single logical file system.
* [Weaver](http://commons.apache.org/proper/commons-weaver/) - Provides an easy way to enhance (weave) compiled bytecode.

#### Other

* [Light-4J](https://github.com/networknt/light-4j/) ⭐ 3,681 | 🐛 26 | 🌐 Java | 📅 2026-02-08 - Fast, lightweight and productive microservices framework with built-in [security](https://github.com/networknt/light-oauth2/) ⚠️ Archived.
* [Orienteer](https://github.com/OrienteerBAP/Orienteer/) ⭐ 258 | 🐛 171 | 🌐 Java | 📅 2024-02-08 - Open-source business application platform for rapid configuration/development of CRM, ERP, LMS and other applications.
* [CUBA Platform](https://www.cuba-platform.com/) - High-level framework for developing enterprise applications with a rich web interface, based on Spring, EclipseLink and Vaadin.
* [Spring](https://spring.io/projects/) - Provides many packages for dependency injection, aspect-oriented programming, security, etc.

### Processes

*Libraries that help the management of operating system processes.*

* [zt-exec](https://github.com/zeroturnaround/zt-exec) ⭐ 911 | 🐛 11 | 🌐 Java | 📅 2025-07-12 - Provides a unified API to Apache Commons Exec and ProcessBuilder.
* [zt-process-killer](https://github.com/zeroturnaround/zt-process-killer) ⭐ 136 | 🐛 9 | 🌐 Java | 📅 2023-12-05 - Stops processes started from Java or the system processes via PID.
* [ch.vorburger.exec](https://github.com/vorburger/ch.vorburger.exec) ⭐ 38 | 🐛 15 | 🌐 Java | 📅 2026-02-05 - Convenient API around Apache Commons Exec.

### Reactive libraries

*Libraries for developing reactive applications.*

* [RxJava](https://github.com/ReactiveX/RxJava) ⭐ 48,523 | 🐛 20 | 🌐 Java | 📅 2026-02-06 - Allows for composing asynchronous and event-based programs using observable sequences.
* [Reactive Streams](https://github.com/reactive-streams/reactive-streams-jvm) ⭐ 4,864 | 🐛 34 | 🌐 Java | 📅 2024-03-13 - Provides a standard for asynchronous stream processing with non-blocking backpressure.
* [Reactor](https://github.com/reactor/reactor) ⭐ 3,687 | 🐛 9 | 📅 2026-01-26 - A framework for building non-blocking applications on the JVM, providing support for reactive programming.
* [Akka](https://akka.io) - Toolkit and runtime for building concurrent, distributed, fault-tolerant and event-driven applications.
* [vert.x](https://vertx.io) - Polyglot event-driven application framework.

### REST Frameworks

*Frameworks specifically for creating RESTful services.*

* [openapi-generator](https://github.com/OpenAPITools/openapi-generator) ⭐ 25,765 | 🐛 5,575 | 🌐 Java | 📅 2026-02-07 - Allows generation of API client libraries, SDKs, server stubs, documentation and configuration automatically given an OpenAPI Spec.
* [Dropwizard](https://github.com/dropwizard/dropwizard) ⭐ 8,592 | 🐛 33 | 🌐 Java | 📅 2026-02-06 - Opinionated framework for setting up modern web applications with Jetty, Jackson, Jersey and Metrics.
* [springdoc-openapi](https://github.com/springdoc/springdoc-openapi) ⭐ 3,665 | 🐛 23 | 🌐 Java | 📅 2026-01-24 - Automates the generation of API documentation using Spring Boot projects.
* [rest.li](https://github.com/linkedin/rest.li) ⭐ 2,533 | 🐛 109 | 🌐 Java | 📅 2026-02-04 - Framework for building robust, scalable RESTful architectures using typesafe bindings and asynchronous, non-blocking IO with an end-to-end developer workflow that promotes clean practices, uniform interface design and consistent data modeling.
* [RestExpress](https://github.com/RestExpress/RestExpress) ⭐ 940 | 🐛 28 | 🌐 Java | 📅 2026-01-20 - Thin wrapper on the JBoss Netty HTTP stack that provides scaling and performance.
* [Microserver](https://github.com/aol/micro-server) ⭐ 936 | 🐛 48 | 🌐 Java | 📅 2023-03-21 - Convenient, extensible microservices plugin system for Spring & Spring Boot. With more than 30 plugins and growing, it supports both micro-monolith and pure microservices styles.
* [Restlet Framework](https://github.com/restlet/restlet-framework-java) ⭐ 661 | 🐛 554 | 🌐 Java | 📅 2026-01-23 - Pioneering framework with powerful routing and filtering capabilities, and a unified client and server API.
* [Elide](https://elide.io) - Opinionated framework for JSON- or GraphQL-APIs based on a JPA data model.
* [Jersey](https://jersey.github.io) - JAX-RS reference implementation.
* [Rapidoid](https://www.rapidoid.org) - Simple, secure and extremely fast framework consisting of an embedded HTTP server, GUI components and dependency injection.
* [RESTEasy](https://resteasy.github.io) - Fully certified and portable implementation of the JAX-RS specification.
* [Spark](http://sparkjava.com) - Sinatra inspired framework.
* [Crnk](http://www.crnk.io) - Implementation of the JSON API specification to build resource-oriented REST endpoints with sorting, filtering, paging, linking, object graphs, type-safety, bulk updates, integrations and more.
* [Swagger](https://swagger.io) - Standard, language-agnostic interface to REST APIs.

### Science

*Libraries for scientific computing, analysis and visualization.*

* [Tablesaw](https://github.com/jtablesaw/tablesaw) ⭐ 3,730 | 🐛 141 | 🌐 Java | 📅 2025-07-12 - Includes a data-frame, an embedded column store, and hundreds of methods to transform, summarize, or filter data.
* [JGraphT](https://github.com/jgrapht/jgrapht) ⭐ 2,757 | 🐛 156 | 🌐 Java | 📅 2026-01-27 - Graph library that provides mathematical graph-theory objects and algorithms.
* [XChart](https://github.com/knowm/XChart) ⭐ 1,575 | 🐛 157 | 🌐 Java | 📅 2025-10-27 - Light-weight library for plotting data. Many customizable chart types are available.
* [JGraphX](https://github.com/jgraph/jgraphx) ⚠️ Archived - Library for visualizing (mainly Swing) and interacting with node-edge graphs.
* [Chart-FX](https://github.com/GSI-CS-CO/chart-fx) ⭐ 584 | 🐛 27 | 🌐 Java | 📅 2025-12-10 - Scientific charting library with focus on performance optimised real-time data visualisation at 25 Hz update rates for large data sets.
* [Morpheus](https://github.com/zavtech/morpheus-core) ⭐ 244 | 🐛 40 | 🌐 Java | 📅 2023-12-06 - Provides a versatile two-dimensional memory efficient tabular data structure called a DataFrame to enable efficient in-memory analytics for scientific computing on the JVM.
* [LogicNG](https://github.com/logic-ng/LogicNG) ⭐ 151 | 🐛 1 | 🌐 Java | 📅 2026-01-26 - Library for creating, manipulating and solving Boolean and Pseudo-Boolean formulas.
* [Erdos](https://github.com/Erdos-Graph-Framework/Erdos) ⭐ 127 | 🐛 2 | 🌐 Java | 📅 2023-08-27 - Modular, light and easy graph framework for theoretic algorithms.
* [Orson-Charts](https://github.com/jfree/orson-charts) ⭐ 120 | 🐛 6 | 🌐 Java | 📅 2025-06-12 - Generates a wide variety of 3D charts that can be displayed with Swing and JavaFX or exported to PDF, SVG, PNG and JPEG. (GPL-3.0-only)
* [Mines Java Toolkit](https://github.com/MinesJTK/jtk) ⭐ 82 | 🐛 5 | 🌐 Java | 📅 2021-03-25 - Library for geophysical scientific computation, visualization and digital signal analysis.
* [jSciPy](https://github.com/hissain/jscipy) ⭐ 17 | 🐛 0 | 🌐 Java | 📅 2026-02-03 - jSciPy is a Java library designed for scientific computing, offering functionalities inspired by popular scientific computing libraries. It currently provides modules for signal processing, including Butterworth filters, peak finding algorithms, and an RK4 solver for ordinary differential equations.
* [BioJava](https://biojava.org/) - Facilitates processing biological data by providing algorithms, file format parsers, sequencing and 3D visualization commonly used in bioinformatics.
* [DataMelt](https://datamelt.org/) - Environment for scientific computation, data analysis and data visualization. (GPL-3.0-or-later)
* [GraphStream](http://graphstream-project.org) - Library for modeling and analyzing dynamic graphs.
* [JFreeChart](http://www.jfree.org/jfreechart/) - 2D chart library for Swing, JavaFX and server-side applications. (LGPL-2.1-only)
* [Orekit](https://www.orekit.org/) - A low level space flight dynamics library providing basic elements (orbits, dates, attitude, frames...) and various algorithms (conversions, propagations, pointing...) to handle them.

### Search

*Engines that index documents for search and analysis.*

* [Apache Lucene](https://lucene.apache.org) - High-performance, full-featured, cross-platform, text search engine library.
* [Apache Solr](https://lucene.apache.org/solr/) - Enterprise search engine optimized for high-volume traffic.
* [Elasticsearch](https://www.elastic.co) - Distributed, multitenant-capable, full-text search engine with a RESTful web interface and schema-free JSON documents.
* [Indexer4j](https://github.com/haeungun/indexer4j) ⭐ 56 | 🐛 1 | 🌐 Java | 📅 2019-01-27 - Simple and light full text indexing and searching library.

### Security

*Libraries that handle security, authentication, authorization or session management.*

* [Tink](https://github.com/google/tink) ⚠️ Archived - Provides a simple and misuse-proof API for common cryptographic tasks.
* [jjwt](https://github.com/jwtk/jjwt) ⭐ 11,014 | 🐛 48 | 🌐 Java | 📅 2025-10-17 - JSON web token for Java and Android.
* [Keywhiz](https://github.com/square/keywhiz) ⚠️ Archived - System for distributing and managing secrets.
* [pac4j](https://github.com/pac4j/pac4j) ⭐ 2,512 | 🐛 12 | 🌐 Java | 📅 2026-02-06 - Security engine.
* [Themis](https://github.com/cossacklabs/themis) ⭐ 1,950 | 🐛 31 | 🌐 C | 📅 2026-01-09 - Multi-platform high-level cryptographic library provides easy-to-use encryption for protecting sensitive data: secure messaging with forward secrecy, secure data storage (AES256GCM); suits for building end-to-end encrypted applications.
* [OpenAM](https://github.com/OpenIdentityPlatform/OpenAM) ⭐ 865 | 🐛 2 | 🌐 Java | 📅 2026-02-04 - Access management solution that includes authentication, SSO, authorization, federation, entitlements and web services security.
* [Ayza](https://github.com/Hakky54/ayza) ⭐ 570 | 🐛 0 | 🌐 Java | 📅 2026-02-02 - High-level SSL configuration builder for configuring HTTP clients and servers with SSL/TLS.
* [Password4j](https://github.com/Password4j/password4j) ⭐ 406 | 🐛 9 | 🌐 Java | 📅 2025-09-06 - User-friendly cryptographic library that supports Argon2, Bcrypt, Scrypt, PBKDF2 and various other cryptographic hash functions.
* [Nbvcxz](https://github.com/GoSimpleLLC/nbvcxz) ⭐ 308 | 🐛 17 | 🌐 Java | 📅 2025-09-05 - Advanced password strength estimation.
* [OTP-Java](https://github.com/BastiaanJansen/OTP-Java) ⭐ 230 | 🐛 6 | 🌐 Java | 📅 2024-12-23 - One-time password generator library according to RFC 4226 (HOTP) and RFC 6238 (TOTP).
* [Hdiv](https://github.com/hdiv/hdiv) ⭐ 219 | 🐛 72 | 🌐 Java | 📅 2024-12-06 - Runtime application that repels application security risks included in the OWASP Top 10, including SQL injection, cross-site scripting, cross-site request forgery, data tampering, and brute force attacks.
* [Kalium](https://github.com/abstractj/kalium) ⚠️ Archived - Binding for the Networking and Cryptography (NaCl) library.
* [Jwks RSA](https://github.com/auth0/jwks-rsa-java) ⭐ 204 | 🐛 17 | 🌐 Java | 📅 2025-12-09 - JSON Web Key Set parser.
* [SecurityBuilder](https://github.com/tersesystems/securitybuilder) ⭐ 47 | 🐛 0 | 🌐 Java | 📅 2021-06-26 - Fluent Builder API for JCA and JSSE classes and especially X.509 certificates.
* [DependencyCheck](https://github.com/jeremylong/DependencyCheck) ⚠️ Archived - Detects publicly disclosed vulnerabilities contained within a project's dependencies.
* [jwt-java](https://github.com/BastiaanJansen/jwt-java) ⭐ 14 | 🐛 2 | 🌐 Java | 📅 2025-07-17 - Easily create and parse JSON Web Tokens and create customized JWT validators using a fluent API.
* [Apache Shiro](https://shiro.apache.org) - Performs authentication, authorization, cryptography and session management.
* [Bouncy Castle](https://www.bouncycastle.org/java.html) - All-purpose cryptographic library and JCA provider offering a wide range of functions, from basic helpers to PGP/SMIME operations.
* [Cryptomator](https://cryptomator.org) - Multiplatform, transparent, client-side encryption of files in the cloud. (GPL-3.0-only)
* [Keycloak](https://www.keycloak.org) - Integrated SSO and IDM for browser apps and RESTful web services.
* [OACC](http://oaccframework.org) - Provides permission-based authorization services.
* [Passay](http://www.passay.org/) - Enforce password policy by validating candidate passwords against a configurable rule set.
* [Topaz](https://www.topaz.sh) - Fine-grained authorization for applications with support for RBAC, ABAC, and ReBAC.

### Serialization

*Libraries that handle serialization with high efficiency.*

* [FlatBuffers](https://github.com/google/flatbuffers) ⭐ 25,529 | 🐛 143 | 🌐 C++ | 📅 2026-02-07 - Memory-efficient serialization library that can access serialized data without unpacking and parsing it.
* [Kryo](https://github.com/EsotericSoftware/kryo) ⭐ 6,485 | 🐛 35 | 🌐 HTML | 📅 2026-02-02 - Fast and efficient object graph serialization framework.
* [Fury](https://github.com/alipay/fury) ⭐ 4,206 | 🐛 160 | 🌐 Java | 📅 2026-02-08 - Blazing fast object graph serialization framework powered by JIT and zero-copy.
* [FST](https://github.com/RuedigerMoeller/fast-serialization) ⭐ 1,594 | 🐛 126 | 🌐 Java | 📅 2023-06-30 - JDK-compatible, high-performance object graph serialization.
* [MessagePack](https://github.com/msgpack/msgpack-java) ⭐ 1,466 | 🐛 73 | 🌐 Java | 📅 2026-01-05 - Efficient binary serialization format.
* [PHP Serializer](https://github.com/marcospassos/java-php-serializer) ⭐ 19 | 🐛 0 | 🌐 Java | 📅 2018-02-28 - Serializing objects in the PHP serialization format.

### Server

*Servers specifically used to deploy applications.*

* [Apache Tomcat](https://tomcat.apache.org) - Robust, all-round server for Servlet and JSP.
* [Apache TomEE](https://tomee.apache.org) - Tomcat plus Java EE.
* [Jetty](https://www.eclipse.org/jetty/) - Provides a Web server and javax.servlet container, plus support for HTTP/2, WebSocket, OSGi, JMX, JNDI, JAAS and many other integrations.
* [nanohttpd](https://github.com/NanoHttpd/nanohttpd) ⭐ 7,205 | 🐛 201 | 🌐 Java | 📅 2023-07-25 - Tiny, easily embeddable HTTP server.
* [WildFly](https://www.wildfly.org) - Formerly known as JBoss and developed by Red Hat with extensive Java EE support. (LGPL-2.1-only)

### Template Engine

*Tools that substitute expressions in a template.*

* [jte](https://github.com/casid/jte) ⭐ 1,071 | 🐛 53 | 🌐 Java | 📅 2026-02-04 - Compiles to classes, and uses an easy syntax, several features to make development easier and provides fast execution and a small footprint.
* [StringTemplate](https://github.com/antlr/stringtemplate4) ⭐ 1,024 | 🐛 48 | 🌐 Java | 📅 2025-05-14 - Template engine for generating source code, web pages, emails, or any other formatted text output.
* [Rocker](https://github.com/fizzed/rocker) ⭐ 781 | 🐛 48 | 🌐 Java | 📅 2026-01-21 - Optimized, memory efficient and speedy template engine producing statically typed, plain objects.
* [Jade4J](https://github.com/neuland/jade4j) ⭐ 706 | 🐛 9 | 🌐 Java | 📅 2022-05-20 - Implementation of Pug (formerly known as Jade).
* [jstachio](https://github.com/jstachio/jstachio) ⭐ 321 | 🐛 38 | 🌐 Java | 📅 2025-04-15 - Typesafe Mustache templating engine.
* [Jtwig](https://github.com/jtwig/jtwig) ⭐ 300 | 🐛 39 | 📅 2018-04-14 - Modular, configurable and fully tested template engine.
* [Jamal](https://github.com/verhas/jamal) ⭐ 65 | 🐛 0 | 🌐 Java | 📅 2025-04-22 - Extendable template engine embedded into Maven/JavaDoc, supporting multiple extensions (Groovy, Ruby, JavaScript, JShell, PlantUml) with support for snippet handling.
* [Freemarker](https://freemarker.apache.org) - Library to generate text output (HTML web pages, e-mails, configuration files, source code, etc.) based on templates and changing data.
* [Handlebars.java](https://jknack.github.io/handlebars.java/) - Logicless and semantic Mustache templates.
* [Pebble](https://pebbletemplates.io) - Inspired by Twig and separates itself with its inheritance feature and its easy-to-read syntax. It ships with built-in autoescaping for security and it includes integrated support for internationalization.
* [Thymeleaf](https://www.thymeleaf.org) - Aims to be a substitute for JSP and works for XML files.

### Testing

*Tools that test from model to the view.*

#### Asynchronous

*Tools that simplify testing asynchronous services.*

* [Karate](https://github.com/intuit/karate) ⭐ 8,779 | 🐛 68 | 🌐 Java | 📅 2026-02-05 - DSL that combines API test-automation, mocks and performance-testing making testing REST/HTTP services easy.
* [REST Assured](https://github.com/rest-assured/rest-assured) ⭐ 7,109 | 🐛 584 | 🌐 Java | 📅 2026-02-04 - DSL for easy testing of REST/HTTP services.
* [Awaitility](https://github.com/awaitility/awaitility) ⭐ 3,988 | 🐛 85 | 🌐 Java | 📅 2025-02-26 - DSL for synchronizing asynchronous operations.
* [ConcurrentUnit](https://github.com/jhalterman/concurrentunit) ⭐ 425 | 🐛 13 | 🌐 Java | 📅 2024-04-05 - Toolkit for testing multi-threaded and asynchronous applications.
* [WebTau](https://github.com/testingisdocumenting/webtau) ⭐ 380 | 🐛 5 | 🌐 Java | 📅 2026-02-03 - Test across REST-API, Graph QL, Browser, Database, CLI and Business Logic with consistent set of matchers and concepts.
* [Hoverfly Java](https://github.com/SpectoLabs/hoverfly-java) ⭐ 173 | 🐛 15 | 🌐 Java | 📅 2025-12-20 - Native bindings for Hoverfly, a proxy which allows you to simulate HTTP services.
* [GreenMail](https://greenmail-mail-test.github.io/greenmail/) - In-memory email server for integration testing. Supports SMTP, POP3 and IMAP including SSL. (GPL-2.0-only)

#### BDD

*Testing for the software development process that emerged from TDD and was heavily influenced by DDD and OOAD.*

* [Cucumber](https://github.com/cucumber/cucumber-jvm) ⭐ 2,789 | 🐛 61 | 🌐 Java | 📅 2026-02-05 - Provides a way to describe features in a plain language which customers can understand.
* [Serenity BDD](https://github.com/serenity-bdd/serenity-core) ⭐ 748 | 🐛 435 | 🌐 HTML | 📅 2026-02-03 - Automated Acceptance testing and reporting library that works with Cucumber, JBehave and JUnit to make it easier to write high quality executable specifications.
* [Lamdba Behave](https://github.com/RichardWarburton/lambda-behave) ⭐ 252 | 🐛 41 | 🌐 Java | 📅 2022-02-22 - Aims to provide a fluent API to write tests in long and descriptive sentences that read like plain English.
* [Cukes-REST](https://github.com/ctco/cukes) ⭐ 111 | 🐛 46 | 🌐 Java | 📅 2025-06-02 - Collection of Gherkin steps for REST-service testing using Cucumber.
* [J8Spec](https://github.com/j8spec/j8spec) ⭐ 48 | 🐛 1 | 🌐 Java | 📅 2022-02-25 - Follows a Jasmine-like syntax.
* [JBehave](https://jbehave.org) - Extensively configurable framework that describes stories.
* [JGiven](http://jgiven.org) - Provides a fluent API which allows for simpler composition.

#### Fixtures

*Everything related to the creation and handling of random data.*

* [Java Faker](https://github.com/DiUS/java-faker) ⭐ 4,928 | 🐛 226 | 🌐 Java | 📅 2024-06-12 - Port of Ruby's fake data generator.
* [Datafaker](https://github.com/datafaker-net/datafaker) ⭐ 1,734 | 🐛 9 | 🌐 Java | 📅 2026-02-05 - Modern fake data generator forked from Java Faker.
* [Instancio](https://github.com/instancio/instancio) ⭐ 1,104 | 🐛 7 | 🌐 Java | 📅 2026-02-07 - Automates data setup in unit tests by generating fully-populated, reproducible objects. Includes JUnit 5 extension.
* [jFairy](https://github.com/Devskiller/jfairy) ⭐ 746 | 🐛 32 | 🌐 Java | 📅 2024-03-18 - Fake data generator.
* [Mockneat](https://github.com/nomemory/mockneat) ⭐ 537 | 🐛 8 | 🌐 Java | 📅 2023-03-27 - Another fake data generator.
* [Fixture Factory](https://github.com/six2six/fixture-factory) ⭐ 446 | 🐛 34 | 🌐 Java | 📅 2023-04-14 - Generates fake objects from a template.
* [JMock](https://github.com/xcancloud/JMock) ⭐ 422 | 🐛 0 | 🌐 Java | 📅 2025-10-25 - JMock is a high-performance data generation and simulation component library implemented in Java.
* [AutoParams](https://github.com/AutoParams/AutoParams) ⭐ 367 | 🐛 24 | 🌐 Java | 📅 2026-01-28 - Supports generating test data or combining scenarios for parameterized tests.
* [Randomized Testing](https://github.com/randomizedtesting/randomizedtesting) ⭐ 180 | 🐛 22 | 🌐 Java | 📅 2026-01-27 - JUnit test runner and plugins for running JUnit tests with pseudo-randomness.
* [Beanmother](https://github.com/keepcosmos/beanmother) ⭐ 121 | 🐛 12 | 🌐 Java | 📅 2022-12-14 - Sets up beans from YAML fixtures.

#### Frameworks

*Provide environments to run tests for a specific use case.*

* [selenium](https://github.com/SeleniumHQ/selenium) ⭐ 33,986 | 🐛 214 | 🌐 Java | 📅 2026-02-08 - Browser automation framework and ecosystem.
* [Pact JVM](https://github.com/DiUS/pact-jvm) ⭐ 1,124 | 🐛 380 | 🌐 Kotlin | 📅 2026-02-05 - Consumer-driven contract testing.
* [weld-testing](https://github.com/weld/weld-testing) ⭐ 113 | 🐛 8 | 🌐 Java | 📅 2026-02-02 - Set of test framework extensions (JUnit 4, JUnit 5, Spock) to enhance the testing of CDI components via Weld. Supports Weld 5.
* [cdi-test](https://github.com/guhilling/cdi-test) ⭐ 27 | 🐛 10 | 🌐 Java | 📅 2026-02-01 - JUnit extension for easy and efficient testing of CDI components.
* [Apache JMeter](http://jmeter.apache.org) - Functional testing and performance measurements.
* [JMeter DSL.java](https://abstracta.github.io/jmeter-java-dsl/) - Load tests with JMeter as simple as a JUnit test.
* [Arquillian](http://arquillian.org) - Integration and functional testing platform for Java EE containers.
* [BitDive ![c]](https://bitdive.io) - Zero-code integration testing platform that generates tests from runtime application behavior.
* [Citrus](https://citrusframework.org) - Integration testing framework that focuses on both client- and server-side messaging.
* [Gatling](https://gatling.io) - Load testing tool designed for ease of use, maintainability and high performance.
* [JUnit](https://junit.org/junit5/) - Common testing framework.
* [jqwik](https://jqwik.net) - Engine for property-based testing built on JUnit 5.
* [PIT](http://pitest.org) - Fast mutation-testing framework for evaluating fault-detection abilities of existing JUnit or TestNG test suites.

#### Matchers

*Libraries that provide custom matchers.*

* [JsonUnit](https://github.com/lukas-krecan/JsonUnit) ⭐ 980 | 🐛 18 | 🌐 Java | 📅 2026-02-06 - Library that simplifies JSON comparison in tests.
* [XMLUnit](https://github.com/xmlunit/xmlunit) ⭐ 312 | 🐛 11 | 🌐 Java | 📅 2026-01-27 - Simplifies testing for XML output.
* [AssertJ](https://joel-costigliola.github.io/assertj/) - Fluent assertions that improve readability.
* [Hamcrest](http://hamcrest.org/JavaHamcrest/) - Matchers that can be combined to create flexible expressions of intent.
* [JSONAssert](http://jsonassert.skyscreamer.org) - Simplifies testing JSON strings.
* [Truth](https://truth.dev) - Google's fluent assertion and proposition framework.

#### Miscellaneous

*Other stuff related to testing.*

* [Testcontainers](https://github.com/testcontainers/testcontainers-java) ⭐ 8,574 | 🐛 626 | 🌐 Java | 📅 2026-02-03 - Provides throwaway instances of common databases, Selenium web browsers, or anything else that can run in a Docker container.
* [LogCaptor](https://github.com/Hakky54/log-captor) ⭐ 425 | 🐛 2 | 🌐 Java | 📅 2026-02-01 - Captures log entries for unit testing purposes.
* [junit-dataprovider](https://github.com/TNG/junit-dataprovider) ⭐ 248 | 🐛 0 | 🌐 Java | 📅 2026-02-07 - TestNG-like data provider/runner for JUnit.
* [Mutability Detector](https://github.com/MutabilityDetector/MutabilityDetector) ⭐ 242 | 🐛 23 | 🌐 Java | 📅 2025-10-11 - Reports whether instances of a given class are immutable.
* [Selfie](https://github.com/diffplug/selfie) ⭐ 88 | 🐛 50 | 🌐 Kotlin | 📅 2026-02-05 - Snapshot testing (inline and on disk).
* [raml-tester](https://github.com/nidi3/raml-tester) ⭐ 73 | 🐛 14 | 🌐 Java | 📅 2019-02-13 - Tests if a request/response matches a given RAML definition.
* [ConsoleCaptor](https://github.com/Hakky54/console-captor) ⭐ 33 | 🐛 0 | 🌐 Java | 📅 2026-02-02 - Captures console output for unit testing purposes.
* [Stebz](https://github.com/stebz/stebz) ⭐ 18 | 🐛 4 | 🌐 Java | 📅 2026-02-07 - Multi-approach framework for test steps managing.
* [log-capture](https://github.com/dm-drogeriemarkt/log-capture) ⭐ 15 | 🐛 1 | 🌐 Java | 📅 2026-01-26 - Captures log entries and provides assertions for unit and integration testing.
* [junit-pioneer](https://junit-pioneer.org/) - JUnit 5 extension pack, pushing the frontiers on Jupiter.
* [pojo-tester](https://www.pojo.pl) - Automatically performs tests on basic POJO methods. (LGPL-3.0-only)

#### Mocking

*Tools which mock collaborators to help testing single, isolated units.*

* [Mockito](https://github.com/mockito/mockito) ⭐ 15,420 | 🐛 483 | 🌐 Java | 📅 2026-02-06 - Mocking framework that lets you write tests with a clean and simple API.
* [Moco](https://github.com/dreamhead/moco) ⭐ 4,432 | 🐛 144 | 🌐 Java | 📅 2026-02-04 - Concise web services for stubs and mocks.
* [PowerMock](https://github.com/powermock/powermock) ⭐ 4,187 | 🐛 463 | 🌐 Java | 📅 2024-01-03 - Mocks static methods, constructors, final classes and methods, private methods, and removal of static initializers.
* [EasyMock](https://github.com/easymock/easymock) ⭐ 830 | 🐛 62 | 🌐 HTML | 📅 2026-02-06 - EasyMock is a Java library that provides an easy way to use Mock Objects in unit testing.
* [JMockit](http://jmockit.github.io) - Integration testing, API mocking and faking, and code coverage.
* [MockServer](https://www.mock-server.com) - Allows mocking of systems integrated with HTTPS.
* [WireMock](http://wiremock.org) - Stubs and mocks web services.

### Utility

*Libraries which provide general utility functions.*

* [Guava](https://github.com/google/guava) ⭐ 51,461 | 🐛 718 | 🌐 Java | 📅 2026-02-07 - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and more.
* [Arthas](https://github.com/alibaba/arthas) ⭐ 37,071 | 🐛 461 | 🌐 Java | 📅 2026-02-03 - Allows to troubleshoot production issues for applications without modifying code or restarting servers.
* [Gephi](https://github.com/gephi/gephi) ⭐ 6,354 | 🐛 548 | 🌐 Java | 📅 2026-02-06 - Cross-platform for visualizing and manipulating large graph networks. (GPL-3.0-only)
* [bucket4j](https://github.com/vladimir-bukhtoyarov/bucket4j) ⭐ 2,691 | 🐛 23 | 🌐 Java | 📅 2026-02-04 - Rate limiting library based on token-bucket algorithm.
* [JavaVerbalExpressions](https://github.com/VerbalExpressions/JavaVerbalExpressions) ⭐ 2,627 | 🐛 15 | 🌐 Java | 📅 2026-02-05 - Library that helps with constructing difficult regular expressions.
* [Embulk](https://github.com/embulk/embulk) ⭐ 1,782 | 🐛 161 | 🌐 Java | 📅 2025-11-24 - Bulk data loader that helps data transfer between various databases, storages, file formats, and cloud services.
* [Dex](https://github.com/PatMartin/Dex) ⭐ 1,320 | 🐛 5 | 🌐 JavaScript | 📅 2019-02-12 - Java/JavaFX tool capable of powerful ETL and data visualization.
* [minio-java](https://github.com/minio/minio-java) ⭐ 1,278 | 🐛 2 | 🌐 Java | 📅 2025-12-16 - Provides simple APIs to access any Amazon S3-compatible object storage server.
* [cactoos](https://github.com/yegor256/cactoos) ⭐ 765 | 🐛 81 | 🌐 Java | 📅 2026-02-06 - Collection of object-oriented primitives.
* [Underscore-java](https://github.com/javadev/underscore-java) ⭐ 548 | 🐛 0 | 🌐 Java | 📅 2026-02-05 - Port of Underscore.js functions.
* [Semver4j](https://github.com/semver4j/semver4j) ⭐ 108 | 🐛 1 | 🌐 Java | 📅 2026-02-07 - Lightweight library that helps you handling semantic versioning with different modes.
* [Javadoc Publisher](https://github.com/MathieuSoysal/Javadoc-publisher.yml) ⭐ 55 | 🐛 5 | 🌐 Java | 📅 2025-12-08 - Generate Javadoc from your maven/gradle project and deploy it automatically on GitHub Page.
* [dregex](https://github.com/marianobarrios/dregex) ⭐ 49 | 🐛 1 | 🌐 Java | 📅 2026-02-06 - Regular expression engine that uses deterministic finite automata. It supports some Perl-style features and yet retains linear matching time, and also offers set operations.
* [Chocotea](https://github.com/cleopatra27/chocotea) ⭐ 48 | 🐛 1 | 🌐 Java | 📅 2023-01-20 - Generates postman collection, environment and integration tests from java code.
* [fswatch](https://github.com/vorburger/ch.vorburger.fswatch) ⭐ 31 | 🐛 5 | 🌐 Java | 📅 2026-01-03 - Micro library to watch for directory file system changes, simplifying java.nio.file.WatchService.
* [JKScope](https://github.com/evpl/jkscope) ⭐ 21 | 🐛 0 | 🌐 Java | 📅 2025-01-25 - Java scope functions inspired by Kotlin.
* [CRaSH](http://www.crashub.org) - Provides a shell into a JVM that's running CRaSH. Used by Spring Boot and others. (LGPL-2.1-or-later)
* [JADE](https://jade.tilab.com) - Framework and environment for building and debugging multi-agent systems. (LGPL-2.0-only)
* [Java Diff Utils](https://java-diff-utils.github.io/java-diff-utils/) - Utilities for text or data comparison and patching.
* [JGit](https://www.eclipse.org/jgit/) - Lightweight, pure Java library implementing the Git version control system.
* [Protégé](https://protege.stanford.edu) - Provides an ontology editor and a framework to build knowledge-based systems.

### Version Managers

*Utilities that help create the development shell environment and switch between different Java versions.*

* [SDKMan](https://github.com/sdkman/sdkman-cli) ⭐ 6,655 | 🐛 189 | 🌐 Gherkin | 📅 2026-01-07 - Java Version Manager inspired by RVM and rbenv. Supports UNIX-based platforms and Windows.
* [jenv](https://github.com/jenv/jenv) ⭐ 6,532 | 🐛 77 | 🌐 Shell | 📅 2025-12-24 - Java Version Manager inspired by rbenv. Can configure globally or per project. Tested on Debian and macOS.
* [jabba](https://github.com/shyiko/jabba) ⭐ 3,367 | 🐛 150 | 🌐 Go | 📅 2024-03-14 - Java Version Manager inspired by nvm. Supports macOS, Linux and Windows.

### Web Crawling

*Libraries that analyze the content of websites.*

* [webmagic](https://github.com/code4craft/webmagic) ⭐ 11,700 | 🐛 367 | 🌐 Java | 📅 2025-12-20 - Scalable crawler with downloading, url management, content extraction and persistent.
* [Crawler4j](https://github.com/yasserg/crawler4j) ⭐ 4,627 | 🐛 187 | 🌐 Java | 📅 2021-11-04 - Simple and lightweight web crawler.
* [Apache Nutch](https://nutch.apache.org) - Highly extensible, highly scalable web crawler for production environments.
* [jsoup](https://jsoup.org) - Scrapes, parses, manipulates and cleans HTML.
* [StormCrawler](http://stormcrawler.net) - SDK for building low-latency and scalable web crawlers.

### Web Frameworks

*Frameworks that handle the communication between the layers of a web application.*

* [Blade](https://github.com/lets-blade/blade) ⭐ 5,886 | 🐛 14 | 🌐 Java | 📅 2025-12-15 - Lightweight, modular framework that aims to be elegant and simple.
* [Erupt](https://github.com/erupts/erupt) ⭐ 2,681 | 🐛 5 | 🌐 Java | 📅 2026-02-06 - Annotation-Driven Low-Code & JPA Visualization
* [Takes](https://github.com/yegor256/takes) ⭐ 869 | 🐛 106 | 🌐 Java | 📅 2026-02-07 - Opinionated web framework which is built around the concepts of True Object-Oriented Programming and immutability.
* [ActiveJ](https://activej.io) - Lightweight asynchronous framework built from the ground up for developing high-performance web applications.
* [Apache Tapestry](https://tapestry.apache.org) - Component-oriented framework for creating dynamic, robust, highly scalable web applications.
* [Apache Wicket](https://wicket.apache.org) - Component-based web application framework similar to Tapestry, with a stateful GUI.
* [Bootique](https://bootique.io) - Minimally opinionated framework for runnable apps.
* [Firefly](http://www.fireflysource.com) - Asynchronous framework for rapid development of high-performance web application.
* [Javalin](https://javalin.io/) - Microframework for web applications.
* [Jooby](http://www.jooby.org) - Scalable, fast and modular micro-framework that offers multiple programming models.
* [Ninja](http://www.ninjaframework.org) - Full-stack web framework.
* [Pippo](http://www.pippo.ro) - Small, highly modularized, Sinatra-like framework.
* [Play](https://www.playframework.com) - Built on Akka, it provides predictable and minimal resource consumption (CPU, memory, threads) for highly-scalable applications in Java and Scala.
* [PrimeFaces](https://www.primefaces.org) - JSF framework with both free and commercial/support versions and frontend components.
* [Ratpack](https://ratpack.io) - Set of libraries that facilitate fast, efficient, evolvable and well-tested HTTP applications.
* [Vaadin](https://vaadin.com) - Full-stack open-source Java framework that simplifies web app development. Build complex, interactive applications with Java alone, and enhance with TypeScript and React components, without needing deep JavaScript, CSS, or HTML expertise.
* [WebForms Core](https://github.com/webforms-core) - A technology for managing HTML tags from the server.

### Workflow Orchestration Engines

* [Cadence](https://cadenceworkflow.io) - Stateful code platform from Uber.
* [flowable](https://github.com/flowable/flowable-engine) ⭐ 9,068 | 🐛 385 | 🌐 Java | 📅 2026-02-04 - Compact and efficient workflow and business process management platform.
* [Temporal](https://temporal.io) - Microservice orchestration platform, forked from Cadence but gRPC based.

## Resources

### Related Awesome Lists

*Awesome Lists related to the Java & JVM ecosystem.*

* [Awesome Microservices](https://github.com/mfornos/awesome-microservices) ⭐ 14,128 | 🐛 7 | 📅 2026-01-17
* [Useful Java Links](https://github.com/Vedenin/useful-java-links) ⭐ 6,139 | 🐛 17 | 🌐 Java | 📅 2025-07-12
* [Java Developer Roadmap](https://github.com/s4kibs4mi/java-developer-roadmap) ⭐ 4,403 | 🐛 0 | 🌐 Java | 📅 2026-01-26
* [Awesome REST](https://github.com/marmelab/awesome-rest) ⭐ 3,840 | 🐛 13 | 📅 2026-01-03
* [AwesomeJavaFX](https://github.com/mhrimaz/AwesomeJavaFX) ⭐ 3,349 | 🐛 12 | 📅 2025-07-05
* [Awesome JVM](https://github.com/deephacks/awesome-jvm) ⭐ 2,154 | 🐛 15 | 📅 2022-08-30
* [ciandcd](https://github.com/ciandcd/awesome-ciandcd) ⭐ 1,982 | 🐛 19 | 📅 2024-04-01
* [Java Concurrency Checklist](https://github.com/code-review-checklists/java-concurrency) ⭐ 1,352 | 🐛 10 | 📅 2020-11-07
* [Awesome Selenium](https://github.com/christian-bromann/awesome-selenium) ⭐ 1,110 | 🐛 0 | 📅 2025-01-03
* [Awesome Annotation Processing](https://github.com/gunnarmorling/awesome-annotation-processing) ⭐ 534 | 🐛 2 | 📅 2024-11-16
* [Awesome Gradle Plugins](https://github.com/ksoichiro/awesome-gradle) ⭐ 481 | 🐛 3 | 📅 2023-10-08
* [Awesome Graal](https://github.com/neomatrix369/awesome-graal) ⭐ 368 | 🐛 3 | 🌐 Shell | 📅 2023-02-15
* [Awesome J2ME](https://github.com/hstsethi/awesome-j2me) ⭐ 307 | 🐛 1 | 🌐 Java | 📅 2025-11-22
* [Awesome Hybris](https://github.com/eminyagiz42/awesome-hybris) ⭐ 49 | 🐛 0 | 📅 2025-08-29
* [Awesome Java libraries and hidden gems](https://libs.tech/java)

### Communities

*Active discussions.*

* [r/java](https://www.reddit.com/r/java/) - Subreddit for the Java community.
* [Stack Overflow](https://stackoverflow.com/questions/tagged/java) - Question/answer platform.

### Frontends

*Websites that provide a frontend for this list. Please note, there won't be an official website. We don't associate with a particular website and everybody is allowed to create one.*

* [java.libhunt.com](https://java.libhunt.com)

### Influential Books

*Books that made a big impact and are still worth reading.*

* [Core Java Volume I--Fundamentals](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)
* [Core Java, Volume II--Advanced Features](https://www.amazon.com/Core-Java-II-Advanced-Features-10th/dp/0134177290)
* [Effective Java (3rd Edition)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)
* [Head First Java (3rd Edition)](https://www.oreilly.com/library/view/head-first-java/9781492091646/)
* [Java Concurrency in Practice](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
* [The Well-Grounded Java Developer (2nd Edition)](https://www.manning.com/books/the-well-grounded-java-developer-second-edition)
* [Thinking in Java](https://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

### Podcasts and Screencasts

*Something to look at or listen to while programming.*

* [140 Second Ducklings](https://twitter.com/debugagent/status/1491075324805001219) - Short videos on Twitter explaining Java debugging in depth.
* [A Bootiful Podcast](https://bootifulpodcast.fm)
* [Foojay Podcast](https://foojay.io/today/category/podcast/)
* [Inside Java](https://inside.java/podcast) (Official)
* [Java Off Heap](http://www.javaoffheap.com)
* [The Java Posse](http://www.javaposse.com) - Discontinued as of 02/2015.

### People

#### Socials

*Active accounts to follow. Descriptions from their socials.*

* [Adam Bien](https://twitter.com/AdamBien) - Freelance author, JavaOne Rockstar speaker, consultant, Java Champion.
* [Aleksey Shipilëv](https://twitter.com/shipilev) - Performance geek, benchmarking czar, concurrency bug hunter.
* [Antonio Goncalves](https://twitter.com/agoncal) - Java Champion, JUG Leader, Devoxx France, Java EE 6/7, JCP, Author.
* [Arun Gupta](https://twitter.com/arungupta) - Java Champion, JavaOne Rockstar, JUG Leader, Devoxx4Kids-er, VP of Developer Advocacy at Couchbase.
* [Brian Goetz](https://bsky.app/profile/briangoetz.bsky.social) - Java Language Architect at Oracle.
* [Bruno Borges](https://twitter.com/brunoborges) - Product Manager/Java Jock at Oracle.
* [Chris Engelbert](https://twitter.com/noctarius2k) - Open Source Enthusiast, Speaker, Developer, Developer Advocacy at TimescaleDB.
* [Chris Richardson](https://bsky.app/profile/crichardson.bsky.social) - Software architect, consultant, and serial entrepreneur, Java Champion, JavaOne Rock Star, \*POJOs in Action- author.
* [Ed Burns](https://twitter.com/edburns) - Consulting Member of the Technical Staff at Oracle.
* [Eugen Paraschiv](https://twitter.com/baeldung) - Author of the Spring Security Course.
* [Heinz Kabutz](https://twitter.com/heinzkabutz) - Java Champion, speaker, author of The Java Specialists' Newsletter, concurrency performance expert.
* [Holly Cummins](https://twitter.com/holly_cummins) - Technical Lead of IBM London's Bluemix Garage, Java Champion, developer, author, JavaOne rockstar.
* [James Weaver](https://twitter.com/JavaFXpert) - Java/JavaFX/IoT developer, author and speaker.
* [Java](https://twitter.com/java) - Official Java Twitter account.
* [Javin Paul](https://twitter.com/javinpaul) - Well-known Java blogger.
* [Josh Long](https://twitter.com/starbuxman) - Spring Advocate at Pivotal, author of O'Reilly's Cloud Native Java- and Building Microservices with Spring Boot, JavaOne Rock Star.
* [Lukas Eder](https://bsky.app/profile/lukaseder.bsky.social) - Java Champion, speaker, Founder and CEO Data Geekery (jOOQ).
* [Mani Sarkar](https://twitter.com/theNeomatrix369) - Java champion, Polyglot, Software Crafter involved with @graalvm, AI/ML/DL, Data Science, Developer communities, speaker & blogger. Creator of couple of awesome lists like this one.
* [Mario Fusco](https://twitter.com/mariofusco) - RedHatter, JUG coordinator, frequent speaker and author.
* [Mark Heckler](https://twitter.com/MkHeck) - Pivotal Principal Technologist and Developer Advocate, conference speaker, published author, and Java Champion, focusing on Internet of Things and the cloud.
* [Markus Eisele](https://twitter.com/myfear) - Java EE evangelist, Red Hat.
* [Martijn Verburg](https://twitter.com/karianna) - London JUG co-leader, speaker, author, Java Champion and much more.
* [Martin Thompson](https://twitter.com/mjpt777) - Pasty faced performance gangster.
* [Monica Beckwith](https://twitter.com/mon_beck) - Performance consultant, JavaOne Rock Star.
* [OpenJDK](https://twitter.com/OpenJDK) - Official OpenJDK account.
* [Peter Lawrey](https://twitter.com/PeterLawrey) - Peter Lawrey, Java performance expert.
* [Randy Shoup](https://twitter.com/randyshoup) - Stitch Fix VP Engineering, speaker, JavaOne Rock Star.
* [Reza Rahman](https://twitter.com/reza_rahman) - Java EE/GlassFish/WebLogic evangelist, author, speaker, open source hacker.
* [Sander Mak](https://twitter.com/Sander_Mak) - Java Champion, author.
* [Simon Maple](https://twitter.com/sjmaple) - Java Champion, VirtualJUG founder, LJC leader, RebelLabs author.
* [Spencer Gibb](https://twitter.com/spencerbgibb) - Software Engineer, Dad, Geek, Co-founder and Lead of Spring Cloud Core @pivotal.
* [Stephen Colebourne](https://bsky.app/profile/jodastephen.bsky.social) - Java Champion, speaker.
* [Trisha Gee](https://twitter.com/trisha_gee) - Java Champion and speaker.
* [Venkat Subramaniam](https://twitter.com/venkat_s) - Author, University of Houston professor, MicroSoft MVP award recipient, JavaOne Rock Star, Java Champion.
* [Vlad Mihalcea](https://twitter.com/vlad_mihalcea) - Java Champion working on Hypersistence Optimizer, database aficionado, author of High-Performance Java Persistence book.

### Websites

*Sites to read.*

* [Baeldung](https://www.baeldung.com)
* [Dzone](https://dzone.com)
* [foojay.io](https://foojay.io)
* [Google Java Style](https://google.github.io/styleguide/javaguide.html)
* [InfoQ](https://www.infoq.com)
* [Java Algorithms and Clients](https://algs4.cs.princeton.edu/code)
* [Java, SQL, and jOOQ](https://blog.jooq.org)
* [Java.net](https://community.oracle.com/community/java)
* [Javalobby](https://dzone.com/java-jdk-development-tutorials-tools-news)
* [JavaWorld](https://www.javaworld.com)
* [JAXenter](https://jaxenter.com)
* [RebelLabs](https://zeroturnaround.com/rebellabs)
* [OverOps Blog](https://blog.overops.com)
* [TheServerSide.com](http://www.theserverside.com)
* [Vanilla Java](https://vanilla-java.github.io)
* [Voxxed](https://www.voxxed.com)
* [Java Weekly](https://discu.eu/weekly/java/)

## Contributing

Contributions are very welcome!

Please have a look at the [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) ⭐ 46,952 | 🐛 2 | 📅 2026-02-07 guidelines and [the validation tools](https://github.com/akullpp/awesome-java-lint) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2020-07-19.

[c]: https://cdn.rawgit.com/akullpp/23246ca832bda82bb505230bf3538e2a/raw/d9bcdb769bf025292f9c6bc1290f01f1fcd1f864/commercial.svg