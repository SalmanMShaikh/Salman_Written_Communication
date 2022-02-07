***
# GraphQL Architecture
<br>
GraphQL is a query language for APIs, we can get exactly what we need from the API. GraphQL can be used with any available protocol and also we can use any database with GraphQL maybe SQL or NoSQL

<br>
GraphQL is designed to make APIs fast. It is a good alternative for REST. GraphQL can pull data from multiple data sources in a single API call. It has strongly defined data types that reduce the miscommunication between the client and server

<br>
There are three different kinds of architecture

<br>

1. GraphQL server with a connected database

2. GraphQL server that integrates existing systems

3. Hybrid Approach

<br>

---
<br/>
<br/>
<br/>

### 1. GraphQL server with a connected database
<br>

In this architecture we have a single server that is connected to the database when the query is performed on the GraphQL server, the server reads the query and understands what kind of data the client wants, fetches the required data from the connected database, and returns to the client. This process is called resolving query

<br>
The desktop/mobile connects with the GraphQL server over HTTP then the server checks the request and returns the data from the database to the desktop/mobile. Basically in this architecture, we have a simple GraphQL server setup, which directly accesses the database and  returns required data.

<br>
This architecture can be used for fresh development, when we set up the system and we decide to have GraphQL based access we can use this.

<br>

- It is used for simple and new projects

- It uses a single server

- It resolves the query and fetches data only from the connected database

<br/>
<br/>
<br>

### 2. GraphQL server integrating the existing systems

<br>
This architecture is not for fresh development, when we will have to support the existing system or we have some existing data we can use this architecture as we are integrating the GraphQL server into it.

<br>

In this architecture, we can connect multiple existing systems with a single GraphQL server. When the client communicates with the GraphQL server, the server reads the payload and returns the required data from existing systems to the client. GraphQL acts as an interface between the client and the existing systems. For getting the data from existing systems GraphQL connects to actual backend services and provides required data.

<br>

- GraphQL is merged with existing systems and it acts as an interface between the client and existing systems.

- The graphQL server will fetch the data from multiple existing databases

-  It is used for complicated projects which have many different APIs

<br/>
<br/>
<br>

### 3. Hybrid Approach
<br>
It combines both the above-mentioned architectures. It is having a connected database and is also integrated with some existing systems.

<br>
When a query is received by the server, it will resolve it either by using existing systems or a connected database (it can fetch data from the single database as well as existing systems) and provide the required data.

<br>

- It is connected with a database and also with existing systems 

- It fetches the data either from existing systems or connected database
<br/>
<br/>
<br>

***
### References
<br>

https://graphql.org/

https://www.howtographql.com/basics/3-big-picture/

https://www.javatpoint.com/graphql-architecture

https://www.tutorialandexample.com/architecture-of-graphql/

https://kamalmeet.com/graphql/graphql-architecture/

https://www.redhat.com/en/topics/api/what-is-graphql

***