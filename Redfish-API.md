# Redfish API
## Definition:
Redfish API is a standardized interface protocol developed by the Distributed Management Task Force (DMTF). It defines a set of commands, functions, and protocols for managing and monitoring modern IT infrastructure, including servers, storage, and networking equipment.

## Out-of-Band Management:

* Redfish API provides out-of-band management capabilities, enabling administrators to remotely monitor, control, and troubleshoot servers, even when the main operating system is unresponsive or offline.

## Purpose and Benefits:

* Redfish enables remote management and monitoring of hardware, enhancing system availability, and reducing the need for physical access to servers.
* Proactive monitoring, alerting, and troubleshooting with Redfish lead to improved system health and reduced downtime.
* Comprehensive management capabilities, including remote power control, sensor monitoring, event logging, and remote console access.

## Architecture:

* Redfish API consists of three main components: the BMC (Baseboard Management Controller), management software, and the Redfish protocol.
* The management software communicates with the BMC through the Redfish protocol, allowing remote interaction with the server.

## Key Features and Functionalities:

**Sensor Monitoring:** Real-time access to server sensors like temperature, voltage, fan speed, and power consumption for critical event alerts and monitoring.

**Event Logging:** Redfish maintains a log, the System Event Log (SEL), recording system events, errors, and warnings for diagnosing issues and tracking hardware failures.

**Remote Power Control:** Administrators can remotely power on, off, restart, or gracefully shutdown servers with Redfish.

**Remote Console Access:** Redfish offers remote console access, enabling BIOS configuration, OS installations, troubleshooting, and recovery tasks.

**Remote Virtual Media:** Support for mounting virtual media, such as ISO images or virtual disks, for remote software installations, firmware updates, or diagnostics.

**Security:** Redfish includes authentication, access control, encryption, and secure communication protocols to ensure secure remote management and protect data.

## Redfish Versions:

Redfish has evolved over time with versions like v1.0, v1.1, v1.2, and beyond, introducing enhanced features and capabilities.

## Redfish Usage:

* Redfish API finds application in data centers, server farms, and remote server management scenarios.
* It proves valuable for managing and monitoring servers in remote or inaccessible environments.
* System administrators, IT professionals, and service providers use Redfish to streamline management tasks, increase efficiency, and improve system availability.

Redfish API has a key difference from IPMI being that it is readable, this makes Redfish API more modern compared to most IPMI. Although this may be the case, many servers still contain IPMI spec over Redfish spec as it is very expensive to upgrade every single server to Redfish API.




