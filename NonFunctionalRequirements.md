The qualities and constraints (the NFRs) that we impose on the IT system:
* Runtime qualities
* Non-runtime qualities
* Business constraints
* Technology constraints

Categories of NFRs.
* Availability – What percentage of time does the cloud vendor guarantee cloud services will be available (including scheduled maintenance down-times)? Bear in mind that although 99% availability may sound good that actually equates to just over 3.5 days potential downtime a year. Even 99.99 could mean 8 hours down time. Also consider as part of this Disaster Recovery aspects of availability and if more then one physical data centre is used where do they reside? The latter is especially true where data residency is an issue if your data needs to reside on-shore for legal or regulatory reasons.
* Elasticity (Scalability) – How easy is it to bring on line or take down compute resources (CPU, memory, network) as workload increases or decreases?
* Interoperability – If using services from multiple cloud providers how easy is it to move workloads between cloud providers? (Hint: open standards help here). Also what about if you want to migrate from one cloud provider to another ? (Hint: open standards help here as well).
* Security – What security levels and standards are in place? for public/private clouds not in your data centre also consider physical security of the cloud providers data centres as well as networks. Data residency again needs to be considered as part of this.
* Adaptability – How easy is it to extend, add to or grow services as business needs change? For example if I want to change my business processes or connect to new back end or external API’s how easy would it be to do that?
* Performance – How well suited is my cloud infrastructure to supporting the workloads that will be deployed onto it, particularly as workloads grow?
* Usability – This will be different depending on who the client is (i.e. business users, developers/architects or IT operations). In all cases however you need to consider ease of use of the software and how well designed interfaces are etc. IT is no longer hidden inside your own company, instead your systems of engagement are out there for all the world to see. Effective design of those systems is more important than ever before.
* Maintainability – More from an IT operations and developer point of view.  How easy is it to manage (and develop) the cloud services?
* Integration – In a world of hybrid cloud where some workloads and data need to remain in your own data centre (usually systems of record) whilst others need to be deployed in public or private clouds (usually systems of engagement) how those two clouds integrate is crucial.
* Disaster Recovery - Do we have mutiple hot data centers?  Do we have hot-warm with RPO and RTO? How do we move compute, network and data? Do we do continuous backups? 
