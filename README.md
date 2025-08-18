# Event-Driven Architecture with SAP Integration Suite, Advanced Event Mesh

## Description

An event-driven architecture is a software architecture using events as the core means for interaction between its software components. One of the main components of an EDA are Event Brokers. SAP's flagship event broker is SAP Integration Suite, advanced event mesh.

In this session we will take a deep dive into SAP Integration Suite, advanced event mesh.

## Overview

![Pic 2](images/overview.png)

SAP Integration Suite, advanced event mesh is a fully managed event streaming and management service that enables enterprise-wide and enterprise-grade event-driven architecture. It is a full blown, general purpose Event Mesh. AEM offers enterprise-grade performance, reliability, security and governance. It scales to very large use cases – and very means very very very in this case.

- Advanced Event Mesh is a distributed mesh of event brokers that can be deployed across environments, both in the cloud and on-premise
- It offers a full-purpose set of eventing services covering all relevant use cases
- AEM supports event streaming, event management and event monitoring
- Brokers fully scale as required and come in T-shirt sizes to perfectly fit different needs

SAP Integration Suite, advanced event mesh

- is a general purpose, multi-site EDA platform and portal
- allows for SAP to SAP, SAP to Everything and Everything to Everything scenarios
- supports distributed networks of event brokers deployed in different clouds and on-premises
- can be deployed in your cloud of choice or in your on premises K8S
- provides sophisticated authentication and security features like Kerberos, OAuth or TLS
- offers fine-grained filtering options
- allows for real-time monitoring, capacity insights and distributed tracing
- provides support for all relevant protocols like JMS, REST, AMQP and MQTT, plus SMF.
- allows to start small and upgrade to bigger T-shirt sizes when your business grows
- provides an outstanding performance up to billions of events per day

SAP Integration Suite, advanced event mesh features touched, some just shortly, some in more detail, include:

- SAP Integration Suite, advanced event mesh queues
- SAP Integration Suite, advanced event mesh Cluster Manager
- SAP Integration Suite, advanced event mesh Mesh Manager
- SAP Integration Suite, advanced event mesh Event Designer and Event Management
- SAP Integration Suite, advanced event mesh Try Me!

## Requirements

- Understanding the basics of event-driven architectures, namely events, queues, topics, event subscriptions ...
- You would be able to execute most of the exercises without prior experience by just following the descriptions. For taking value out of the chance to explore Advanced Event Mesh some experience with event-driven architectures is recommended.

## User Data and Password

In order to log into Advanced Event Mesh, you can use the below email address with XX replaced with your user number.

Users:
AC191299U01 - AC191299U30 (AC191299UXX)

Email:
AC191299U01@sapexperienceacademy.com - AC191299U30@sapexperienceacademy.com

Pw: Ob8LC0OWRf1!

Please make sure to use incognito / private mode

Use this [Tenant](https://eu10.console.pubsub.em.services.cloud.sap/login?tenant-id=47ad3afc-3d8a-4dca-85bb-6cce8ebae9e3) to do the exercises.

## Exercises

SAP Integration Suite, advanced event mesh

- [Exercise 1 - Explore SAP Integration Suite, advanced event mesh](exercises/ex1/)

  - [Exercise 1.1 - Log into Advanced Event Mesh and Explore it](exercises/ex1#exercise-11---log-into-advanced-event-mesh-and-explore-it)
  - [Exercise 1.2 - Create a Queue in Advanced Event Mesh ](exercises/ex1#exercise-12---create-a-queue-in-advanced-event-mesh)
  - [Exercise 1.3 - Create a Subscription in Advanced Event Mesh](exercises/ex1#exercise-13---create-a-queue-subscription-in-advanced-event-mesh)
  - [Exercise 1.4 - Send an event from the Try Me! Tool to your Topic](exercises/ex1#exercise-14---send-an-event-from-the-try-me-tool-to-your-topic)

- [Exercise 2 - Use Cloud Integration for event mediation](exercises/ex2/)

  - [Exercise 2.1 - Setup REST Endpoint](exercises/ex2#21-setup-rest-endpoint)
  - [Exercise 2.2 - Create Integration Package](exercises/ex2#22-create-integration-package)
  - [Exercise 2.2 - Copy & Configure Integration Flow](exercises/ex2#23-copy--configure-integration-flow)
  - [Exercise 2.2 - Monitor Messages](exercises/ex2#24-monitor-messages)

- [Exercise 3 - Incremental growth: RAP based S4 events -> AEM -> web application as additional consumer](exercises/ex3/)

  - [Exercise 3.1 - Create new queue for RAP based events](exercises/ex3#exercise-31-create-new-queue-for-rap-based-events)
  - [Exercise 3.2 - Configure RAP based events](exercises/ex3#exercise-32-rap-based-events)
  - [Exercise 3.3 - Configure web application as subscriber](exercises/ex3#exercise-33-configure-web-application)
  - [Exercise 3.4 - Publish RAP based event again](exercises/ex3#exercise-34-publish-rap-based-event-to-again)

-

## Background Material

A lot of material to get up to speed with SAP Integration Suite, advanced event mesh is available.

- Blogs

  - [SAPs Event-Driven Ecosystem](https://blogs.sap.com/2022/09/01/saps-event-driven-ecosystem-revisited/)
  - [Advanced Event Mesh](https://blogs.sap.com/2022/10/28/turn-your-erp-into-a-team-player-introducing-sap-integration-suite-advanced-event-mesh/)
  - [Advanced Event Mesh Details](https://blogs.sap.com/2023/10/26/sap-advanced-event-mesh-create-your-first-event-broker/)

- Videos

  - [Discover Event-driven Integrations](https://www.youtube.com/watch?v=r9lyC_2ss2U)
  - [SAP on Azure](https://www.youtube.com/watch?v=NNrzXbX3mk0)

- Documentation

  - [Help](https://help.pubsub.em.services.cloud.sap/Cloud/cloud-lp.htm)

## License

Copyright (c) 2024 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
