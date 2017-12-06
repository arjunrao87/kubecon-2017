# Distributed Tracing - Jaeger

- Metrics and logs dont give you a holistic view. Tracing does. 
- Highly contextual information associated with a specific transaction 
- Distributed context propagation ( A controller passes context to all the services that might need it because then you can associate metrics etc with services( lets say for Service B ) that have no idea about other services like Service B
- https://medium.com/opentracing/take-opentracing-for-a-hotrod-ride-f6e3141f7941
- Instrument frequently used frameworks
- Use OpenTracing http://opentracing.io/
- Enable tracing by default 
- Use OpenTracing "Baggage" to identify synthetic traffic 
- Uber uses Developer Studio to simulate scenarios for finding trace results 
- Tracing helps in Service Dependency Analysis to find out how services/microservices are connected to each other and to help with scaling  