How to guarantee that you can update data across the distributed architecture? 

BFF 
- backend from frontend API 
- focus point to communicate with the services 

API gateways
- Another approach to provide  a central contact point between clients and services 

Load Balancer 
- key component across microservices 

Stateless 
- Doesn't keep any information about previous call in the service
- doesn't keep the state of that call 

Service Register 
- Keep a list of available microservices 

Synchronous
 - Basically the caller wait for a response  
 - Can cause an issue called **temporal coupling 
 - Resiliency communication pattern can help 

Asynchronous 
 - Need to use a message broker
 - A downstream service doesn't keep the flow of the process 
 - Avoid having distributed transactions 