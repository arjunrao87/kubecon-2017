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
