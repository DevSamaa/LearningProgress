# Acceleration Plan for Protégés in the Future Makers Academy - Quorum 2
​
This is a working document which we can use to plot a protégé's progress as they work their way through the Protégé Acceleration program. The aim is to prepare for the Second Quorum review. This is a **guide** and should be used as a reference to help the protégé to focus learning and track their progress. Please note that this checklist is what is considered the minimum knowledge and experience which the protégé should have. Protégés are encouraged to dive deeper into the subjects to enhance their learning.

You should refer to the Acceleration page of the Protégé's handbook for further details: https://myobconfluence.atlassian.net/wiki/spaces/FMA/pages/1022724705/Acceleration
​
## Frameworkless Web Application & CI/CD Deployment Pipelines

The Frameworkless Web Application & CI/CD Deployment Pipelines part of Acceleration program includes these topics:

* [AWS Basics](../things-we-value/technical/operations/aws-basics.md)
* [Basics of HTTP](../things-we-value/technical/web/HTTP.md)
* [Basics of REST](../things-we-value/technical/web/REST.md)
* [Containerization](../things-we-value/technical/operations/containerization.md)
* [Continuous Integration and Delivery](../things-we-value/technical/continuous-integration-and-delivery)
* [Managing Secrets](../things-we-value/technical/security/managing-secrets.md)

### AWS Basics
​
The protégé will have demonstrated an understanding of the following concepts and used them while completing exercises and katas:
​
- [x] Has an understanding of what AWS accounts are and can identify which accounts to use
- [x] Has used the AWS web console to view and create AWS resources
- [x] Has created a simple website using Elastic Compute Cloud (EC2) and Route53 for DNS
- [ ] Can describe what Virtual Private Cloud (VPC) is and why it is important
- [ ] Can describe what CloudFormation is and why it is useful

### Basics of HTTP

The protégé will have demonstrated an understanding of the following concepts:

- [x] Can describe the elements of an HTTP request
- [x] Can describe the elements of an HTTP response
- [x] Can describe what happens in an HTTP request and response flow
- [x] Can describe how to serve different types of content
- [x] Has used `curl` and a Browser Network Inspector to investigate HTTP requests and responses
- [ ] Can describe why Transport Layer Security (TLS) is important and how it is used

### Basics of REST

The protégé will have demonstrated an understanding of the following concepts:

- [ ] Can describe what REST is and how it is useful for building APIs
- [x] Can describe how HTTP verbs and URLs are used in REST
- [ ] Can describe the different types of REST calls and what impact they have on the data
- [ ] Can describe the roles of Clients and Servers in REST

### Containerization

The protégé will have demonstrated an understanding of the following concepts and used them while completing exercises and katas:

- [x] Has built a Docker image which runs a C# application
- [x] Can describe the key elements of a `Dockerfile`
- [x] Can mount a Volume in a Docker container
- [x] Can describe what a Container Registry is, and how Docker uses them
- [x] Has published and pulled a Docker Image to a Container Registry

### Continuous Integration and Delivery

The protégé will have demonstrated an understanding of the following concepts and used them while completing exercises and katas:

- [x] Can describe the key systems and relationships involved in building and deploying an application to Jupiter or AWS
- [x] Can describe the differences between Continuous Integration, Continous Delivery, and Continous Deployment
- [x] Has implemented a pipeline that contains clear separation of compile, test, package, and deploy stages
- [x] Has implemented a pipeline where there is some form of verification before the deploy stage, and if the verification fails then the deploy does not occur
- [x] Can describe the pipeline providing explanations of each step, the sequence of steps, and the why and how for each of the steps
- [x] Has got an application running in Jupiter or AWS which is deployed via a pipeline

### Managing Secrets

The protégé will have demonstrated an understanding of the following concepts and used them while completing exercises and katas:

- [x] Can describe what a secret is with examples
- [x] Can describe why secrets should not be in code repositories
- [x] Can describe the different tools or services which could be used to manage secrets
- [x] Has used a tool or service to include a secret in an application or Docker container
