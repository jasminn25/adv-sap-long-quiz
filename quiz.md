## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- In my understanding, Service Oriented Architecture is a software development that is focused on reusable services. And these reusable services are used to make new applications and by using SOA or Service Oriented Architecture, the services can communicate or work well together across different platforms. For example, a developer is planning to create an application that will be use to cater users that orders food, or a food delivery service perhaps, like foodpanda. instead of creating its own login service, map service, or payment, the developer can reuse the API of google map service, implement the payment service of Paypal, and log in their account from facebook or gmail.

2. List and discuss the characteristics of SOA.
- There are many characteristics of SOA according to our handout, and we will start with Standardized Service Contract. This is to ensure to achieve reusability potential of services. Next is Loose Coupling, which avoids crash if ever there are parts of services that break. This makes the services independent from each other. Third is Abstraction, this talks about encapsulation, keeping users or the outside world from seeing the logic. Fourth is Service Reusability, which is of course its intent to maximize reusability by dividing the logics in applications into services. Next, Autonomy, from the word autonomy, meaning freedom or independency, is about having control or ability to carry out the logic independently. Sixth is Statelessness, from what I understand, this is to promote and maximize scalability and also reusability by services minimizing its operations or information that they handle. Next is Service Discoverability, which is the storing of metadata or data in what they call service registry or profile documents. Eighth is the Composability, it involves breaking large problems into tiny or smaller problems. Last is Service Interoperability, which enables the operation of various distributed web services across a range of hardware architectures and software platforms.

3. Define Microservices.
- Microservices in my own understanding, are loosely coupled and reusable components. For example, we have web, mobile and pc who are loosely coupled. Each of them has their own function, for example shopping cart, billing and user profile. These are microservices. Microservices architectures are composed of these many loosely coupled and independent smaller services.

4. List and discuss the benefits of using Microservices.
- First, Independently deployable. Since their services are smaller and independently deployable, there is a benefit in speed, which is they do not take huge amounts of time, the developer's team can understand easier the code and contribute it faster. Next, Right Tool for the job, instead of using the same stack, data model, or database, in microservices it is possible for every services stack to be optimized for that service. Also, another benefit is precise scaling. Since they enable precise scaling of only the components that need it, they enable less infrastructure than monolithic applications.

5. List and discuss the similarities and differences of SOA and Microservices.
- According to what I've read, SOA or Service- Oriented Architecture is enterprise-wide and as what is mentioned earlier, it is reusable. Meanwhile, microservices architecture has an application scope. The SOA architectural style evolved into microservices architecture. Each microservice is a considerably smaller software component that focuses on a specific task, whereas each SOA service is a whole business capability. 

6. Define Web Services.
- Based on my understanding, web services are, from the term itself, services or softwares that are made available over the internet for the sole purpose of exhanging data. It is often used for common tasks by companies or businesses, such as for example, registering or signing in to a website using their google or facebook credentials, or making payments using Paypal. A web service, according to what I have researched, is a "software system that supports interoperable machine-to-machine interaction over a network." And that's why web services can be independently used on the implemented software platform, so it is not tied to one operating system or language.

7. List and discuss the benefits of using Web Services.
- One benefits of web services according to handout is:

A. Exposing the existing function on the network. Once the existing function is exposed, the function of your program can now be used by other applications.

B. Interoperability. From the term itself, the meaning of interoperability is the ability of computer systems to exhange and make use of information. And web services, they allow communications between applications and share services or data between them.

C. Standardized Protocol. Of course one must follow rules when it comes to transmitting and exchanging data. Web services uses Service Transport, XML Messaging, Service Description, and Service Discovery Layers.

D. Low Cost of Communication. It is said that web services is using SOAP over HTTP protocol. In that way, others can use their existing low-cost internet when they want to implement web services.

8. List and discuss the characteristics of Web Services.
- web services has the following characteristics based on the handout:

A. XML- Based. They use XML which makes them allow applications to exchange and make use of data in a way that it is understood universally by all. That is why web services interoperability is high. 

B. Loosely coupled. It is actually also a benefit that since web services are loosely coupled, they are independent and can reduce the risk of unwanted changes when there is a change made in one part/component. 

C. Coarse-Grained. It says that the business/ interfaces that they expose should be coarse-grained which means that the components are larger.

D. Ability to be Synchronous or Asynchronous. Which means that their clients can retrieve results later point in time and as soon as the service is completed.

E. Supports remote procedure calls (RPCs). Providing a service of its own that are comparable to those of traditional component.

F. Supports Document Exchange. Since they use XML, they of course support exchange of data or documents to handle business integration.

9. List and discuss the distinct roles in Web Services Architecture.
- the following are the distinct roles:

A. Provider. Creates and provides the web service on the internet on to the client.

B. Requestor. Is the provider is the one who provides the web service, the requestor is the consumer of the web service.

C. Broker (service registry). Location/storage or a centralized place of new services or existing ones.

10. List and discuss the Web Services Components.
- There are 3 web services components according to our handout:

A. Soap. Which stands for Simple Access Object Protocol and it is an XML-based protocol for exchanging information between computers.

B. WSDL. It stands for web services description language which is also an XML-based language but for describing web services and how to utilize them.

C. UDDI. Stands for universal description, discovery, and integration. Now, this is also of course an XML-based for describing, publishing, and finding web services.
