## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
-Soa is a middleweight solution which makes two or more system or application to talk each other.
And also SOA is often used in the large of development, distributed system where flexibility, scalability,
and reusability are crucial.It's been widely adopted to IT environments to improve agility of the system
software components and business processes.

2. List and discuss the characteristics of SOA.
Standrtdized Service Contracts
-It is a service to use contracts like to express their purpose,
express what their capabilities are, and it use formal standardized service contacts

Loose Couple
-Every Services in Soa is designed to be an independent, they will defined to interact through interfaces

ABSTRACTION
- Services is being expose well-defined interface and also this services making it easier to understand and to use

SERVICE REUSABILITY 
- Also every services in SOA is designed to be reusable in every different contexts and applications to avoid
duplicating across multiple systems

AUTONOMY
- In SOA Autonomy is each service is designed to operate independently of other services, so it have a own set of
rules,policies, and functionality without being coupled to the other services.

STATELESSNESS
- In Soa Statelessness is each service operates without retaining information about the state of the user or the system between requests. This means that every request from a client contains all the information needed to fulfill that request, and the service does not rely on any stored state information from previous requests.

DISCOVERABILITY
- The services can be able to discovered in service registry and also that service is contain appropriate metadate
for discovery which is also to communicates purpose and capabilities to humans.

COMPOSABILITY
- This kind of Services can be able to combined or to composed to create the new applications or business processes.

INTEROPERABILITY
- This service should be able to use standard that can be allow diverse subscribers to use the service or to use the function of the service.

3. Define Microservices.
- The Microservices is an architectural style that can be approach to developinng a software applications
as a collection of small.

4. List and discuss the benefits of using Microservices.
INDEPENDENTLY DEPLOYABLE
- Each services is smaller and independently deployable microservices and the small size of the services is combined with their clear boundaries and communication patterns to make it easier for the new team members to 
understand to codes and contribute to it quickly clear benefits of both speed and employee morale.

RIGHT TOOL FOR THE JOB
- In the common traditional patterns an application is typically shares the common stacks with a large relational database to support the entire applications

PRECISE SCALING
- In individual services can be individually deployed but it can be a individually scaled, as well. And another primary benefit of microservices is that each invidual component can be adopted the stack best fit to the specific job

5. List and discuss the similarities and differences of SOA and Microservices.
COMMUNICATION
- In Microservices every services is developed indenpendenty with it own communication protocols, While in Soa every services is need to share common communication mechanism and its called enterprise service bus (ESB)

INTEROPERABILITY
- In Microservice use a lightweight messaging protocols, While in SOA are more open to heterogeneous messaging protocols

SPEED
- In SOA simplyfy development and troubleshooting, While is microservices minimize sharing in favor of duplicaton
