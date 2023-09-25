## What is CI/CD?

CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of app development. 
The main concepts attributed to CI/CD are continuous integration, continuous delivery, and continuous deployment. 
CI/CD is a solution to the problems integrating new code can cause for development and operations teams (AKA "integration hell").

## What is Jenkins? 

Jenkins is a self-contained, open source automation server which can be used to automate all sorts of tasks related to building, testing, and delivering or deploying software.

Jenkins can be installed through native system packages, Docker, or even run standalone by any machine with a Java Runtime Environment (JRE) installed.

## Installing Jenkins : 

### 1. Windows : 
- Use the installer from:  
    `https://www.jenkins.io/download/#downloading-jenkins`


### 2. Jenkins Features : 

- Automatic Job definition : jenkins can automatically create, update or delete jobs based on repositories it identifies.
- Organization folder : jenkins can build jobs with repositories in an organization folder like github organizations, bucket teams or gitlabs group.
- Multibranch pipelines : Jenkins can build jobs with multibranch pipelines.  
    `Note : Jenkins Pipeline (or simply "Pipeline" with a capital "P") is a suite of plugins which supports implementing and integrating continuous delivery pipelines into Jenkins. [reference : https://www.jenkins.io/doc/book/pipeline/]`

### 3. Running Jobs : 

- By default jenkins runs jobs on built-in node. 
- To use a different not we can use following :  
    `Manage Jenkins » Nodes and Clouds`
- We can set built-in executor to 0 to prevent jenkins from running on built-in node.
- We can also setup agents here.
- We need to have atleast one agent to run builds.

`The Jenkins controller and agents can be thought of as a distributed process which executes across multiple discrete processes and machines.`  


