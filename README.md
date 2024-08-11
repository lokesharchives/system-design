# system-design
My System Design Reference


# What is system design?

Simply put, System Design is about Planning and Structuring a system in a way that ensures it meets both functional and non functional requirements (performance, scalability, reliability, and security).

# Why it is Important?

System Design rovides a blueprint that guides development, preventing costly redesigns and ensuring the system meets user and business needs. System Design is the first step to start with once we start developing a large scale system.

# System Design Views

When starting with a system design we start with 
*High-Level Design (HLD)* 
In the HLD we focus on System's Components, Interactions between them and Data Flow between them. In HLD we will be creating

1. *Architecture Diagram:* Illustrates the system's major components and their interactions.
2. *Component Design:* Defines how each component or service will be developed and interact with others.
3. *Data Flow Diagrams:* Depict how data moves through the system and is processed.
4. *Technology Stack:* Choosing appropriate technologies for different parts of the system.

Once we are done with HLD we will start our *Low Level Design (LLD)*. In LLD we furthur focus on detailed design of each component we designed in HLD. Like - 
1. *Class Diagrams*: Describe the object-oriented design and relationships between classes.
2. *Database Schema Design*: Details the structure of the database, including tables, relationships, and indexing strategies.
3. *API Design*: Specifies the endpoints, methods, and data structures used for communication between different parts of the system.
4. *Algorithms and Logic*: Defines the algorithms and logic that each component will use.

In System Design while we are designing Functinal Capabilites of the system it is very important to consider non functional attributes like -
*Scalability*: How the system can handle growth, such as increased user load or data volume.
*Performance*: Ensuring the system can process requests efficiently.
*Reliability*: Ensuring the system is robust and can handle failures gracefully.
*Security*: Protecting the system from unauthorized access and vulnerabilities.
*Maintainability*: Designing the system so it can be easily updated and managed over time.
*Cost*: Balancing the budget while meeting the system’s needs.
