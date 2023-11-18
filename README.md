## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
- Service Oriented Architecture is known as a style of a software design where services are provided to the other components by application components. In addition, it also gives way to make sofware components to be reusable and interoprable. In here, each of the services is composed of the code and data integrations required to execute the specific function of the business. SOA allows it easier for software components on computers connected over a network to cooperate.

2. List and discuss the characteristics of SOA.
- Some characteristics of SOA are: 
*Interoperability - Allows services to operate and communicate with each other regardless of the platform or language is being used. 

*Composability - Services allows to be combined to achieve more complex functionality. This allows for the creation of composite applications or business processes that use multiple services.

*Discoverability - Services can be understood and discovered by others. It stores metadata in a service registry or profile documents

*Statelessness-  It doesn't store information from one session to the next. This makes them more scalable and reliable. It also supports the design of agnostic logic and improve service reuse.

*Autonomy - In here services have control over the logic they encapsulate and are developed and deployed independently. It gives increased realibility and behavioural predictability.

*Service Reusability - Services are designed to be reused. This means that a service can be used by multiple applications at the same time, which can lead to significant cost savings and increased efficiency.

*Abstraction - Services mask the complexity of their underlying reasoning. They make it easy for other services or apps to use them without being aware of the specifics of how they operate by exposing functionality while hiding the process.

*Loose Coupling - Services within SOA are loosely coupled. Wherein it means that they can operate independently of each other. This allows for greater flexibility and less dependency between different services.

*Standardized Serice Contracts - Service contract is a formal agreement between a service provider and a service consumer that outlines the functionality provided by the service. Services use service contracts in order to express their purpose and capabilities. 

3. Define Microservices.
- It is an achitectural style that structures an application as a collection of small autonomous services, modeled around a business domain. Microservice architecture are build up of loosely coupled, reusable and specialized components. This is usually used to build individual applications in a way that makes them more agile, scalable and resilient. With the use of Microservice, teams can update more codes easily and uses different stacks for different components.

4. List and discuss the benefits of using Microservices.
With the help of Microservies codes can be updated easily, teams can use diffrent stacks for different component. Addition to this, here are some addition of the benefits of using Microservices are: 
* Scalability: Microservices allow for individual services to be scaled independently based on the specific needs of the application. This means that resources can be allocated efficiently, resulting in better performance and cost optimization.

*Flexibility and Agility: Microservices enable flexibility in development and deployment. Each service can be developed, tested, and deployed independently, allowing for faster iterations and the ability to introduce new features or updates without impacting the entire system.

*Precise Scaling - Services can be deploye individually but can be scaled individually. 

*Container compatibility- Microservices components are suited for deployment and management within virtual containers, using well-proven container and orchestration technologies.

*Flexibility and Agility: Microservices enable flexibility in development and deployment. Each service can be developed, tested, and deployed independently, allowing for faster iterations and the ability to introduce new features or updates without impacting the entire system.

5. List and discuss the similarities and differences of SOA and Microservices.
•	Similarities
o	SOA And Microservices are both considered as architectural styles that structures an application. 
o	These two architectural promotes reusability, because services that are created in here allows to be reused by different applications. 
o	It focuses on business functionality and capabilities.
o	SOA and Microservices aim’s to break down application into a smaller and manageable application. 

•	Differences
o	All database can share the same database while Microservice has its own database. 
o	SOA performs large related task in contrast Microservice only performs single task.

