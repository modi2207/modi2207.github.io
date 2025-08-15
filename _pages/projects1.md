---
layout: page
permalink: /projects/
title: Projects
description: 
nav: true
nav_order: 3
---
## **1) eBPF-Based Code Profiling in Kubernetes Deployments**

**Tools/Technology:** Perforator, Kubernetes, eBPF | [Code](https://github.com/modi2207/Perforator_Profiling.git) | [April’25]

**Description:**

* Integrated **Perforator**, an **eBPF-based** performance profiler, into a **Kubernetes** environment to monitor both system-level and container-level application behavior with minimal overhead.
* Analyzed and visualized profiling data for CPU-bound and network-intensive applications to uncover runtime bottlenecks and optimize resource usage across Kubernetes workloads.

## **2) DPDK-Based High-Performance DNS Resolver**

**Tools/Technology:** DPDK, KDNS, AF_XDP, Multus CNI Plugins, Kubernetes | Advisor: Prof. Sameer G. Kulkarni | [Dec’24 - Present]

**Description:**

* Deployed and configured **KDNS**, a high-speed DNS resolver leveraging **DPDK** for kernel-bypass packet processing.
* Contributed to core development by upgrading **KDNS** to a newer DPDK release, adapting to API changes, and resolving compatibility issues.
* Currently developing **KDNS** for container environments using **AF_XDP** and **DPDK** with **Multus CNI plugins**.

## **3) Comparative Study of User-Space TCP/IP Stacks with DPDK**

**Tools/Technology:** DPDK, mTCP, F-Stack, h2load, NGINX | Advisor: Prof. Sameer G. Kulkarni | [Oct’24]

**Description:**

* Evaluated user-space TCP/IP stacks (**mTCP**, **F-Stack**, and **DPDK-KNI**) under **short and long flow** workloads by simulating real-world web traffic.
* Built an **NGINX web server** on top of user-space network stacks (mTCP and F-Stack), utilizing **DPDK** with kernel bypass to achieve substantial performance gains.


## **4) High-Performance Packet I/O Evaluation on Bare-Metal Systems**

**Tools/Technology:** DPDK, io_uring, pktgen | Advisor: Prof. Sameer G. Kulkarni | [June’24]

**Description:**

* Conducted an empirical performance analysis of modern packet I/O frameworks — **DPDK**, **io_uring**, and the native Linux networking stack — on a 10 Gbps testbed using synthetic traffic workloads.

## **5) 5G Stand Alone Network Slicing Simulation**

**Tools/Technology:** Open5GS, UERANSIM | [Code](https://github.com/modi2207/5G_SA_Network_Slicing.git) | [Nov’24]

**Description:**

* Deployed 5G RAN and core architecture using **Open5GS** and **UERANSIM** for end-to-end 5G simulation.
* Simulated network slicing for **eMBB**, **URLLC**, and **mMTC** by replicating control and user plane network functions.





## **6) Instant Payment Gateways**

**Tools/Technology:** Distributed Systems,Go lang,GRPC,ELK Stack,Mysql,Nginx,Docker \| [Code](https://github.com/modi2207/Instant-Payment-Gateway) \| [Feb’24-April’24]

**Description:**

 * Designed and implemented a high-performance, fault-tolerant payment gateway mimicking UPI functionality, capable of handling thousands of concurrent requests.
 * Implemented a load-balancing strategy using Nginx and containerized all servers and microservices (Nginx, MySQL,
Elasticsearch) using Docker for streamlined deployment and management.

 
## **7) Human Activity Recognizer**

**Tools/Technology:** Python,Sklearn,numpy,pandas \| [Code](https://github.com/modi2207/Human_Activity_Recognizer.git) \| [Feb’24]

**Description:**

 * Developed a machine learning model which classify 6 human activities (walking,walking upstair,walking downstair laying,sitting,standing) based on timeseries data of acceleration involved . I trained sklearn's decision tree on open source UCI-HCR dataset. 

 * Performed hypertuning to select best model parameters based on bias-variance tradeoff. Also tested this model with real data collected by mobile application and built confusion matrix.


## **8) Pretrainig and Fine-tuning LLM with BERT**

**Tools/Technology:** Python,Pytorch,Hugging Face Model Hub \| [Code](https://github.com/modi2207/Project-3) \|
 [October’23]

**Description:**
* Fine-tuned BERT for various NLP tasks (e.g., classification,entity recognition) using Python, NumPy, and PyTorch.
*  Contributed to the open-source community by uploading pretrained and fine-tuned BERT models to Hugging Face
Model Hub.



## **9) VOIP Call Application**

**Tools/Technology:** Angular, ELK Stack, WebRTC, Ejabberd XMPP \| [Code](https://github.com/modi2207/P2P_using_peerjs) \| [Dec’22]

**Description:**

* Designed and implemented a P2P video call application utilizing WEBRTC technology and XMPP signaling server
* Integrated Elasticsearch to enable optimized searching of usernames from large user databases.



## **10) Nextdoor- Property Rental Website** 

**Tools/Technology:** Java Servlets,JSP,HTML,CSS, Java script,Bootstrap,Eclipse,Sql Server Management Studio \| [Code](https://github.com/modi2207/NextDoor.git) \| [Feb 2021 - April 2021]

**Description:**

* Nextdoor is property rental website in which Landlord can add property for rent and renter can select property based on requirement and can contact to landlord. Landlord also can make rent agreement and save as pdf for future purposes.



## **11) Quicknote- Notes Sharing System For Students**

**Tools/Technology:** Java Servlets,JSP,HTML,CSS, Java script,Bootstrap, Eclipse,Sql Server Management Studio \| [Code](https://github.com/modi2207/Quicknote.git) \| [March 2021 - April 2021]

**Description:**

* Quicknote is note sharing website which is usefull for college students where all notes can be access at one place. Student can upload their notes and other students can access those notes easily.




## **12) MSUAdSense- MSU Event Programmes**

**Tools/Technology:**  java swing,JDBC, Java Mail Api,SQL,Eclipse,Sql Server Management Studio \| [Code](https://github.com/modi2207/Msu_ad_sense) \| [Dec 2019 - Feb 2020]

**Description:**

* MSUAdEx is a portal in which any student can see latest updates in fests/events which is held in university and through which student can also participate in fest. It is also useful to Organizers of event.



## **13) Institute Management System(IMS)**

**Tools/Technology:** Lucidchart, Draw.io \| [docs](https://github.com/modi2207/Institute_Management_System.git) \| [Aug 2019 - Sept 2019]

**Description:**

* Developed SDLC (software develop life cycle ) documentation for institute management system.

<!-- I am currently interning at a startup founded by an alumnus of IIT Hyderabad, specializing in crime detection using an ML-based model with high accuracy and low latency.

Here are some of the work carried out 



For now, this page is assumed to be a static description of your courses. You can convert it to a collection similar to `_projects/` so that you can have a dedicated page for each course.

Organize your courses by years, topics, or universities, however you like! -->
