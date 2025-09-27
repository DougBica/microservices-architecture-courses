
- Each service needs to be tightly scoped in specific data 
- Identify  domains 
- If one can compete in performance, it can be split to another service 
- Frequency of change is another reason to split a services
- Improve resilience and availability
- Use third party API which is unreliable, you can create another service to handle this 
- Subdomain can be moved to another service, in this case, the service have more reasons to change 
- Don´t be afraid to create a microservice, and also don´t be afraid to merge to services if needed 


## Identify bounded contexts 

- Collaborative approach to found core concepts of the software and co-concepts 
- Core concept and co-concepts makes the bounded context
- It is the starting point to create a service 
## Event Storming 

## An existing monolith service ?

- Identify in the code base the domains of each service 
- Create clean boundaries between de domains of each services 
- **Strangler Application Pattern

Be possible to rewrite the service if it´s needed.
