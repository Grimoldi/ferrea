# ferrea

Repo for the whole project. Building a library circuit SW with Kubernetes microservices and Neo4j DB Paas.

## Acknowledgments

Big kudos as font of inspiration for the design of the app have to go to Morgan Bruce and Paulo A. Pereira, authors of "Microservices in action".

## What is this?

When I graduated at Polimi (Politecnico of Milan) in CS, I did the final project by building a (monolithic) software for a decentralized library circuit.

The BE was made on Neo4J (a graph db engine) on a Django server.

Later on, I decided to build it has it should have been built, using microservices and implementing some functionality that was missing due to lack of time.

So, this is my temptative to build a microservices app, almost on scratch.

### How it is organized

Each microservice has its own repo, identified by "ferrea-\<microservice\>".

This repo will holds all microservices in one place by using the git submodule.
