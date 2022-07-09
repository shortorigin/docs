# Docker Swarm Notes

## Section 1

Connecting the computers

docker swarm join --token SWMTKN-1-2p0httixf6db62f28tk0espz4itm296afagqloll1rkns39pif-723ritvo02w9hsa3c6lcjrks8 {overlayAddress}:2377

## Docker Swarm Notes
### Features of Docker Swarm
1. Decentralized Access
2. High Security
3. Auto Load Balancing
4. High Scalability
5. Roll-Back Environment To A Previous State (Safer Environment, If Needed)
   
### Containers & Services
- In Swarm, containers are launched using rest services.
   - Services are a collection of containers of the same image that are launched together.
  
### Requirements for Docker Swarm
- Manager Node and Client/Worker Node are needed to deploy a service in docker swarm.
  - Manager node maintains cluster management tasks (Like a server)
    - Can see the status of all the worker nodes in a cluster!
  - Worker node receives and excecutes tasks from the manager node. (Like a client)
    - If manager tells worker to run as a mySQL environment, the worker will convert to a mySQL environment.

# Communication between Manager and Worker Nodes are done by using a REST API

