# AMI Internship
I began interning at AMI at the start of June and have completed 40 hours in total. During the internship, I learned what a Baseboard Management Console(BMC) is and the different parts of the BMC. This includes the IPMI protocol, Redfish API and the KVM. I have made this Github to showcase projects I have completed throughout the internship and to showcase what I have learned from this internship.

# BASICS

## Server
* Definition: A server is a computer system designed to provide resources and services to other computers or users over a network.
* Components: Servers typically include a CPU, memory, storage drives, networking interfaces, power supply, cooling system, and management interfaces (e.g., BMC/IPMI)
* Key Considerations: Servers should be reliable (24/7), scalable, secure, and efficient. They require effective hardware management, resource allocation, performance monitoring, and maintenance.

## BMC
* Definition: BMC is a specialized microcontroller embedded in computer systems that provides out-of-band management capabilities for remote monitoring, control, and maintenance of the hardware.
* Key Functions: BMC enables remote access to system status, sensor monitoring, power management, firmware updates, and console redirection.
* Benefits: BMC enhances system manageability, reduces downtime, facilitates troubleshooting, and enables remote administration. In terms of a server a BMC helps a server stay online 24/7 by informing the administrator of any issues that arise in the server.

## IPMI (Intelligent Platform Management Interface)
* Definition: IPMI is a standardized interface protocol used by BMCs for monitoring and controlling computer systems.
* Key Features: IPMI provides sensor readings (temperature, voltage, fan speed), event logging, power control, and remote console capabilities.
* Benefits: IPMI enables centralized management and monitoring of server hardware, even in the absence of an operating system, enhancing system availability and reliability.

## Redfish
* Definition: Redfish is a modern, open, and secure standard for hardware management that provides a RESTful interface to manage servers, storage, and networking devices.
* Key Features: Redfish allows uniform management of diverse hardware resources, supports event-driven notifications, provides standardized data models, and promotes scalability and interoperability.
* Benefits: Redfish simplifies management tasks, improves automation, facilitates integration with management systems, and enhances the overall efficiency of managing hardware infrastructure.

## KVM (Kernel-based Virtual Machine)
* Definition: KVM is a virtualization solution for Linux that allows running multiple virtual machines (guests) on a single physical server.
* Key Features: KVM leverages hardware virtualization extensions in modern CPUs, providing high-performance virtualization capabilities.
* Benefits: KVM enables efficient server consolidation, improved resource utilization, easy migration of virtual machines, and robust isolation between guests.
