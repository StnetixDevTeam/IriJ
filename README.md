# IriJ
## Owerview
The project "IriJ" is a product ready solution for organizing hosting on the basis of a heterogeneous environment. Heterogeneous environment - a set of public and private clouds and services for virtualization with a single point of resource management.

## Targets
* Hosting companies (having private cloud solutions and wanting go to hybrid clouds);
* SMB companies (wishing to use means of automation and monitoring of resource consumption by a hybrid cloud, or companies wishing to migrate in order to reduce costs with vendor-lock solutions to open);
* Internet services (using Iriy as a platform for operation).

## Objectives
* Application Store (Web application (CMS, DB, eCommerce, ...) ready for deploy on hybrid cloud);
* One single point of orchestration for different hypervizors and clouds;
* Flexible architecture (customer can add/change/remove many modules);
* Creation of a management system for a group of servers with Hyper-V hypervisor for WindowsServer and positioning as a lightweight analog of System Center.
* Creating a system for managing a group of servers with an ESXi hypervisor, using integration with vSphere. Positioning as a lightweight universal management interface (requered license key of VMware vSphere).
* Support solution for create a Docker-cluster (without the need to integrate with Swarm and Kubernetes)

## Subsystems
The project consists of several subsystems: 
* Arys - orchestration system, 
* Mokosh - billing system, 
* Gamayun - monitoring system, 
* Svyatogor - BLOB storage system, 
* Volga - security system,
* RiseDNS service (aka Rod project) - DNS loadbalanser,
* Svetloyar - Application Store service.
