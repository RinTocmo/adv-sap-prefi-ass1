## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
- Based on my understanding from the handout, Service-Oriented Architecture (SOA) is a software development approach that focuses on creating reusable software components, or services. These services are specialized to handle distinct business tasks or functions, each dedicated to performing a specific process or job. 

2. List and discuss the characteristics of SOA.
- There are 9 characteristics of SOA which are:
	Standardized Service Contracts: In this characteristic, the contracts should be formal and standardized. It should express their purpose and capabilities
	Loose Coupling: This is a way of connecting different services in a system which minimize on each other. It create specific relationships in which each services, in my opinion, has a specific role or job to do that helps reduce dependencies.
	Abstraction: This characteristic perform actions without revealing all the actions that they do to the outside world. They hide those unnecessary informations to avoid overwhelming users.
	Service Reusability: This characteristic is intended to maximize service reuse
	Authonomy: The services should have control to the logic and to achieve that, the services must be more isolated.
	Statelessness: The services should not have a state.
	Discoverability: The services should be discoverable.
	Composability: The services divides complex problems into smaller, more manageable pieces. It allows flexible service contracts to accommodate various types of interactions and integrations.
	Interoperability: It ensures that services adhere to widely accepted standards, enabling various users or systems with different technologies to effectively utilize the service. It's so commonly expected in modern practices that its significance as a guiding principle is sometimes overlooked.
	
3. Define Microservices.
-  Microservises is similar to SOA, however, instead of implementing them across an entire enterprise, microservices are commonly employed to construct individual applications that enhance their agility, scalability, and resilience.

4. List and discuss the benefits of using Microservices.
- There are 3 benefits of using Microservices
	Independently Deployable: Microservices offers organizations a solution to the frustration of long delays associated with implementing minor changes, because of their smaller size and standalone nature. Organizations can swiftly operate in response to changing needs, benefiting from clearer communication patterns and easily integrating new team members into the codebase, boosting both speed and team morale by forming smole and agile teams around individual services. 
	Right tool for the job: Traditional designs make it difficult to optimize for certain activities because applications frequently share a common stack and database. The independent operation of each component in a microservices architecture, on the other hand, enables customized technology stack optimization for distinct services. Because of this flexibility, applications made out of smaller services may adjust to changing technologies more easily and at a lower cost.
	Precise Scaling: Microservices minimize infrastructure needs by enabling the independent deployment and scalability of individual services. This precision in scaling lowers infrastructure costs by scaling only the essential components rather than the complete application. 
	
5. List and discuss the similarities and differences of SOA and Microservices.
Similarities
- Both SOA and Microservices are approaches that focuses on building software systems by decomposing their functionalities into smaller components that are easier to manage. Both are reusable. Also, these two promotes service autonomy where it can operate independently.
Differences
- SOA typically focuses on creating larger, standardized services that can encompass multiple functionalities within an organization. It often involves a more centralized approach to service management and interoperability standards, aiming for broad integration across the enterprise. Conversely, Microservices emphasize fine-grained, single-purpose services deployed independently, with a strong focus on individual service autonomy, technology diversity, and agility within smaller, more specialized teams.
