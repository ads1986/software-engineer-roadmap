# Software Engineer Roadmap

As a Software Engineer I've been facing the same dilemma when deciding what I should learn to improve my skills and learn new things. There's no a right or wrong answer, but I started to dig more about what I should learn that I could improve and evolve in my career.

Based on very good books and articles, I created a Software Engineer Roadmap, that have helping me to keep track of my learning and give me the big picture of the hole key points I should learn.

## 1. Checklist of Learning

To have the control of what I learned and how many times I visited a specific topic, I include a number inside square brackets before the topic`s name. This number will be increased every time I revisited the topic. If the learning generate any artefact, a link will be included in the topic as in the example below :

- [[1] Some Topic](https://github.com/ads1986/algorithms-and-datastructure/blob/main/src/main/java/com/algorithms/BFS.java)

## 2. Algorithm & Data Structure

### 2.1. Algorithms

- [[1] Breadth-First Search](https://github.com/ads1986/algorithms-and-datastructure/blob/main/src/main/java/com/algorithms/BFS.java)
- [[1] Depth-First Search](https://github.com/ads1986/algorithms-and-datastructure/blob/main/src/main/java/com/algorithms/DFS.java)
- Binary Search
- Merge Sort
- Quick Sort

### 2.2. Datastructures

- [[1] LinkedList](https://github.com/ads1986/algorithms-and-datastructure/blob/main/src/main/java/com/datastructure/LinkedList.java)
- [[1] Trees](https://github.com/ads1986/algorithms-and-datastructure/blob/main/src/main/java/com/datastructure/Tree.java)
- [[1] Tries](https://github.com/ads1986/algorithms-and-datastructure/blob/main/src/main/java/com/datastructure/trie/Trie.java)
- [[1] Graphs](https://github.com/ads1986/algorithms-and-datastructure/blob/main/src/main/java/com/datastructure/graph/Graph.java)
- Stacks
- Queues
- [[1] Heaps](https://github.com/ads1986/algorithms-and-datastructure/blob/main/src/main/java/com/datastructure/Heap.java)
- Vectors
- ArrayLists
- Hash Tables

### 2.3. Concepts

- Bit Manipulation
- Memory (Stack vs Heap)
- Recursion
- Dynamic Programming
- Big O Time & Space

## 3. Software Architecture

### 3.1. Programming Paradigms

- [1] Structured Programing
- Functional Programing
- [1] Object-oriented Programing

### 3.2. ¹Design Patterns (Solve a localised problem)

#### 3.2.1. Creational

[1] Abstract Factory
[1] Singleton
[1] Factory Method
[1] Prototype
[1] Builder

    ✓ Structural

        ✓ Adapter
        ✓ Bridge
        ✓ Decorator
        ✓ Composite
        ✓ Proxy
        ✓ Flyweight
        ✓ Facade

    Behavioral
        ✓ Chain of Responsability
        ✓ Command
        Interpreter
        Iterator
        Mediator
        Memento
        Observer
        State
        Strategy
        Template Method
        Visitor

²Enterprise Integration Patterns (Solve the problems related to the integration between systems)

    Messaging

        ✓ Message Channel
        Message
        ✓ Pipes and Filters
        ✓ Message Router
        ✓ Message Translator
        ✓ Message Endpoint

    Message Channel

        Point-to-Point Channel
        Publish-Subscribe Channel
        Datatype Channel
        Invalid Message Channel
        Dead Letter Channel
        Guaranteed Delivery
        Channel Adapter
        Messaging Bridge
        Message Bus

    Message Construction

        Command Message
        Document Message
        Event Message
        Request-Reply
        Return Address
        Correlation Identifier
        Message Sequence
        Message Expiration
        Format Indicator

    Message Router

        Content-Based Router
        Message Filter
        Dynamic Router
        Recipient List
        Splitter
        Aggregator
        Resequencer
        Composed Message Processor
        Scatter-Gather
        Routing Slip
        Process Manager
        Message Broker

    Message Transformation

        Envelope Wrapper
        Content Enricher
        Content Filter
        Claim Check
        Normalizer
        Canonical Data Model

    Message Endpoint

        Messaging Gateway
        Messaging Mapper
        Transactional Client
        Polling Consumer
        Event-Driven Consumer
        Competing Consumers
        Message Dispatcher
        Selective Consumer
        Durable Subscriber
        Idempotent Receiver
        Service Activator

    System Management

        Control Bus
        Detour
        Wire Tap
        Message History
        Message Store
        Smart Proxy
        Test Message
        Channel Purger

³Pattern-Oriented Software Architecture (POSA)

        Software architecture

            ✓ Domain model
            ✓ Layers
            ✓ Model-View-Controller
            ✓ Presentation-Abstraction-Control
            ✓ Microkernel
            ✓ Reflection
            ✓ Shared repository
            ✓ Blackboard
            ✓ Domain object
        
        Distribution Infrastructure

            ✓ Publisher-subscriber
            ✓ Message Broker
            ✓ Client proxy
            ✓ Requestor
            ✓ Invoker
            ✓ Client request handler
            ✓ Server request handler

        Adaptation and execution

            ✓ Object Adapter
            ✓ Interceptor
            ✓ Execute-Around Object
            ✓ Null Object
            ✓ Wrapper Facade
            ✓ Declarative component configuration
        
        Resource management

            ✓ Container
            ✓ Component Configurator
            ✓ Object manager
            ✓ Lookup
            ✓ Virtual Proxy
            ✓ Lifecycle callback
            ✓ Task coordinator
            ✓ Resource pool
            ✓ Resource cache
            ✓ Lazy Acquisition
            ✓ Eager Acquisition
            ✓ Partial Acquisition
            ✓ Activator
            ✓ Evictor
            ✓ Leasing
            ✓ Automated Garbage Collection
            ✓ Counting Handle
            ✓ Disposal Method

        Database access

            ✓ Database Access Layer
            ✓ Data mapper
            ✓ Row Data Gateway
            ✓ Table Data Gateway
            ✓ Active Record

Enterprise Patterns

    ✓ Transaction Script
    ✓ Data Transfer Object (DTO)
    ✓ Identity Maps
    ✓ Interactors
    ✓ Use Cases
    ✓ Repositories
    ✓ Comands/Queries (CommandQuerySeparation)
    ✓ Value Object
    ✓ Entities
    ✓ Object/Relational mapping (ORM)

Archtectural Principles

    ✓ Policy(What should happen and when) vs Detail(Implementation of Policies)
    ✓ Coupling & cohesion (high cohesion + low coupling)
    ✓ Composition over inheritance
    ✓ Encapsulate what varies
    ✓ Program against abstractions
    ✓ Holiwood principle (Don't call me, I you call you.)
    ✓ Don't Repeat Yourself (DRY)
    ✓ You aren't gonna need it (YAGNI)
    ✓ Keep it simple, Stupid (KISS)
    ✓ Law of Demeter
    ✓ TellDontAsk

    ✓ Package Cohesion Principles
        ✓ Reuse-Release Equivalent Principle (REP)
        ✓ Common-Reuse Principle (CCP)
        ✓ Common-Clojure Principle (CRP)

    ✓ Package Coupling Principles
        ✓ Acyclic Dependency Principle (ADP)
        ✓ Stable-Dependencies Principle (SDP)
        ✓ Stable-Abstractions Princple (SAP)

    ✓ SOLID
        ✓ Single Responsability Principle (SRP)
        ✓ Open Close Principle (OCP)
        ✓ Liskov Substitution Principle (LSP)
        ✓ Interface Segragation Principle (ISP)
        ✓ Dependency Inversion Principle (DIP)

Archtectural Styles (How to organize our code - Application design at the highest level of abstraction)

    ✓ Structural
        ✓ Component-based
        ✓ Monolithic
        ✓ Layered

    ✓ Messaging
        ✓ Event-Driven
        ✓ Publish-Subscribe

    ✓ Distributed
        ✓ Client-Server
        ✓ Peer-to-peer

Archtectural Patterns (Solve the problems related to the Architectural Style - a way to implement an Architectural Style)

    ✓ CQRS
    ✓ Event Sourcing
    ✓ Domain-Driven Design
    ✓ Hexagonal Archtecture (Archtecture Design Pattern)
    ✓ Sagas
    ✓ Software Orchestrated 
    ✓ Software Choreography
    ✓ Message Queues
    ✓ Event Streaming	
    ✓ Blackboard pattern
    ✓ Servless Archtecture
    ✓ Microkernel
    ✓ Microservices
    ✓ Three-tier
    ✓ Model-View-Controller
    ✓ Model-View-View-Model
    ✓ SOA

===========================
Backend RoadMap
===========================

	Internet

		✓ How does the internet work ?
		✓ Wha is HTTP ?
		✓ Browsers and how they work ?
		✓ DNS and how it works ?
		✓ What is Domain Name
		✓ What is hosting ?

	Basic Frontend Knowledge
		✓ HTML
		✓ CSS
		✓ JavaScript

	OS and General Knowledge
		✓ Terminal Usage
		✓ How Os work in General
		✓ Process Managment
		✓ Threads and Concurrency
		✓ Basic Terminal Command
		✓ Memory Managment
		✓ Interprocess Communication
		✓ I/O Managment
		✓ POSIX Basics
		✓ Basic Networking Concepts
		✓ Process Managment
		✓ Sockets
		✓ Networking Concepts
		✓ Virtualization
		Memory/Storage
		File System
		Startup Managment (intid)
		Service Managment (systemd)

	Learn a Language
		✓ Java

	Relational Databases
		PostgreSQL

	NoSQL Databases
		Mongo DB

	More about Databases
		ORMs
		ACID
		Transactions
		N+1 Problem
		Data Replication
		Sharding Strategies
		CAP Theorem

	Learn about APIs
		HATEOAS
		Open API Spec and Swagger
		JSON APIs
		SOAP
		✓ gRPC
		Authentication
			Cookie Based
			✓ OAuth2
			Basic Authentication
			Token Authentication
			JWT
			Open ID
			SAML

	Networking, Security and Protocols

		Emails
			SMTP
			IMAPS
			POP3S
			DMARC
			SPF
			Domain Keys

		✓ HTTP
		FTP
		Port Forwarding

	Web Security Knowledge
		Hashing Algorithms
			MD5 and why not to use it
			SHA Family
			scrypt
			bcrypt
		HTTPS
		Content Security Policy
		CORS
		SSL/TLS
		OWASP Security Risks
		SSH

	Caching
		CDN
		Client Side
		Server Side
			Redis
			Memcached

	CI/CD

	Design and Development Principles
		GOF Design Patterns
		Domain Driven Design
		Test Driven Development
		SOLID
		KISS
		YAGNI
		DRY

	Message Brokers
		Rabbit MQ
		✓ Kafka

	Conteinerization vs Virtualization
		Docker
		RKT
		LXC

	GraphQL
		Apollo
		Relay Modern

	Graph Databases
		Neo4j

	✓ WebSockets
	
	Integration
	    ✓ Apache Camel

	Web Servers
		Nginx
		Apache

	Building for Scale

		Understand the Diff.
			Instrumentation
			Monitoring
			Telemetry

		Migration Strategies

		Horizontal vs Vertical Scaling

		Building with Observability in mind

===========================
Devops RoadMap
===========================

	Operation System
		Linux
			Ubuntu
			CentOS
			RHEL

		Unix
			FreeBSD

	Learn to live in Terminal

		Learn Bash Scripting
		Vim/Nano/PowerShell/Emacs
		Compiling apps from source (gcc, make and other related stuff)
		System Performance (nmon, iostat,sar,vmstat)
		Others (strace, dtrace, systemtap, uname, df and history)
		Text Manipulation Tools (awk, sed, grep , uniq, cat, cut, echo, fmt, tr, nl, egrep, fgrep and WebSockets)
		Process Monotoring (ps, top, htop, atop and lsof)

	What is and how to setup a ____
		Reserve Proxy
		Forward Proxy
		Caching Server
		Load Balancer
		Firewall

	Web Server
		Ngnix
		Apache

	Learn Infrastructure as Code

		Containers
			Docker
			LXC

		Configuration Managment
			Ansible
			Salt
			Chef
			Puppet

		Container Orchestration
			✓ Kubernetes
			Docker Swarm
			Mesos
			Nomad

		Infrastructure Provisiong
			Terraform
			CloudFormation
			Pulumi

		Learn some CI/CD Tool
			Gitlab CI
			Jenkins
			GiHub Actions

	Learn how to monitor sofware and infrastructure

		Infrastructure Monitoring	
			Prometheus
			Grafana

		Application Monitoring
			Dynatrace
			Jaeger
			New Relic

		Logs Management
			Elastic Stack (Kibana)
			Splunk
			GrayLog
			Papertrail

	Cloud

		✓ PaaS (Platform as a Service)

		IaaS (Infrastructure as a Service)

		SaaS (Software as a Service)

		Faas (Function as a Service)

		Providers
			AWS
			Google Cloud
			Azure
			Digital Ocean

		Design Patterns 
			Availabillity
			Data Management
			Design and Implementation
			Management and Monitoring

===========================
Fonts
===========================

Backend RoadMap : https://github.com/kamranahmedse/developer-roadmap/blob/master/img/backend.png?year-2020-2
DevOps RoadMap : https://github.com/kamranahmedse/developer-roadmap/blob/master/img/devops.png
Algorithm & Datastructure : Cracking The Code Interview (Page 61)
Archtecture : https://github.com/AlaaAttya/software-architect-roadmap
https://github.com/stemmlerjs/software-design-and-architecture-roadmap

===========================
Notes
===========================

¹ Patterns presented here where removed in "²Pattern-Oriented Software Architecture (POSA)" topic, just for not repeat patterns in both topics.
² Patterns presented here where removed in "²Pattern-Oriented Software Architecture (POSA)" topic, just for not repeat patterns in both topics.
³ Patterns presented here, where removed in "Enterprise Patterns" topic, just for not repeat patterns in both topics.