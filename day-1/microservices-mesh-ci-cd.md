# Microsoft Service Mesh/CI-CD 

- Canary testing ( 90-10 testing with production traffic )
- Advanced routing to do canary testing at any layer of the mesh of microservices 
- Observability and tracing is needed to monitor the canary test 
- have chaos testing in your testing model
- Use Istio and envoy to do this advanced routing and canary testing  
- Use initializers to init envoy into every pod of a particular namespace ( this is in newer k8s releases )
- Brigade is an event driven scripting language for K8s. You can build CI CD for k8s using brigade functions - https://brigade.sh/
- Opening a PR kicks off a CI/CD process part of which is sending a slack message 
- https://medium.com/@chzbrgr71/kubecon-2017-demo-istio-and-brigade-ci-cd-9db5ef15a942