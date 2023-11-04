# AWS Amplify, Part 2


  1. **What makes an API RESTful?**
     A RESTful API that adheres to these constraints is designed to be simple, scalable, and easy to understand. 
     It follows a client-server model, uses standard and consistent interactions, and leverages the HTTP protocol
     to access and manipulate resources. REST is widely used for building web services and APIs due to its simplicity 
     and compatibility with HTTP.
  2. **What is the benefit of using GraphQL? Any downsides?**

     - **Benefits of Using GraphQL:**
       1. **Efficiency:** GraphQL allows clients to request exactly the data they need, and no more. This eliminates 
          over-fetching or under-fetching of data, resulting in more efficient data retrieval.
       2. **Flexibility:** Clients have the power to define the shape and structure of the data they want. 
          This flexibility simplifies the client-server interaction and can reduce the number of API requests.
       3. **Reduced Versioning:** Unlike REST, where changes in the API often require versioning, GraphQL avoids this 
          problem by allowing clients to request only the fields they need. This means you can add new fields to your 
          types without breaking existing clients.
       4. **Single Endpoint:** It typically uses a single endpoint, simplifying the client setup and making it easier 
          to manage and optimize requests. This contrasts with REST, which often involves multiple endpoints.
       
     - **Downsides of Using GraphQL:**
       1. **Learning Curve:** Learning GraphQL and its query language can take some time for both front-end and 
          back-end developers who are new to it. It introduces a new way of thinking about data retrieval and management.
       2. **Over- or Under-Fetching:** While GraphQL allows clients to specify their data needs, it's possible for 
          clients to request too much or too little data, leading to performance issues. This requires careful query design.
       3. **Complexity:** GraphQL APIs can become complex as the schema grows, and handling complex business logic or 
          authorization can be challenging. This complexity may affect the development and maintenance of the API.
       4. **Security:** Properly securing a GraphQL API can be more complex than securing a REST API. Fine-grained
          control over what data clients can access and more complex authorization logic is often required.
       5. **Tooling:** While GraphQL has a growing ecosystem of tools and libraries, it may not have as mature and 
          extensive tooling as REST. For example, not all web frameworks and libraries offer native support for GraphQL.
       6. **Performance and Efficiency:** While GraphQL allows for efficient data retrieval, it can also introduce 
          performance issues if queries are not optimized. Inefficient or nested queries can lead to performance 
          bottlenecks.

  3. **Describe “serverless” to a new 301 Code Fellows student.**
     "Serverless" is a cloud computing model approach that allows developers to focus on writing code for specific 
     functions or services without the need to manage servers. that simplifies application deployment and management
     by letting the cloud provider take care of server provisioning and allocation dynamically. 
     It's like renting computing power on-demand, where you only pay for what you use.

## Things I want to know more about
- To gain a deeper understanding of REST and GraphQL, I will consider diving deeper into the following areas:

For REST: HTTP, Response Formats, Authentication and Authorization.
For GraphQL: Schema Design, Optimizing Queries, Security and Authentication. 