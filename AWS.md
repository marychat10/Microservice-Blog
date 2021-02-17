# AWS Elastic Beanstalk
***
#### Deploy a .NET application using Elastic Beanstalk

## Step 1 Create an environment 

An AWS Elastic Beanstalk environment is a collection of AWS resources running an application version. You can deploy multiple environments when you need to run multiple versions of an application. For example, you might have development, integration, and production environments.

![AWS](https://user-images.githubusercontent.com/34166599/108118240-0b1a8b80-706c-11eb-90f8-fc0e71921826.JPG)

## Step 2 Publish your application to Elastic Beanstalk

To publish use the AWS Toolkit for Visual Studio to publish your application to Elastic Beanstalk.

![AWS2](https://user-images.githubusercontent.com/34166599/108130735-21c9de00-707e-11eb-8cca-8896a391f45c.JPG)


![AWS3](https://user-images.githubusercontent.com/34166599/108130888-5ccc1180-707e-11eb-8b73-f91dd5b7acd4.JPG)


![AWS4](https://user-images.githubusercontent.com/34166599/108130909-69506a00-707e-11eb-803b-216a60135ad9.JPG)


![AWS5](https://user-images.githubusercontent.com/34166599/108131327-19be6e00-707f-11eb-87fe-161bd635bb2b.JPG)


![AWS6](https://user-images.githubusercontent.com/34166599/108131348-217e1280-707f-11eb-8337-c704e45c0b26.JPG)



## Step 3 Go to the environment

![AWS8](https://user-images.githubusercontent.com/34166599/108132059-41fa9c80-7080-11eb-96ac-a37c663c92d1.JPG)

![AWS7](https://user-images.githubusercontent.com/34166599/108131378-2b077a80-707f-11eb-84fe-59e4ee409831.JPG)


#### Cloud is aiding Microservices

For creating, running, and upgrading resilient and highly scalable applications, microservices are an excellent option. AWS offers a lot of controlled building blocks to handle any element of the implementation of microservices and offers all the resources required to substitute these components with open source alternatives. Due to the variety of IaaS, PaaS, SaaS solutions, and SDK packages provided by this cloud platform, Amazon Web Services is one of the best options for deploying a microservice-based application. To support software of any complexity and size, AWS offers a large array of building blocks.

![AWS9](https://user-images.githubusercontent.com/34166599/108140737-5a72b300-7090-11eb-9416-50a287fc4728.JPG)



AWS has a number of offerings that address the most important challenges of
microservices architectures:

## On-demand resources 
AWS resources are available and rapidly provisioned when needed. Compared to traditional infrastructures, there is no practical limit on resources. Different environments and versions of services can temporarily or persistently co-exist. There is no need for difficult forecasting and guessing capacity. On-demand resources address the challenge of provisioning and scaling resources in a costefficient way.

## Experiment with low cost and risk 
The fact that you only pay for what you use dramatically reduces the cost of experimenting with new ideas. New features or services can be rolled out easily and shut down again if they aren’t successful. Reducing cost and risk for experimenting with new ideas is a key element of driving innovation. This perfectly fits with the goal of microservices to achieve high agility.

## Programmability 
AWS services come with an API, Command Line Interface (CLI), and an SDK for different programming languages. Servers or even complete architectures can be programmatically cloned, shut down, scaled, and monitored. Additionally, in case of failure, they can heal themselves automatically. Standardization and automation are keys to building speed, consistency, repeatability, and scalability. You are empowered to summon the resources you need through code and build-dedicated tools to minimize operational efforts for running microservices.


## Infrastructure as code 
In addition to using programmatic scripts  to provision and manage an infrastructure, AWS allows you to describe the whole infrastructure as code and manage it in a version control system–just as you do for application code. As a consequence, any specific version of an infrastructure can be redeployed at any time. You can compare the quality and performance of a specific infrastructure version with a specific application version and ensure that they are in
sync. Rollbacks are no longer limited to the application—they can include the whole infrastructure. 

## Continuous Delivery 
The programmability of the cloud allows automation of the provisioning and deployment process. Continuous Integration within the development part of the application lifecycle can be extended to the operations part of the lifecycle. This enables the adoption of Continuous Deployment and Delivery. Continuous delivery addresses the challenges of operational complexity that occur when you manage multiple application life cycles in parallel.

## Managed services 
A key benefit of cloud infrastructures is managed services. Managed services relieve you of the heavy lifting of provisioning virtual servers, installing, configuring and optimizing software, dealing with scaling and resilience, and doing reliable backups. System characteristics and features such as monitoring, security,
logging, scalability, and availability are already built into those services. Managed services are a major element you can use to reduce the operational complexity of running microservices architectures.

## Service orientation 
AWS itself follows a service-oriented structure. Each AWS service focuses on solving a well-defined problem and communicates with other services using clearly defined APIs. You can put together complex infrastructure solutions by combining those service primitives like LEGO blocks. This approach prevents reinventing
the wheel and the duplication of processes.

## Polyglot 
AWS provides a large choice of different storage and database technologies. Many popular operating systems that run on Amazon Elastic Compute Cloud (Amazon EC2) are available on the AWS Marketplace.

### Implement Microservice on AWS

AWS has integrated building blocks that support the development of microservices. Two popular approaches are using AWS Lambda and Docker containers with AWS Fargate.

-You simply upload your code with AWS Lambda and let Lambda take care of anything needed to run and scale the execution to satisfy your specific demand curve with high availability. One of AWS Lambda's greatest benefits is that you can move quickly: since protection and scaling are handled by AWS, you can concentrate on your business logic. The scalable platform is guided by the opinionated approach of Lambda.

-AWS Fargate is a container management service that allows you to run serverless containers so you don’t have worry about provisioning, configuring, and scaling clusters of virtual machines to run containers. Fargate can launch tens of thousands of containers and easily scale to run your most mission-critical applications.




