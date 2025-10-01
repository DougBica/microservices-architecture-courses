
- Distributed transaction  
- Avoid physical distributed transaction using synchronous communication (temporal coupling)
- Message broker, asynchronous communication creates a logical transaction 

### if something goes wrong ?

- Part successful transaction 
- Transaction manager used to be useful on this cases 
- If some services couldn't process the message, it sends a message to manager and it is going to start a failure compensation process, by sending messages to the other services to undo what their have done.


## Saga pattern
