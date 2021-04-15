# API Gateway

Gabriella Kim and Kevin Lynch

The API gateway layer is an entrance to an environment that implements microservices. When the Gateway receives a request, it is able to map them to the appropriate service or services. Gate ways can also implement handling of throttling/rate limiting and help to propagate authorization/session across the network. Gateways are often used in conjunction with load balancers and other components to achieve this functionality. Additionally, the gateway ensures that there is loose coupling between routing logic and a services implementation logic. The Gartner report mentions that when building/implementing a microservice architecture that there are typically one-to-many relationship between the published API as well as the set of microservices that implement the API functionality. Typically, an outer API exposes multiple functions and each function maps to a separate microservice.
The reports goes into how the API gateways enforce different policies which include the following:
- Security that is relating to authentication, authorization, encryption of content, validation, and verification, as well as others.
- Traffic management which consists of requesting routing, load balancing and throttling
- Monitoring which includes observing and analyzing system health
- Lastly, transformation which relates to versioning, multi-experience support and semantic reconciliation(The ability to recognize two objects are the same when being described differently) 
Some prominent API gateways include Google Apigee, Oracle API Gateway, Kong and Tyk. All in all, API gateways can be summarized as a centralized access point(s).
