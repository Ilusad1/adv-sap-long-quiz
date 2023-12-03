## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
    - Service-Oriented Architecture (SOA) is a design approach for      structuring software systems into a collection of services. Within this architectural style, services are autonomous, self-contained entities that maintain loose coupling and interact through clearly defined interfaces. These services are capable of individual development, deployment, and scalability, fostering adaptability and modularity in extensive software systems

2. List and discuss the characteristics of SOA.
    - 1. Service
            -  essential components that act as building blocks. These modular and reusable entities carry out specific business functions, each serving a distinct purpose and accessible independently.
      2. Loose Coupling 
            - To ensure flexibility, services are loosely coupled, meaning modifications to one service don't directly impact others. Loose coupling facilitates easier maintenance, updates, and scalability.
      3. Interoperability
            - Interoperability is a key feature, as services communicate through well-defined interfaces, allowing seamless interaction between services developed in different technologies or by different teams.
      4. Reusability
            - Services are designed with reusability in mind, promoting efficiency by minimizing redundancy across various applications and projects.
      5. Discoverability
            - Discoverability is facilitated by registering services in a directory, simplifying the process for other services or applications to find and use them.
      6. Abstraction
            - Abstraction is employed to hide the internal details of services, revealing only the necessary functionality through clearly defined interfaces. This enables changes to the internal workings without affecting users of the service.
      7. Scalability
            - Scalability is achieved by independently adjusting the scale of services based on demand, optimizing resource utilization for enhanced performance.
      8. Security
            - Security is prioritized within SOA, with services implementing mechanisms such as authentication, authorization, and encryption to uphold data integrity and prevent unauthorized access.
      9. Service Contracts
            - Service contracts, in SOA, set clear and standardized guidelines specifying how services can be accessed, the required parameters, and the expected results.

3. Define Microservices.
    - Microservices in software development is an approach where a complex application is made up of small, independent units, each handling a specific business function. These units communicate through clear interfaces and can work independently during both development and deployment.

4. List and discuss the benefits of using Microservices.
    - 1. Decentralization 
            - Microservices work on their own, and each has its own way of doing things, like having its own code and storage.

      2. Autonomy 
            - They do their job without needing others, and teams can use different tools for each.

      3. Scalability 
            - If more or less is needed, each microservice can change by itself.

      4. Resilience 
            - If one microservice fails, it doesn't break everything. They can handle problems without causing big issues.

      5. Flexibility and Agility 
            - Microservices help software be more flexible and quick. They make it easier to build and change things fast.

      6. Continuous Delivery 
            - Microservices often release new things a lot, following a fast and efficient process.

      7. Isolation 
            - Each microservice is separate from others, keeping things from mixing up and causing unexpected problems.

      8. APIs and Communication
            -  Microservices talk to each other using clear rules, either right away or later, depending on what's needed.

5. List and discuss the similarities and differences of SOA and Microservices.
    - Similarities between SOA and Microservices:

    Service-Based Architecture:

    SOA: SOA and microservices both use a service-based architectural approach, breaking software systems into smaller, modular services.

    Microservices: Microservices architecture organizes an application into independent, self-contained services, reflecting its service-oriented nature.

    Loose Coupling:

    SOA: Both SOA and microservices emphasize a loose connection between services, striving to minimize the impact on other services when changes are made.

    Microservices: Like SOA, microservices promote independence among services, allowing them to evolve and scale separately.

    Interoperability:

    SOA: Both architectures rely on clear interfaces for communication between services to ensure interoperability.

    Microservices: Microservices use APIs to communicate, ensuring standardized interactions and aligning with SOA principles.

    Reusability:

    SOA: SOA services are made to be reused in different applications and projects.
    Microservices: Microservices are designed for reuse, encapsulating specific business functionalities for various contexts.

    Differences between SOA and Microservices:

    Scope and Size:

    SOA: Usually includes bigger, more comprehensive services that cover multiple business functions.

    Microservices: Consists of smaller, more detailed services, each dedicated to specific business capabilities and functioning independently.

    Autonomy and Independence:

    SOA: Services might be closely connected, needing coordination among different providers when changes are made.

    Microservices: Created for strong autonomy, enabling each service to operate independently without affecting others.

    Technology Stack:

    SOA: Uses a shared technology stack for communication, often depending on middleware solutions such as Enterprise Service Bus (ESB).

    Microservices: Provides flexibility in the technology stack, letting each service be developed using the most suitable tools and languages for its specific functionality.

    Data Management:

    SOA: Usually centralizes data management, using shared databases or centralized data services.

    Microservices: Prefers decentralization, where each service handles its own data storage, potentially resulting in polyglot persistence with various databases for different services.

    Deployment and Scaling:

    SOA: Services can be deployed together as part of a bigger application, and scaling may affect the whole application.

    Microservices: Can be deployed separately, enabling more detailed scaling based on the demand for each service.



6. Define Web Services.
    - A web service is a set of open protocols and standards that allow data to be exchanged between different applications or systems. Web services can be used by software programs written in a variety of programming languages and running on a variety of platforms to exchange data via computer networks such as the Internet in a similar way to inter-process communication on a single computer.

7. List and discuss the benefits of using Web Services.
     1. Business Functions can be exposed over the Internet
            - Because all apps are now accessible via the internet, Web services have become increasingly valuable. That is to say, the web service can be located anywhere on the internet and provide the required functionality.
     2. Interoperability
            - Web administrations allow diverse apps to communicate with one another and exchange information and services. Different apps can also make use of web services.
     3. Communication with Low Cost
            - Because web services employ the SOAP over HTTP protocol, you can use your existing low-cost internet connection to implement them.
     4. A Standard Protocol that Everyone Understands
            - Web services communicate via a defined industry protocol. In the web services protocol stack, all four layers (Service Transport, XML Messaging, Service Description, and Service Discovery) use well-defined protocols.
     5. Reusability
            - A single web service can be used simultaneously by several client applications.

8. List and discuss the characteristics of Web Services.
     1. XML Based
            - The information representation and record transportation layers of a web service employ XML.
     2. Loosely Coupled
            - A strongly coupled system means that the patron’s and server’s decisions are inextricably linked, indicating that if one interface changes, the other should be updated as well.
     3. Capability to be Synchronous or Asynchronous
            - Synchronicity refers to the client’s connection to the function’s execution. The client is blocked and the client has to wait for the service to complete its operation, before continuing in synchronous invocations. Asynchronous operations allow a client to invoke a task and then continue with other tasks.
     4. Coarse-Grained
            - Web services generation is an easy approach to define coarse-grained services that have access to enough commercial enterprise logic.
9. List and discuss the distinct roles in Web Services Architecture.
     1. Service provider
            - A service provider provides the interface for the web service and the implementation of the application. The service provider is also responsible for creating the definition of the service and publishing that definition to meet the Universal Description, Discovery, and Integration (UDDI) specification.
     2. Service registry
            - A service registry is a way in which web services are formally published. The service registry is based on the UDDI specification and reflects information about services provided by the service provider. The service registry provides a service requester with a Web Services Description Language (WSDL) service description and a Uniform Resource Locator (URL) that points to the service itself.
     3. Service requester
            - A service requester is the consumer of a web service and uses the service registry to gain information about, and access to, a web service.

10. List and discuss the Web Services Components.
     1. SOAP (Simple Object Access Protocol)
            - It is a transport-independent messaging protocol. SOAP is built on sending XML data in the form of SOAP Messages. A document known as an XML document is attached to each message. Only the structure of the XML document, not the content, follows a pattern. The best thing about Web services and SOAP is that everything is sent through HTTP, the standard web protocol.
     2. UDDI (Universal Description, Discovery, and Integration)
            - UDDI is a standard for specifying, publishing and discovering a service provider’s online services. It provides a specification that aids in the hosting of data via web services.
     3. WSDL (Web Services Description Language)
            - The WSDL file is another XML-based file that explains what the web service does to the client application. The client application will be able to understand where the web service is located and how to use it by using the WSDL document.

