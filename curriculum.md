# Node-RED learning curriculum

This document outlines the learning for developer to allow them to understand low-code programming using Node-RED, get started using Node-RED and be able to create a production ready application in Node-RED

## Intro & Concepts

This section should deliver a key understanding of Low-Code technology and what roles it can play in a solution.

**Target Audience** : All Developers, Architects  
**Barriers to entry** : None  
**Product covered** : [Open Source Node-RED](https://nodered.org)  
**Content delivery formats** : Presentation style content, no hands on  
**Learner outcomes** (After completing the content the learner will be able to .....):  

- understand what low-code development is
- understand flow based programming concepts
- understand how low-code programming can fit in a modern cloud native development process
- understand that low-code development is suitable for developers to use (it is not just a tool for non-developers)

## Getting Started

This section should enable a developer to adopt Node-RED technology and apply the learning to their own solutions.

**Target Audience** : All Developers (content focus is a Cloud Native developer)  
**Barriers to entry** : Developer grade laptop  
**Content delivery formats** : Presentation style content with hands-on experience  
**Learner outcomes** (After completing the content the developer will be able to .....):  

- understand the JSON data format and the data types used in Node-RED (JavaScript)
- Understand and be able to apply the event driven programming model
- apply best practices to create well structured, maintainable Node-RED applications
- use the Node-RED browser based interface to  access the capabilities offered by Node-RED
- have a good working knowledge of the key nodes and can apply their functionalities to create solutions
- incorporate data storage services to their Node-RED applications
- handle more complex data types, such as binary data from IoT devices
- create more complex flow capability, such as loops, splitting and joining complex data structures, limiting data flow within an application
- create complex data mapping capability
- create user interfaces for applications using available add-on nodes

## Move to Production

This section should enable a developer to move their Node-RED applications to a production environment, to run as a managed application / service within a modern Cloud native environment

**Target Audience** : All Developers (content focus is for Cloud Native developer)
**Barriers to entry** :

- A good working knowledge of Node-RED
- A good working knowledge of cloud native development (devops, agile, git, .....)
- A laptop to complete the assignment work (tablet or phone OK to consume content, but laptop needed for assignment work)
- An active IBM Cloud account with resources available to deploy a NodeJS application.
- Access to a Kubernetes cluster (cloud based or local)
- Access to a source control git based repository (IBM Cloud or github.com)
- Access to a devops toolchain (IBM Cloud or Jenkins/Travis) with an understanding how to use the toolchain to automate build, test and deploy actions.

**Content delivery formats** : Presentation style content with hands-on experience  
**Learner outcomes** (After completing the content the developer will be able to .....):

- develop applications that follow the 12-factor app principles
- use appropriate techniques to handle credentials for services/API's provided by the runtime
- use appropriate strategies to handle application state and persistence in a scaleable cloud environment
- deploy a Node-RED based application as a CloudFoundry application *??-is this still a valid deploy option in the k8s world??*
- deploy a Node-RED based application to a Kubernetes cluster
- create cloud native applications that only use Node-RED features and nodes that are suitable for production use and can scale up and down as managed by the hosting platform
- enable project feature in the Node-RED editor and use git as a source code repo.
- design a developer workflow for cloud native applications using Jenkins to target a Kubernetes (knative?) runtime
- create the necessary endpoints within the application/service container to allow a cloud environment to monitor and manage Node-RED applications
