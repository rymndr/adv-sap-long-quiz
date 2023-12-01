## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).

Service Oriented Architecture (SOA) this talk about on how software's architecture and its role is to orgnazie the software's components in order to provide a good services. And those services have their own ability to use in other softwares in short the softwares can be reusable for other functions.

2. List and discuss the characteristics of SOA.

SOA.
 • Reusability
SOA services are designed to be reusable, making development more efficient and allowing services to be utilized in various business processes.

• Discoverability
SOA facilitates the discovery of services through the use of directories, enabling developers to easily locate and incorporate these services into their own organizational applications.

• Composability
SOA enables businesses process by arranging existing services that can be helpful for creating flexible adaptive systems.

• Interoperability
SOA highlights the use of standardized communication protocols that enables services to interact smoothly across the many different platforms.

3. Define Microservices.

Microservices is a small, independent component that is desgined to perform a specific business function or process. In microservices application it was divided into a collection of self-contained services and each of those is represents a distinct defined piece of functionality. Microservices architecture makes application easier and faster to develop.

4. List and discuss the benefits of using Microservices.

• Ease of Deployment
Microservices architecture facilitates continuous integration and deployment practices, enabling smooth and frequent updates without impacting the entire system.
• Team Autonomy

Since micro services align with smaller, cross-functionalMicro service empowers teams to work autonomously.
• Enhanced Maintainability

Microservices architecture promotes easier maintenance tasks by enabling developers to focus on individual services without affecting the entire application. This modular approach facilitates simpler updates, bug fixes, and new feature implementation.

5. List and discuss the similarities and differences of SOA and Microservices.

Similarities of SOA and Microservices Flexibility
Both architecture promote flexibility making application into smaller and manageable components.
Quick development, testing and deployment.
• Scalability
Both architecture allows individuals services to developed of one another.
• Interoperability
SOA and Microservices allows different services to work together smoothly without any problem.


Difference of SOA and Microservices
• Development Speed Microservices - Faster development, delivery since team can work indepdently on focused device.
 SOA - Longer development cycle since SOA is influenced by complexity of the services.
• Adaptability to Change Microservices - designed to be more adaptable to change since each service can evolve indepdently without affecting the entire system.
 SOA - when chaning in SOA it requires centralized coordination that can lead to slow adaptation to change especially when migrating to larger systems.

6. Define Web Services.

The web service is a software application or component that communicates and interacts with other software applications or systems over the internet. Web services typically employ open standards such as HTTP (Hypertext Transfer Protocol), XML (eXtensible Markup Language), and SOAP (Simple Object Access Protocol) for communication. They facilitate a standardized platform for exchanging data from different applications, making them a fundamental component of modern computing technology.

7. List and discuss the benefits of using Web Services.

Web Services.
Easy Maintenance: Web services are modular, making updates and maintenance tasks easier to perform because the service doesn't need to be updated in every client application.

• Cost-Efficiency: Development costs are reduced because developers can save a lot of time and resources by avoiding the need to build functionality from scratch. This leads to cost savings in terms of development requirements.

• Reusability: Web services are designed as modular components, making them easier to reuse in different contexts. This reusability can lead to more efficient development and reduced redundancy.

8. List and discuss the characteristics of Web Services.

• XML-Based: Web services utilize XML for data representation. XML offers a flexible and extensible approach to data structuring, making it adaptable to various information types. This ensures consistent data structuring and transmission across different systems.

• Business Integration: XML excels in facilitating business integrations. A compelling example is business-to-business (B2B) communication, where organizations exchange complex documents. XML provides a standardized and extensible means of representing information for seamless collaboration.


9. List and discuss the distinct roles in Web Services Architecture.

• Provider: they are responsible for creating and hostiitng the web services. Their task is developing the web service, deploying the web serivce, and making the web services available for clients.

• Requestor: referred to client application, is any software applications needs to use the functionality provided by a web services. This could be an apllication developed by .NET, Java, etc.

• Broker: acts as intermediary that facilitates the discovery of web services. This provides mechanism for requestors to find available web service.

• Publish: their task is registering web services with the borker. they also ensures the information is accessible to potential clients

• Find: This involves querying the registry based on certain criteria. their task is selecting web services that matches it suitable requirements and also they also search the services registry for suitable web services.

• Bind: This involves creating the necessary communication link and sending requests to the identified web service's endpoints

• Task: Handles the responses received from the web service.
      Establishing a connection to the web service


10. List and discuss the Web Services Components.

• UDDI:

A protocol and platform framework for discovering and integrating web services.
Plays an important role in web service discovery by providing a standardized way for service providers to publish information.

• SOAP:

Utilizes XML as its message format.
Allows for the standardized structuring of data within messages.
Serves as a communication protocol that enables the exchange of structured information between services.