Project description: 

This project stablishes a Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins, Git, Maven, and Docker.

Outcome of this project:

This project aims to automate the deployment of an application.
The final application is hosted in a docker container and can be accessed by the users through their browsers.

Tools used:

1. Jenkins
   
   Automates the build, test, and deployment processes.
   
   Configured with a pipeline that pulls code from Git, builds it with Maven, and deploys using Docker.

2. Git

   Source code management and version control.
   
   Code is stored in a Git repository, which Jenkins accesses to trigger builds.

3. Maven

   Used for building and packaging the application.

   Integrated with Jenkins to compile and prepare the application for deployment.

4. Docker

   Containerization of the application.

   Docker images are built, pushed to DockerHub, and deployed as containers.
   

   
The pipeline automates the process from code integration to deployment, ensuring fast, reliable and consistent delivery of the application.


PROJECT ARCHITECTURE: 

<img width="874" alt="Screenshot 2024-08-31 at 8 35 12 PM" src="https://github.com/user-attachments/assets/db3728f4-3992-4611-97ce-9c3b3754f729">

