# msvc-test
Directories:
 - DockerBuild: Contains the Dockerfile
 - Kubernetes: Contains the Kubernetes Deployment and Service .yaml scripts
 - test: The project from which the .jar can be compiled
 
 The docker images reside oin the public dockerhub repo https://hub.docker.com/r/staticblast/msvc-test/
 Versions: 
  - v1: No Liveness Check
  - v2: Implements Spring Boot Actuator for Liveness Check
  
When running, project displays a message accessible on http://localhost:8090/