# Notes about AZ-900 certification

## Studying the playlist from  <a href="https://www.youtube.com/watch?v=NPEsD6n9A_I&list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM&ab_channel=AdamMarczak-AzureforEveryone"> Adam Marczak - Azure for Everyone. </a>



# Summary

- [Episode 1 - Cloud Computing and Vocabulary](https://github.com/AfonsoFeliciano/AZ-900-Notes/blob/main/README.md#Cloud-Computing-and-Vocabulary)
- [Episode 2 - Principle of economies of scale](https://github.com/AfonsoFeliciano/AZ-900-Notes/blob/main/README.md#Principle-of-economies-of-scale)
- [Episode 3 - CapEx vs OpEx and their differences](https://github.com/AfonsoFeliciano/AZ-900-Notes/blob/main/README.md#CapEx-vs-OpEx-and-their-differences)
- [Episode 4 - Consumption-based Model](https://github.com/AfonsoFeliciano/AZ-900-Notes/blob/main/README.md#Consumption-based-Model)
- [Episode 5 - IaaS vs PaaS vs SaaS cloud service models](https://github.com/AfonsoFeliciano/AZ-900-Notes/blob/main/README.md#IaaS-vs-PaaS-vs-SaaS-cloud-service-models)





## Cloud Computing and Vocabulary

### The main goals consist of describing terms such as: 

- High Availability
- Scalability
- Elasticity
- Agility
- Fault Tolerance
- Disaster Recovery

### Cloud computing

Can be defined as a delivery model for services like storage (files, databases), computer power (virtual machines using windows or Linux and web services), networking (firewalls), analytics (performance, telemetry)

### Scalability 

Increase the size of a resource. 

Vertical scaling can be divided into two terms: 
- Scaling up: increase the memory, CPU, and storage
- Scaling down: decrease the memory, CPU, storage

Horizontal scaling, which increases the amount/quantity of the resources, can be divided into two terms: 
- Scaling out: increase the amount
- Scaling in: decrease the amount

<p align="center">
    <img
    src="imgs/Screenshot_1.png"
    title="Scalability"
    style="display: inline-block; margin: 0 auto; max-width: 400">
</p>

In other terms

> Scalability is the ability to scale, adding or removing resources

### Elasticity

 The workload used during the day by the users where can be automatic scaling. 

<p align="center">
    <img
    src="imgs/Screenshot_2.png"
    title="Elasticity"
    style="display: inline-block; margin: 0 auto; max-width: 400">
</p>

> Elasticity is the ability to scale dynamically

### Agility

The resources can be provided in two ways: manual or APIs and scripts. The main difference comparing cloud and on-premises environments is the time to finish. 

Cloud is faster than on-premises

<p align="center">
    <img
    src="imgs/Screenshot_3.png"
    title="Agility"
    style="display: inline-block; margin: 0 auto; max-width: 400">
</p>

The main definition is: 

> The ability to react quickly

### Fault Tolerance One failure will not interrupt the service

> Disaster is a serious disruption of services caused by natural or human-induced causes.

Based on disaster, the term disaster recovery appears, using replication on multiple locals.

> Disaster recovery is the ability to recover from an event that has taken down the service.

### High availability 

Is a metric with measures the downtime of the services.

<p align="center">
    <img
    src="imgs/Screenshot_4.png"
    title="High availability "
    style="display: inline-block; margin: 0 auto; max-width: 400">
</p>

> Availability is a measure of system uptime for users/services and high availability is the ability to keep services running for extended periods of time with very little downtime.


<a href="https://marczak.io/az-900/episode-01/practice-test/"> Episode 1: Practice test </a>

## Principle of economies of scale

When the company grows in size, it becomes more effective at what they do. Thanks to this they can reduce their operating costs and therefore decrease their price per unit.


<p align="center">
    <img
    src="imgs/Screenshot_5.png"
    title="Principle of economies of scale"
    style="display: inline-block; margin: 0 auto; max-width: 400">
</p>

<a href="https://marczak.io/az-900/episode-02/practice-test/"> Episode 2: Practice test </a>

## CapEx vs OpEx and their differences

Main goal:

- Describe the differences between Capital Expenditure (CapEx) and Operational Expenditure (OpEx)

### CapEx

- You have your infrastructure
- You need a big initial investment
- Lost of maintenance required
1. Support Staff
2. Power & Networking
3. Hardware failures
4. others

> An action of spending company funds upfront


<p align="center">
    <img
    src="imgs/Screenshot_6.png"
    title="CapEx"
    style="display: inline-block; margin: 0 auto; max-width: 400">
</p>


### OpEx

- Rent infrastructure
- No need for initial investment because the pay is for what is used
- Minimal maintenance
1. Operations team

<p align="center">
    <img
    src="imgs/Screenshot_7.png"
    title="OpEx"
    style="display: inline-block; margin: 0 auto; max-width: 400">
</p>

> You spend money on services every month as you use them. As such you deduct the tax in the same year. 

### Differences

<p align="center">

| Caracteristic     | #CapEx        | #OpEx          |
| :---:             | :---:         | :---:          |
| Up front cost     | Significant   | None           |       
| Ongoing cost      | Low           | Based on Usage |
| Tax Deuction      | Over time     | Same year      |
| Early Termination | No            | Anytime        |
| maintenance       | Significant   | Low            |
| Value over time   | Lowers        | No change      |

</p>


<a href="https://marczak.io/az-900/episode-03/practice-test/"> Episode 3: Practice test </a>

## Consumption-based ModelThere are no upfront costs
- No wasted resources 
- Pay when you need the resources
- Stop paying at any time

It's possible to pay for the use from compute, storage and network. In this case, are:
- Multiple pricing components per service
- Very granular usage measurement




<p align="center">
    <img
    src="imgs/Screenshot_8.png"
    title="Compution based model"
    style="display: inline-block; margin: 0 auto; max-width: 400">
</p>

Each service in the cloud has multiple small consumption-based metrics which combined make up for the service cost. This allows the cloud provider to charge their customers appropriately for their usage. 

<p align="center">
    <img
    src="imgs/Screenshot_9.png"
    title="Price example"
    style="display: inline-block; margin: 0 auto; max-width: 400">
</p>

<a href="https://marczak.io/az-900/episode-04/practice-test/"> Episode 4: Practice test </a>

## IaaS vs PaaS vs SaaS cloud service models

The goals are: 
- Describe infrastructure as a service (IaaS)
- Describe Platform as a service (PaaS)
- Describe Software as a service (SaaS)
- Compare and contrast the three different service types

Differentiating the layers

<p align="center">
    <img
    src="imgs/Screenshot_10.png"
    title="Types of layers"
    style="display: inline-block; margin: 0 auto; max-width: 400">
</p>

> On-Premises manage everything including infrastructure, platform and software. The infrastructure contains networking, hardware and virtualization. 
Platform contains operating system, middleware, runtime
Software contains data and applications

### IaaS

Cloud provider manages infrastructure and you manage the platform and softwares. 

Examples of use cases: 
- Migration of workloads
- Test and development
- Storage, backups and recovery

Examples of services:
- Virtual machine
- Virtual network
- Managed disk

### PaaS

Cloud provider manages infrastructure and platform and you manage only the software layer

Example of use cases:
- Development framework
- Analytics and business intelligence

Examples of services:
- SQL
- App Service
- Logic Apps
- Function Apps

### SaaS

Cloud provider manages everything (infrastructure, platform and software) and you manage nothing.

Examples of use cases:
- Buying the shell applications

Example of services:
- One drive
- Outlook
- Skype




