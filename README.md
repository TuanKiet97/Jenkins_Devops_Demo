# Jenkins_Upgradev3

# Need to understand about the Docker and Jenkins:
## Docker and Kernel
- What's a Kernel ?
  - NT kernel for windows
  - Debian kernel for linux
  - what is difference between VM and Container ?
- The Docker filesystem
- Running the Jenkins in a container
- Understanding copy in write on image and container layers
- Wrapping up Jenkins state
## Creating a Jenkins Build Farm with Docker 
- Provisioning Containerized Agents (Cloud agents)
- Build Dotnet Application with Dockerfile
- Wrapping up Dotnet agent
- Consider meta build
- Understanding Container connect method between master and agents
  - Attach container
  - Through the JNLP connection
  - Using the ssh protocol
- Working the private registries
- More specific Jenkins images
## Working with Multi-architecture containers in Jenkins
- Understanding multi-architecture: docker image inspect --format '{{Os}}/{{.Architecture}}' jenkins/jenkins:lts
