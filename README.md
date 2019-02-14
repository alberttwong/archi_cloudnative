# archi_cloudnative
Cloud Native Architectural Models using Archi. Contains models for CAAS, Cloud Native Applications, 12/15 Factor Applications with CI/CD/CS, monitoring and log management. Infrastructure components include Red Hat OpenShift, Red Hat Storage, Red Hat Cloudforms, Red Hat JBoss Java Web Server, Red Hat JBoss Enterprise Application Server, Red Hat JBoss Business Rules Management, Red Hat JBoss Data Grid, Red Hat JBoss Data Virtualization and Red Hat Ansible.  Includes material and architectural thinking from the following books, papers and articles.

### Architecture
* https://www.openshift.com/promotions/for-developers.html
* https://www.openshift.com/promotions/devops-with-openshift.html
* https://developers.redhat.com/promotions/microservices-for-java-developers/
* https://developers.redhat.com/promotions/distributed-javaee-architecture/
* https://www.openshift.com/promotions/docker-security.html
* https://content.pivotal.io/ebooks/migrating-to-cloud-native-application-architectures
* https://content.pivotal.io/ebooks/beyond-the-12-factor-app
* https://thenewkingmakers.com
* https://insights.sei.cmu.edu/devops/2015/04/devops-case-study-netflix-and-the-chaos-monkey.html

### Continuous Integration and Continuous deployment (CI/CD) and DevSecOps
* From the Red Hat reference architecture team (https://access.redhat.com/documentation/en-us/reference_architectures/2017/html-single/application_cicd_on_openshift_container_platform_with_jenkins/index)
* From the Red Hat Innovation Labs (https://github.com/rht-labs/labs-ci-cd, https://github.com/redhat-cop/container-pipelines)
* Department of Homeland Security DevSecOps using OpenShift (from Lucy Kerner)
* Doing it raw with the Jenkins Client Plugin for OpenShift (all the above extends this plugin - https://github.com/openshift/jenkins-client-plugin)
* Booz Allen (https://github.com/boozallen/jenkins-templating-engine)
* Blue Ocean (from cloudbees themselves)

## Sample Diagrams
### System Context
![System Context Cloud Native Application](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/System%20Context:%20Cloud%20Native%20Applications.png)

![System Context Cloud Native Application Patterns](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/System%20Context:%20Cloud%20Native%20Application%20Patterns.png)

### Component Model:
![Component Model: Cloud Native Applications](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Component%20Model:%20Cloud%20Native%20Applications.png)

![Component Model: Cloud Native Applications Layers](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Component%20Model:%20Cloud%20Native%20Applications%20Layers%20with%20Mobile%2C%20Workflow%2C%20Rules.png)

### Component Model: Cloud Native Software Stack
![Component Model: Cloud Native Applications Software Stack](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Component%20Model:%20Cloud%20Native%20Applications%20Software.png)

### Component Model: Cloud Native Data
![Component Model: Cloud Native Applications Data Centric](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Component%20Model:%20Cloud%20Native%20Applications%20Data%20Centric.png)

### Operational Model: Red Hat OpenShift On-Premise Reference Architecture
![Operational Model: OpenShift with RH Storage on Bare Metal](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Operational%20Model:%20Data%20Center%20View%20On-Prem%20Reference%20Architecture%20(OCP%2C%20CF%2C%20CNS).png)

### Operational Model: Red Hat OpenShift on AWS Reference Architecture
![Operational Model: OpenShift with AWS Storage on AWS](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Operational%20Model:%20Data%20Center%20View%20AWS%20Reference%20Architecture.png)
![Operational Model: OpenShift with Red Hat Storage on AWS](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Operational%20Model:%20Data%20Center%20View%20AWS%20Reference%20Architecture%20(OCP%2C%20CF%2C%20CNS).png)

### Operational Model: Cloud Native on AWS Reference Architecture
![Operational Model Detail: Cloud Natve on AWS](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Operational%20Model:%20Data%20Center%20View%20Detail.png)

### DevSecOps with CI/CD using Jekins and OpenShift
![DevSecOps with CI/CD using Jekins and OpenShift](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Continuous%20Integration%20and%20Continuous%20Deployment%20(DevSecOps)%20Detail%20on%20OpenShift%20with%20Jenkins.png)

### What is Archi
The Archi® modelling tool is targeted toward all levels of Enterprise Architects and Modellers. It provides a low cost to entry solution to users who may be making their first steps in the ArchiMate modelling language, or who are looking for a free, cross-platform ArchiMate modelling tool for their company or institution and wish to engage with the language within a TOGAF® or other Enterprise Architecture framework.

## What is Red Hat OpenShift
Red Hat OpenShift is a container-as-a-platform made by Red Hat.   It's an enterprise version of Kubernetes, Docker, Jenkins, monitoring, log aggregation, self service dashboard and more all rolled into one single product. 

## How to load and extend this model 
Run Archi and install the collaboration plugin.  You can get the collabration git plugin at https://github.com/archi-contribs/archi-modelrepository-plugin.   Just click on "import remote model to workspace", supply this git project URL, git username and password.  That should be it.
