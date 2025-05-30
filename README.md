# Nexfs-Public-Download 
# Note: The lastest downloads can always be found in the downloads section of the Nexustorage website

Vist our website for more information on [Nexustorage Nexfs](http://nexustorage.com)

Nexfs from Nexustorage protects data and lowers costs through united block, file, cloud and object storage technology.

NexFS delivers a unified smart, cost-effective and massively scalable storage solution.

NexFS does not attempt to bridge the gap in storage technologies, many have failed in the field, NexFS unites traditional block, file, cloud and object storage technologies, presenting a single feature-rich pool of storage, reducing cost, complexity. 

As software-defined storage NexFS offers flexibility, including the ability to configure and deploy storage systems your way; you choose the type of hardware, be that physical, virtual, cloud, or hybrid

NexFS Software is distributed under the [Nexustorage Terms & Conditions](https://www.nexustorage.com/nexustorage-terms-and-conditions) and [Nexustorage EULA](https://www.nexustorage.com/nexustorage-end-user-license-agreem)

Nexfscli is an opensource project which can be used to manage NexFS while also providing code examples on how to use the NexFS direct managment file API
Sure, here’s a professional and concise version of the release notes for **NexFS 1.8 LTS**:

---

## **NexFS 1.8 LTS – Release Notes**

**Release Date:** 30 May 2025
**Version:** 1.8 (Long-Term Support)

---

### **Overview**

NexFS 1.8 LTS is a major stability and scalability release that significantly enhances core components of the NexFS platform. This release introduces a highly optimized content web server, improves POSIX compatibility, and delivers important bug fixes and system hardening, making it the recommended upgrade for all production environments.

---

### **Highlights**

#### ✅ **Enhanced Content Web Server**

* Major architectural improvements to the integrated content web server.
* Significantly increased scalability under high-concurrency workloads.
* Lower latency and improved request handling for large-scale S3-compatible deployments.

#### 🧩 **Increased POSIX Compatibility**

* Extended support for POSIX file operations and behaviors.
* Improved compatibility with legacy and modern Linux applications relying on advanced file system semantics.

#### 🐛 **Bug Fixes**

* Resolved multiple stability issues and memory handling bugs identified in prior releases.
* Fixed edge-case errors in object listing, multipart uploads, and file attribute handling.

#### 🔐 **General System Hardening**

* Improved input validation and internal consistency checks.
* Enhanced error handling and defensive programming across all subsystems.
* Security-relevant fixes and safeguards based on code audits and field reports.

---

### **Upgrade Recommendation**

This release is recommended for all existing NexFS users, especially those operating in production or performance-sensitive environments. As an LTS release, 1.8 will receive extended support and maintenance updates.

---


NexFS Release 1.7 Highlights include:

  * Enhanced iSCSI Configuration: All iSCSI configuration settings are now available through the management web console.
  * iSCSI Active Server Information: Active server information is now accessible via the management API and management web console.
  * Improved Response to iSCSI Initiators: Better handling of scenarios where no storage on any tier is available to service a request.
  * Enhanced AWS S3 API Support: Including improved multipart upload compatibility.
  * Enhanced Management and Content Server: Improved functionality and performance.
  * Many Small Enhancements and Fixes: Various minor improvements and bug fixes.
    
Nexfs Release 1.6 Highlights include:
  * Enhanced iSCSI configuration
  * Extensive AWS S3 API Support, including Multipart uploads
    
NexFS Release 1.01.04(23)Highlights include:
  * Added DeleteObjects API method to Content Server (S3 API)
  * Enhanced Nexfs Server to use ListObjectv2 and DeleteObject when purging datafiles from S3 API Storage
  * Enhanced Managed Capacity Accounting
    
NexfS Release 1.01.03(23)Highlights include:
  * Added HTTPS server option for Management Console
  * Added HTTPS server option for Content Server (S3 API)
  * Added SSL Certificate Management
    
NexFS Release 1.01(23)Highlights include:
  * Intergrated S3 API server
  * Mapped S3 to POSIX ACLs
  * Support for running multiple Nexfs procs on the same server
  * Nexfs as an S3 T3 destination
    
NexFS Release 0.99.0 Highlights include:
  * Integrated Admin Web Console, For Management, Configuration and Service Overview
  * Configure iSCSI and NFS through the Admin Web Console
  * New Management API with AWS Style Version 4 Signatures 
  * Role-Based Security
  * SNMP Traps (v2c/3) - Service Status Change Alerts 
  * Remote Service Monitoring (Poll Service Status using HTTP)
  * Automated Structure MetaData Replication 
  * Automated Structure MetaData Replication Active Volume Failover
  * Support for Multiple Nexfs Instances Running on a Single Server
  * Accumulator Counters (For external Monitoring and graph), in addition to existing 60-minute statistics
  
NexFS Release 0.95 Highlights include:
  * Integrated iSCSI Server		
  * Managed NFS v3 & v4			
  * Enhanced Statistics                                    
  * Simplified Installation
  * File Metadata Replication
