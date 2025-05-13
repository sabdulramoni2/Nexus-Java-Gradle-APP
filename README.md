# Nexus- Artifact Repository Manager

## **Project Overview**
This project demonstrates building a java application using Gradle build tool and publishing the artifact to Nexus.
---

## **Features**
- Installed Java on the server followed by Nexus on server, created a new Linux User for Nexus and changed the permissions of Nexus executable and the Sonatype-work folder.
- Set Nexus configuration to run as a Nexus user and started Nexus with the Nexus User.
- Configured Firewall rules to open port 8081 to access the Nexus server from the web browser.
- Created new user on Nexus with permission to upload artifacts.
- Build a jar file with Gradle and upload it to Nexus.
- Build a jar file with Maven and upload it to Nexus.
- Queried the different types of Repositories.
- Queried the components of a repository.
- Queried the assets of a component.
- Created a new blob store.
- Created a new cleanup policy, attached to a repository, and executed task manually.

 
---

## **Prerequisites**
- **Sports API Key**: Sign up for a free account and subscription & obtain your API Key at serpapi.com
- **AWS Account**: Create an AWS Account & have basic understanding of ECS, API Gateway, Docker & Python
- **AWS CLI Installed and Configured**: Install & configure AWS CLI to programatically interact with AWS
- **Serpapi Library**: Install Serpapi library in local environment "pip install google-search-results"
- **Docker CLI and Desktop Installed**: To build & push container images
