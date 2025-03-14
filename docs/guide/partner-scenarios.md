---
title: Microsoft partner and third-party scenarios on Azure
description: Review an extensive list of architectures and solutions that use Microsoft partner and third-party solutions.
author: martinekuan
ms.author: robbag
ms.date: 06/14/2023
ms.topic: conceptual
ms.service: azure-architecture-center
ms.subservice: architecture-guide
products:
  - azure-kubernetes-service
  - azure-netapp-files
  - azure-virtual-machines
  - entra-id
  - azure-virtual-desktop
  - azure-service-bus
categories:
  - databases
  - hybrid
  - analytics
  - web
  - iot
  - migration 
  - containers
  - integration 
  - media
  - compute
  - management-and-governance
  - storage
  - mobile
  - security
  - networking
  - azure-virtual-desktop
ms.custom: fcp
---

# Microsoft partner and third-party scenarios on Azure

This article explores Microsoft partner and third-party, non-open source scenarios on Microsoft Azure.

Microsoft partners make up a community of organizations that work with Microsoft to create innovative solutions for you. Driven by the opportunities of the intelligent cloud, Microsoft is prioritizing investments that support these opportunities.

The [Azure Sponsorship for ISVs program](https://azure.microsoft.com/partners/isv) helps independent software vendors (ISVs) use Azure services to drive platform innovation and develop new solutions that can accelerate your digital transformation. 

Visit [Azure Marketplace](https://azuremarketplace.microsoft.com) to discover, try, and deploy cloud software from Microsoft and Microsoft partners.

This article provides a summary of architectures and solutions that use Azure together with partner and third-party solutions. For more information, see [Apache open-source scenarios on Azure](/azure/architecture/guide/apache-scenarios).

## Advanced

|Architecture|Summary|Technology focus|
|--|--|--|
|[Refactor mainframe applications with Advanced](../example-scenario/mainframe/refactor-mainframe-applications-advanced.yml)|Learn how to use the automated COBOL refactoring solution from Advanced to modernize your mainframe COBOL applications, run them on Azure, and reduce costs.|Mainframe|

## Astadia

|Architecture|Summary|Technology focus|
|--|--|--|
|[Unisys Dorado mainframe migration to Azure with Astadia & Micro Focus](../example-scenario/mainframe/migrate-unisys-dorado-mainframe-apps-with-astadia-micro-focus.yml)|Migrate Unisys Dorado mainframe systems with Astadia and Micro Focus products. Move to Azure without rewriting code, switching data models, or updating screens.|Mainframe|

## Avanade

|Architecture|Summary|Technology focus|
|--|--|--|
|[IBM z/OS mainframe migration with Avanade AMT](../example-scenario/mainframe/avanade-amt-zos-migration.yml)|Learn how to use the Avanade Automated Migration Technology (AMT) framework to migrate IBM z/OS mainframe workloads to Azure.|Mainframe|
|[Unisys mainframe migration with Avanade AMT](../reference-architectures/migration/unisys-mainframe-migration.yml)|Learn options for using the AMT framework to migrate Unisys mainframe workloads to Azure.|Mainframe|

## Confluent

|Architecture|Summary|Technology focus|
|--|--|--|
|[Banking system cloud transformation on Azure](../example-scenario/banking/banking-system-cloud-transformation.yml)|Use simulated and actual applications and existing workloads to monitor the reaction of a solution infrastructure for scalability and performance. Kafka is used with Confluent Schema Registry for streaming.|Migration|

## Infinite i

|Architecture|Summary|Technology focus|
|--|--|--|
|[IBM System i (AS/400) to Azure using Infinite i](../example-scenario/mainframe/ibm-system-i-azure-infinite-i.yml)|Use Infinite i to easily migrate your IBM System i (AS/400) workloads to Azure. You can lower costs, improve performance, improve availability, and modernize.|Mainframe|

## LzLabs

|Architecture|Summary|Technology focus|
|--|--|--|
|[Use LzLabs Software Defined Mainframe (SDM) in an Azure VM deployment](../example-scenario/mainframe/lzlabs-software-defined-mainframe-in-azure.yml)|Learn an approach for rehosting mainframe legacy applications in Azure by using the LzLabs SDM platform.|Mainframe|

## Micro Focus

|Architecture|Summary|Technology focus|
|--|--|--|
|[Micro Focus Enterprise Server on Azure VMs](../example-scenario/mainframe/micro-focus-server.yml)|Optimize, modernize, and streamline IBM z/OS mainframe applications by using Micro Focus Enterprise Server 6.0 on Azure VMs.|Mainframe|
|[Unisys Dorado mainframe migration to Azure with Astadia & Micro Focus](../example-scenario/mainframe/migrate-unisys-dorado-mainframe-apps-with-astadia-micro-focus.yml)|Migrate Unisys Dorado mainframe systems with Astadia and Micro Focus products. Move to Azure without rewriting code, switching data models, or updating screens.|Mainframe|

## MongoDB

|Architecture|Summary|Technology focus|
|--|--|--|
|[Advanced Azure Kubernetes Service (AKS) microservices architecture](../reference-architectures/containers/aks-microservices/aks-microservices-advanced.yml)|Learn about a scalable, highly secure AKS microservices architecture that builds on recommended AKS microservices baseline architectures and implementations. In this architecture, Azure Cosmos DB stores data by using the open-source Azure Cosmos DB for MongoDB. |Containers|
|[Core startup stack architecture](../example-scenario/startups/core-startup-stack.yml)|Review the components of a simple core startup stack architecture. MongoDB is recommended for uses cases that require a NoSQL database.|Startup|
|[Data considerations for microservices](../microservices/design/data-considerations.yml)|Learn about managing data in a microservices architecture. The MongoDB API is used with Azure Cosmos DB in an example scenario.|Microservices|
|[Baseline web application with zone redundancy](../web-apps/app-service/architectures/baseline-zone-redundant.yml)|Use the proven practices in this reference architecture to improve redundancy, scalability and performance in an App Service web application. MongoDB is recommended for non-relational data. |Web|

## NetApp

|Architecture|Summary|Technology focus|
|--|--|--|
|[AIX UNIX on-premises to Azure Linux migration](../example-scenario/unix-migration/migrate-aix-azure-linux.yml)|Migrate an on-premises IBM AIX system and web application to a highly available, highly secure Red Hat Enterprise Linux solution in Azure. Azure NetApp Files provides shared NAS.|Mainframe|
|[Enterprise file shares with disaster recovery](../example-scenario/file-storage/enterprise-file-shares-disaster-recovery.yml)|Learn how to implement resilient NetApp file shares. Failure of the primary Azure region causes automatic failover to the secondary Azure region.|Storage|
|[FSLogix configuration examples](/fslogix/concepts-configuration-examples)|Learn how to build virtual desktop infrastructure solutions at enterprise scale by using FSLogix. Azure NetApp Files is recommended for storing profiles.  |Hybrid|
|[General mainframe refactor to Azure](../example-scenario/mainframe/general-mainframe-refactor.yml)|Learn how to refactor mainframe applications to run more cost-effectively and efficiently on Azure. Azure NetApp Files is recommended for file storage. |Mainframe|
|[Moodle deployment with Azure NetApp Files](../example-scenario/file-storage/moodle-azure-netapp-files.yml)|Deploy Moodle with Azure NetApp Files for a resilient solution that offers high-throughput, low-latency access to scalable shared storage.|Storage|
|[Multiple forests with AD DS and Microsoft Entra ID](../example-scenario/azure-virtual-desktop/multi-forest.yml)|Learn how to create multiple Active Directory forests with Azure Virtual Desktop. Azure NetApp Files is one recommended storage solution for the scenario.|Virtual Desktop|
|[Oracle Database with Azure NetApp Files](../example-scenario/file-storage/oracle-azure-netapp-files.yml)|Implement a high-bandwidth, low-latency solution for Oracle Database workloads. Use Azure NetApp Files to get enterprise-scale performance and to reduce costs.|Storage|
|[Refactor mainframe computer systems that run Adabas & Natural](../example-scenario/mainframe/refactor-adabas-aks.yml)|Learn how to modernize mainframe computer systems that run Adabas & Natural and move them to the cloud. Azure NetApp Files is used to store persistent data.|Mainframe|
|[Run SAP BW/4HANA with Linux VMs](../reference-architectures/sap/run-sap-bw4hana-with-linux-virtual-machines.yml)|Learn about the SAP BW/4HANA application tier and how it's suitable for a high-availability, small-scale production environment of SAP BW/4HANA on Azure. Azure NetApp Files is used by a high-availability cluster for shared file storage. |SAP|
|[SAP deployment in Azure using an Oracle database](../example-scenario/apps/sap-production.yml)|Learn proven practices for running SAP on Oracle in Azure, with high availability.|SAP|
|[SAP HANA for Linux VMs in scale-up systems](../reference-architectures/sap/run-sap-hana-for-linux-virtual-machines.yml)|Learn proven practices for running SAP HANA in a high availability scale-up environment that supports disaster recovery.|SAP|
|[SAP S/4HANA in Linux on Azure](/azure/architecture/guide/sap/sap-s4hana)|Learn proven practices for running SAP S/4HANA in a Linux environment on Azure, with high availability.|SAP|
|[SAS on Azure architecture](../guide/sas/sas-overview.yml)|Learn how to run SAS analytics products on Azure. Includes recommendations for using Azure NetApp Files.|Compute|
|[SQL Server on Azure Virtual Machines with Azure NetApp Files](../example-scenario/file-storage/sql-server-azure-netapp-files.yml)|Implement a high-bandwidth, low-latency solution for SQL Server workloads. Use Azure NetApp Files to get enterprise-scale performance and to reduce costs.|Storage|

## NServiceBus

|Architecture|Summary|Technology focus|
|--|--|--|
|[Build message-driven business applications with NServiceBus and Azure Service Bus](/azure/service-bus-messaging/build-message-driven-apps-nservicebus)|Use NServiceBus to build better message-driven applications on Azure Service Bus, abstracting infrastructure concerns like serialization, routing, and dead-lettering.|Microservices|

## Oracle

|Architecture|Summary|Technology focus|
|--|--|--|
|[Migrate IBM mainframe apps to Azure with TmaxSoft OpenFrame](../solution-ideas/articles/migrate-mainframe-apps-with-tmaxsoft-openframe.yml)|Migrate IBM zSeries mainframe applications to Azure. Use a no-code approach that TmaxSoft OpenFrame provides. OpenFrame can integrate with RDBMSs like Oracle.|Mainframe|
|[Migrate an Oracle database to Azure](../databases/idea/topic-migrate-oracle-azure.yml)|Migrate an Oracle database and its applications to Azure. You can migrate to either Azure virtual machines or Oracle Database@Azure, Exadata Database Service.|Oracle|
|[Oracle Database with Azure NetApp Files](../example-scenario/file-storage/oracle-azure-netapp-files.yml)|Implement a high-bandwidth, low-latency solution for Oracle Database workloads. Use Azure NetApp Files to get enterprise-scale performance and to reduce costs.|Storage|
|[Refactor mainframe applications with Advanced](../example-scenario/mainframe/refactor-mainframe-applications-advanced.yml)|Learn how to use the automated COBOL refactoring solution from Advanced to modernize your mainframe COBOL applications, run them on Azure, and reduce costs. Use Oracle databases on VMs for persistent data.|Mainframe|
|[Run SAP NetWeaver in Windows on Azure](/azure/architecture/guide/sap/sap-netweaver)|Learn proven practices for running SAP NetWeaver in a Windows environment on Azure, with high availability. Oracle is one recommended database.|SAP|
|[SAP deployment on Azure using an Oracle database](../example-scenario/apps/sap-production.yml)|Learn proven practices for running SAP on Oracle in Azure, with high availability.|Oracle|

## Qlik

|Architecture|Summary|Technology focus|
|--|--|--|
|[Mainframe and midrange data replication to Azure using Qlik](../example-scenario/mainframe/mainframe-midrange-data-replication-azure-qlik.yml)|Learn how Qlik Replication is a valuable tool for migrating mainframe and midrange systems to the cloud, or for extending such systems with cloud applications.|Mainframe|

## Raincode

|Architecture|Summary|Technology focus|
|--|--|--|
|[Rehost mainframe applications to Azure with Raincode compilers](../reference-architectures/app-modernization/raincode-reference-architecture.yml)|Learn how the Raincode COBOL compiler modernizes mainframe legacy applications.|Mainframe|

## SAP

|Architecture|Summary|Technology focus|
|--|--|--|
|[Multitier web application built for HA/DR](../example-scenario/infrastructure/multi-tier-app-disaster-recovery.yml)|Learn how to create a resilient multitier web application built for high availability and disaster recovery on Azure. Common scenarios include any mission-critical application that runs on Windows or Linux, including applications like SAP. |Networking|
|[Run SAP BW/4HANA with Linux VMs](../reference-architectures/sap/run-sap-bw4hana-with-linux-virtual-machines.yml)|Learn about the SAP BW/4HANA application tier and how it's suitable for a high availability small-scale production environment of SAP BW/4HANA on Azure.|SAP|
|[Run SAP HANA for Linux VMs in scale-up systems](../reference-architectures/sap/run-sap-hana-for-linux-virtual-machines.yml)|Learn proven practices for running SAP HANA in a high availability scale-up environment that supports disaster recovery.|SAP|
|[Run SAP NetWeaver in Windows on Azure](/azure/architecture/guide/sap/sap-netweaver)|Learn proven practices for running SAP NetWeaver in a Windows environment on Azure, with high availability.|SAP|
|[SAP deployment on Azure using an Oracle database](../example-scenario/apps/sap-production.yml)|Learn proven practices for running SAP on Oracle in Azure, with high availability.|SAP|
|[SAP S/4HANA for Large Instances](../solution-ideas/articles/sap-s4-hana-on-hli-with-ha-and-dr.yml)|With large SAP HANA instances, use Azure Virtual Machines, OS clustering, and NFS storage for scalability, performance, high reliability, and disaster recovery.|SAP|
|[SAP S/4HANA in Linux on Azure](/azure/architecture/guide/sap/sap-s4hana)|Review proven practices for running SAP S/4HANA in a Linux environment on Azure, with high availability.|SAP|
|[SAP workload automation using SUSE on Azure](../solution-ideas/articles/sap-workload-automation-suse.yml)|Use this solution to bolster productivity and facilitate innovation.|SAP|

## SAS

|Architecture|Summary|Technology focus|
|--|--|--|
|[SAS on Azure architecture](../guide/sas/sas-overview.yml)|Learn how to run SAS analytics products on Azure. See guidelines for designing and implementing cloud solutions for SAS Viya and SAS Grid.|Compute|

## Skytap

|Architecture|Summary|Technology focus|
|--|--|--|
|[Migrate AIX workloads to Skytap on Azure](../example-scenario/mainframe/migrate-aix-workloads-to-azure-with-skytap.yml)|Learn now to migrate AIX logical partitions (LPARs) to Skytap on Azure.|Mainframe|
|[Migrate IBM i series to Azure with Skytap](../example-scenario/mainframe/migrate-ibm-i-series-to-azure-with-skytap.yml)|Learn how to use the native IBM i backup and recovery services with Azure components.|Mainframe|

## Software AG

|Architecture|Summary|Technology focus|
|--|--|--|
|[Refactor mainframe computer systems that run Adabas & Natural](../example-scenario/mainframe/refactor-adabas-aks.yml)|Learn how to modernize mainframe computer systems that run Adabas & Natural and move them to the cloud.|Mainframe|

## Stromasys

|Architecture|Summary|Technology focus|
|--|--|--|
|[Stromasys Charon-SSP Solaris emulator on Azure VMs](../solution-ideas/articles/solaris-azure.yml)|Learn how the Charon-SSP cross-platform hypervisor emulates legacy Sun SPARC systems on industry standard x86-64 computer systems and VMs.|Mainframe|

## Syncier

|Architecture|Summary|Technology focus|
|--|--|--|
|[GitOps for Azure Kubernetes Service](../example-scenario/gitops-aks/gitops-blueprint-aks.yml)|View a GitOps solution for an AKS cluster. This solution provides full audit capabilities, policy enforcement, and early feedback. Syncier Security Tower provides an overview of all AKS clusters and helps manage policies. |Containers|

## TmaxSoft

|Architecture|Summary|Technology focus|
|--|--|--|
|[Migrate IBM mainframe apps to Azure with TmaxSoft OpenFrame](../solution-ideas/articles/migrate-mainframe-apps-with-tmaxsoft-openframe.yml)|Migrate IBM zSeries mainframe applications to Azure. Use a no-code approach that TmaxSoft OpenFrame provides.|Mainframe|

## Unisys

|Architecture|Summary|Technology focus|
|--|--|--|
|[Unisys ClearPath Forward mainframe rehost to Azure using Unisys virtualization](../example-scenario/mainframe/unisys-clearpath-forward-mainframe-rehost.yml)|Use virtualization technologies from Unisys and Azure to migrate from a Unisys ClearPath Forward Libra (legacy Burroughs A Series/MCP) mainframe.|Mainframe|

## Related resources

- [Apache open-source scenarios on Azure](/azure/architecture/guide/apache-scenarios)
- [Scenarios featuring Microsoft on-premises technologies](../guide/on-premises-microsoft-technologies.md)
- [Architecture for startups](../guide/startups/startup-architecture.md)
- [Azure and Power Platform scenarios](../solutions/power-platform-scenarios.md)
- [Azure and Microsoft 365 scenarios](../solutions/microsoft-365-scenarios.md)
- [Azure and Dynamics 365 scenarios](../solutions/dynamics-365-scenarios.md)
- [Azure for AWS professionals](../aws-professional/index.md)
- [Azure for Google Cloud professionals](../gcp-professional/index.md)
