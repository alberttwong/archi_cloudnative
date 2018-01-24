# archi_cloudnative
Cloud Native Architectural Models using Archi. Contains models for CAAS, Cloud Native Applications, 12/15 Factor Applications with CI/CD/CS, monitoring and log management. Infrastructure components include Red Hat OpenShift, Red Hat Storage, Red Hat Cloudforms, Red Hat JBoss Middleware and Red Hat Ansible.  Includes material and architectural thinking from the following books.

* https://www.openshift.com/promotions/for-developers.html
* https://www.openshift.com/promotions/devops-with-openshift.html
* https://developers.redhat.com/promotions/microservices-for-java-developers/
* https://developers.redhat.com/promotions/distributed-javaee-architecture/
* https://www.openshift.com/promotions/docker-security.html
* https://content.pivotal.io/ebooks/migrating-to-cloud-native-application-architectures
* https://content.pivotal.io/ebooks/beyond-the-12-factor-app
* https://thenewkingmakers.com

## Sample Diagrams
### System Context
![System Context Cloud Native Application](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/System%20Context:%20Cloud%20Native%20Applications.png)

![System Context Cloud Native Application Patterns](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/System%20Context:%20Cloud%20Native%20Application%20Patterns.png)

### Component Model:
![Component Model: Cloud Native Applications]
(https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Component%20Model:%20Cloud%20Native%20Applications.png)

![Component Model: Cloud Native Applications Layers](https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Component%20Model:%20Cloud%20Native%20Applications%20Layers%20with%20Mobile%2C%20Workflow%2C%20Rules.png)

![Component Model: Cloud Native Applications Data Centric]
(https://github.com/alberttwong/archi_cloudnative/blob/master/images_docs/Component%20Model:%20Cloud%20Native%20Applications%20Data%20Centric.png)

### Operational Model: Red Hat OpenShift on AWS Reference Architecture
![Operational Model: OpenShift on AWS](https://github.com/alberttwong/archi_openshift/blob/master/images_docs/Operational%20Model:%20Data%20Center%20View.png)

![Operational Model Detail: OpenShift on AWS](https://github.com/alberttwong/archi_openshift/blob/master/images_docs/Operational%20Model:%20Data%20Center%20View%20Detail.png)

### What is Archi
The Archi® modelling tool is targeted toward all levels of Enterprise Architects and Modellers. It provides a low cost to entry solution to users who may be making their first steps in the ArchiMate modelling language, or who are looking for a free, cross-platform ArchiMate modelling tool for their company or institution and wish to engage with the language within a TOGAF® or other Enterprise Architecture framework.

## What is Red Hat OpenShift
Red Hat OpenShift is a container-as-a-platform made by Red Hat.   It's an enterprise version of Kubernetes, Docker, Jenkins, monitoring, log aggregation, self service dashboard and more all rolled into one single product. 

## How to load and extend this model 
Run Archi and install the collaboration plugin.  You can get the collabration git plugin at https://github.com/archi-contribs/archi-modelrepository-plugin.   Just click on "import remote model to workspace", supply this git project URL, git username and password.  That should be it.
