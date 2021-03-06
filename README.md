# **Blaktip**
## Monitor, manage, and instrument marine livestock environments...
**Blaktip** is a modern serverless application used to monitor, manage instrument marine livestock environments. The app showcases serverless services using the AWS platform.

The mobile front-end is built using the [Expo](https://expo.io/) framework and client libraries to call AWS services and mobile backend APIs. The backend APIs themselves are powered by AWS services. The backend APIs are built using a serverless architecture, which makes it easy to deploy updates, and it also means that there are no servers to operationally manage.

**Blaktip** is primarily developed and maintained by Dan Brown. The project code is released under the Apache 2.0 license. Dan also maintains a [Developer Guide](/DEVGUIDE.md) for those that would like to dive deeper. This project has several over-arching objectives:

* ### Serverless Reference Architecture
  Show off Serverless
* ### AWS Concept Sandbox
  Learn how to integrate and operate
* ### Modern Software Deployment Sandbox
  Learn how to deliver
* ### Product Development
  Build something I need

## AWS Services Used
**Blaktip** is built using the following AWS services:

[AWS Cognito](https://aws.amazon.com/cognito/) - Amazon Cognito lets you easily add user sign-up and sign-in to your mobile and web apps. With Amazon Cognito, you also have the options to authenticate users through social identity providers such as Facebook, Twitter, or Amazon, with SAML identity solutions, or by using your own identity system. Furthermore, AWS Cognito supports User Groups that let to create collections of users to manage their permissions or to represent different types of users. For this application we are using User Pool Authentication.

[AWS Lambda](https://aws.amazon.com/lambda/) - AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume - there is no charge when your code is not running. With Lambda, you can run code for virtually any type of application or backend service - all with zero administration.

[Amazon DynamoDB](https://aws.amazon.com/dynamodb/) - Amazon DynamoDB is a fast and flexible NoSQL database service for all applications that need consistent, single-digit millisecond latency at any scale. It is a fully managed cloud database and supports both document and key-value store models.

[Amazon API Gateway](https://aws.amazon.com/api-gateway/) - Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. You can create an API that acts as a “front door” for applications to access data, business logic, or functionality from your back-end services, such as workloads running on Amazon Elastic Compute Cloud (Amazon EC2), code running on AWS Lambda, or any Web application. Amazon API Gateway handles all the tasks involved in accepting and processing up to hundreds of thousands of concurrent API calls, including traffic management, authorization and access control, monitoring, and API version management.

[AWS CloudFormation](https://aws.amazon.com/cloudformation/) - AWS CloudFormation gives developers and systems administrators an easy way to create and manage a collection of related AWS resources, provisioning and updating them in an orderly and predictable fashion.

# Reference Architecture
---PICTURE HERE---
## Logical Architecture
---PICTURE HERE--
## Physical Architecture
---PICTURE HERE--
## Application Architecture
### Front End
* #### Web
* #### iOS
* #### Android
### Back End API
* #### Admin APIs
* #### Device APIs
* #### Client APIs
## Data Architecture
### Information Flows
### Analytics
### Data Structures
### Data Model(s)
## Security Architecture
### Authentication & Authorization
### Data Protection
### Network Security
### Device Authentication and Hardening
