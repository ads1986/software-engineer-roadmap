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

- [[1] Abstract Factory](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/creational/abstractFactory)
- [[1] Singleton](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/creational/singleton)
- [[1] Factory Method](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/creational/factory)
- [[1] Prototype](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/creational/prototype)
- [[1] Builder](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/creational/builder)

#### 3.2.2. Structural

- [[1] Adapter](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/structural/adapter)
- [[1] Bridge](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/structural/bridge)
- [[1] Decorator](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/structural/decorator)
- [[1] Composite](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/structural/composite)
- [[1] Proxy](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/structural/proxy)
- [[1] Flyweight](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/structural/flightweight)
- [[1] Facade](

#### 3.2.2. Behavioral

- [[1] Chain of Responsability](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/behavioral/chain)
- [[1] Command](https://github.com/ads1986/design-patterns-examples/tree/main/src/main/java/com/design/patterns/behavioral/command)
- Interpreter
- Iterator
- Mediator
- Memento
- Observer
- State
- Strategy
- Template Method
- Visitor

### 3.3. ²Enterprise Integration Patterns (Solve the problems related to the integration between systems)

#### 3.3.1. Messaging

- [1] Message Channel
- Message
- [1] Pipes and Filters
- [1] Message Router
- [1] Message Translator
- [1] Message Endpoint

#### 3.3.2. Message Channel

- Point-to-Point Channel
- Publish-Subscribe Channel
- Datatype Channel
- Invalid Message Channel
- Dead Letter Channel
- Guaranteed Delivery
- Channel Adapter
- Messaging Bridge
- Message Bus

#### 3.3.3. Message Construction

- Command Message
- Document Message
- Event Message
- Request-Reply
- Return Address
- Correlation Identifier
- Message Sequence
- Message Expiration
- Format Indicator

#### 3.3.4. Message Router

- Content-Based Router
- Message Filter
- Dynamic Router
- Recipient List
- Splitter
- Aggregator
- Resequencer
- Composed Message Processor
- Scatter-Gather
- Routing Slip
- Process Manager
- Message Broker

#### 3.3.5. Message Transformation

- Envelope Wrapper
- Content Enricher
- Content Filter
- Claim Check
- Normalizer
- Canonical Data Model

#### 3.3.6. Message Endpoint

- Messaging Gateway
- Messaging Mapper
- Transactional Client
- Polling Consumer
- Event-Driven Consumer
- Competing Consumers
- Message Dispatcher
- Selective Consumer
- Durable Subscriber
- Idempotent Receiver
- Service Activator

#### 3.3.6. System Management

- Control Bus
- Detour
- Wire Tap
- Message History
- Message Store
- Smart Proxy
- Test Message
- Channel Purger

### 3.4. ³Pattern-Oriented Software Architecture (POSA)

#### 3.4.1. Software architecture

- [1] Domain model
- [1] Layers
- [1] Model-View-Controller
- [1] Presentation-Abstraction-Control
- [1] Microkernel
- [1] Reflection
- [1] Shared repository
- [1] Blackboard
- [1] Domain object

#### 3.4.2. Distribution Infrastructure

- [1] Publisher-subscriber
- [1] Message Broker
- [1] Client proxy
- [1] Requestor
- [1] Invoker
- [1] Client request handler
- [1] Server request handler

#### 3.4.3. Adaptation and execution

- [1] Object Adapter
- [1] Interceptor
- [1] Execute-Around Object
- [1] Null Object
- [1] Wrapper Facade
- [1] Declarative component configuration

#### 3.4.4. Resource management

- [1] Container
- [1] Component Configurator
- [1] Object manager
- [1] Lookup
- [1] Virtual Proxy
- [1] Lifecycle callback
- [1] Task coordinator
- [1] Resource pool
- [1] Resource cache
- [1] Lazy Acquisition
- [1] Eager Acquisition
- [1] Partial Acquisition
- [1] Activator
- [1] Evictor
- [1] Leasing
- [1] Automated Garbage Collection
- [1] Counting Handle
- [1] Disposal Method

#### 3.4.5. Database access

- [1] Database Access Layer
- [1] Data mapper
- [1] Row Data Gateway
- [1] Table Data Gateway
- [1] Active Record

### 3.5. Enterprise Patterns

- [1] Transaction Script
- [1] Data Transfer Object (DTO)
- [1] Identity Maps
- [1] Interactors
- [1] Use Cases
- [1] Repositories
- [1] Comands/Queries (CommandQuerySeparation)
- [1] Value Object
- [1] Entities
- [1] Object/Relational mapping (ORM)

### 3.6. Archtectural Principles

- [1] Policy(What should happen and when) vs Detail(Implementation of Policies)
- [1] Coupling & cohesion (high cohesion + low coupling)
- [1] Composition over inheritance
- [1] Encapsulate what varies
- [1] Program against abstractions
- [1] Holiwood principle (Don't call me, I you call you.)
- [1] Don't Repeat Yourself (DRY)
- [1] You aren't gonna need it (YAGNI)
- [1] Keep it simple, Stupid (KISS)
- [1] Law of Demeter
- [1] TellDontAsk

##### 3.6.1. Package Cohesion Principles
- [1] Reuse-Release Equivalent Principle (REP)
- [1] Common-Reuse Principle (CCP)
- [1] Common-Clojure Principle (CRP)

##### 3.6.2. Package Coupling Principles
- [1] Acyclic Dependency Principle (ADP)
- [1] Stable-Dependencies Principle (SDP)
- [1] Stable-Abstractions Princple (SAP)

##### 3.6.3. SOLID
- [1] Single Responsability Principle (SRP)
- [1] Open Close Principle (OCP)
- [1] Liskov Substitution Principle (LSP)
- [1] Interface Segragation Principle (ISP)
- [1] Dependency Inversion Principle (DIP)

### 3.7. Archtectural Styles (How to organize our code - Application design at the highest level of abstraction)

### 3.7.1. Structural

- [1] Component-based
- [1] Monolithic
- [1] Layered

### 3.7.2. Messaging

- [1] Event-Driven
- [1] Publish-Subscribe

### 3.7.2. Distributed

- [1] Client-Server
- [1] Peer-to-peer

### 3.8. Archtectural Patterns (Solve the problems related to the Architectural Style - a way to implement an Architectural Style)

- [1] CQRS
- [1] Event Sourcing
- [1] Domain-Driven Design
- [1] Hexagonal Archtecture (Archtecture Design Pattern)
- [1] Sagas
- [1] Software Orchestrated 
- [1] Software Choreography
- [1] Message Queues
- [1] Event Streaming	
- [1] Blackboard pattern
- [1] Servless Archtecture
- [1] Microkernel
- [1] Microservices
- [1] Three-tier
- [1] Model-View-Controller
- [1] Model-View-View-Model
- [1] SOA

## 4. Backend Ecosystem

### 4.1. Internet

- [1] How does the internet work ?
- [1] What is HTTP ?
- [1] Browsers and how they work ?
- [1] DNS and how it works ?
- [1] What is Domain Name
- [1] What is hosting ?

### 4.2. Basic Frontend Knowledge
- [1] HTML
- [1] CSS
- [1] JavaScript

### 4.3. OS and General Knowledge
- [1] Terminal Usage
- [1] How Os work in General
- [1] Process Managment
- [1] Threads and Concurrency
- [1] Basic Terminal Command
- [1] Memory Managment
- [1] Interprocess Communication
- [1] I/O Managment
- [1] POSIX Basics
- [1] Basic Networking Concepts
- [1] Process Managment
- [1] Sockets
- [1] Networking Concepts
- [1] Virtualization
- Memory/Storage
- File System
- Startup Managment (intid)
- Service Managment (systemd)

### 4.4. Learn a Language
- Java

### 4.5. Relational Databases

- PostgreSQL

### 4.6. NoSQL Databases

- Cassandra
- Mongo DB

### 4.7. More about Databases

- ORMs
- ACID
- Transactions
- N+1 Problem
- Data Replication
- Sharding Strategies
- CAP Theorem

### 4.7. Learn about APIs

- HATEOAS
- Open API Spec and Swagger
- JSON APIs
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