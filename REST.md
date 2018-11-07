### RESTful systems

- [Reference article]( https://codewords.recurse.com/issues/five/what-restful-actually-means)
- Representational state transfer 
  - Set of design principles for making systems scalable, flexible, and modular 
  - Roy T. Fielding's 2000 dissertation 
- Fielding constraints: 
  - Client-server 
    - a.k.a. one-to-one 
    - alt: event-based integration architecture (broadcasting and eavesdropping)
  - Stateless 
    - Clients and servers agnostic of each other's state 
    - Server keeps no record of past requests 
    - Each request treated as standalone 
  - Uniform interface 
    1. Identification of resources 
    2. Manipulation of resources by representations 
    3. Self-descriptive messages 
    4. Hypermedia 
  - Caching 
  - Layered systems 
  - Code on demand (e.g. scripts)