# Keynote - Brendan Burns 

What can we do to make distributed systems more intuitive and easy to develop

# First principles for Distributed Systems 

1. Have everything in one place
- topology of application 
- where images reside 
- where configuration resides ( eg. changing ports needs to be done in code, dockerfile and k8s yaml today )
- single source of truth to understand the state of our application 

2. Build libraries not platforms
- Have opt-ins and not lock-ins 

3. Encourage sharing and re-use 


# Solutions

## Language Idiomatic Cloud 

1. Design your appliction in code 
- not configuration. No more DSLs, YAML files 

2. More approachable 

3. Better tooling 
- Unit tests
- Code reviews
- Autodocs
- Style guides

4. Thoughtful langauge features
- Turing completeness
- Abstraction
- Inheritance

- Cloud native will move from assembly language features of kubernetes to langauge native cloud keywords. Like @synchronized became a keyword for Java
- This will help democratize distributed Systems like PyWren did for python 

- Standard Cloud Native library - Metaparticle - https://github.com/brendandburns/metaparticle


