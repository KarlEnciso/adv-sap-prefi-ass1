## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
* A compilation of a bunch of services in one application to create a new process of application.

2. List and discuss the characteristics of SOA.
* Standardized Service Contracts = creating an agreement to follow specific tasks or rules to have clear communication by one or more service descriptions.
* Loose Coupling = some services need dependencies on each other to avoid any unnecessary impairment in the system.
* Service Abstraction = encapsulating a logic service that is unknown by the user since it should not show how it will perform its functionalities.
* Service Reusability = they reusing existing services.
* Service Autonomy = services is the one who can control all the encapsulated services.
* Service Statelessness = All services need to be stateless when it comes to sending a request from one state to the other. Since it should not keep any data.
* Service Discoverability = labeling specific tasks to help the user understand how the system works. So that, the user discovered easily the functionalities.
* Service Composability = a set of massive problems that split into small problems.
* Service Interoperability = services need to use standards to give the users their desired service.

3. Define Microservices.
* Also known as the microservice architecture - is an architectural style that structures an application as a collection of services that are Independent, deployable, Loosely coupled, Organized around business capabilities, and Owned by a small team

4. List and discuss the benefits of using Microservices.
* Independently Deployable = It can deploy without relying on other services.
* Right tool for the Job = It's the right tool because it's an architecture pattern that will help developers/ users use their desired applications. 
* Precise Scaling = It can deploy each service individually within its running time.

5. List and discuss the similarities and differences between SOA and Microservices.
- Differences - 
* When it comes to the architecture SOA is designed to share resources across services, while the Microservices are designed to host different services so that they can function independently.
* SOA shares data storage between services. While the Microservices can have independent data storage.
* SOA communicates via ESB and Microservices use the API layer to communicate.
* SOA depends on sharing resources, while the Microservices depend on the bounded context of coupling.
* SOA uses protocols and the Microservices use REST and JMS.

- Similarities - 
* They are both collection services.
* They are both efficiently used for cloud services.
* They are both architectural methods when it comes to managing and building applications.
