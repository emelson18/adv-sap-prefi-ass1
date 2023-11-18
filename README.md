## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
	Service Oriented Architecture or SOA is a method of software development which uses Services to create business applications. Services is a software component that provides functionality or data exchange to their consumer. Services are basically the building blocks in a SOA.
 
2. List and discuss the characteristics of SOA.
	-SOA enables the exchange of data between services and also the use of the data that is sent through that exchange.
	-SOA helps in providing methods for service encapsulation which helps in making a cleaner and simpler look to an object. Sevice encapsulation is done by hiding the internal representation of an object.
	-SOA allows service discovery which is a process in which web service providers can be located and web services descriptions can be retrieved. This is done with the use of service registry which is a database that holds the relevant metatdata as well as the available and upcoming services available in an application.
	-SOA allows service composition which is the process of combining multiple small services to create a bigger and  more complex service with the purpose of providing a dunction for  bigger business requirement. This helps businesses in avoiding the need for developing an entire solution for a business need.
	-SOA provides loosely coupled services meaning services are working independently without relying to other services. This allows changes on a service to be applied without directly affecting other services since each service are working independently.
	- SOA provides ease of maintenance and reduced cost development and deployment. SOA is easy to maintain since its services are lossly coupled and changes on a service doesnt affect other service. Services can also be reused meaning lesser time for development which leads to lesser cost.
 
3. Define Microservices.
	Microservices is an architectural style of developing applications which allows large applications to be divided into smaller independednt parts where each parts has its own responsibilities or functions. 

4. List and discuss the benefits of using Microservices.
	- Failure Isolation is also observed in a microservices architecture. Microservices being divided into parts avoids the possibility of one service failure to affect the rest of the application.
	- Microservice is programming langunage and technology agnostic meaning it can be connected to any programming language and can also be run on any platform.
	- Microservice provides better data and security by storing data of services in each respective database instead of storing dadta in a single database that can be accessed as a whole by the application.
	- Services in a microservice architecture can be worked on by the developers for development and upgrade without thinking of coding conflicts simply because services are working independently of one another. This provides faster time to market for applications. 
	
5. List and discuss the similarities and differences of SOA and Microservices.
SIMILARITIES:
	SOA and Microservices are similar in terms of how they divided applications into smaller parts which serves for a single function of the application. This also leads to their ability of bbeing interopearble. SOA and Microservices both have their own communication protocols which allows the services to communicate and echange data with onw another. They are also both scalable because services can be changed without worrying about the other.

DIFFERENCES:
	Eventhough SOA and Microservices both divides application into smaller parts with the use of services, SOA uses larger services since it covers the whole enterprise compared to microservices that only covers application scope and uses small services focused on a single function. The services that SOA and microservices also differ with how they manage their data. Since SOA does use service composition, SOA services does have common data storage for multiple services unlike in microservice where one service have its own data management database. Failure of one service in SOA can also affect the other services specially services that are joined togteher through service composition unlike in microservices which makes sure that one service failure wont affect others because services works independently of one another.
