# Baseboard Management Console (BMC)
* The BMC is a microncontroller found within the servers motherboard and is used to make sure the server is working properly and alert the server administrators if any issues arise within the server.
* BMCs are found widely throughout many different servers, they help keep check on server health and are used to help server admins fix and debug issues that arise within a server.
* The Baseboard Management Console has many different hardware components embedded inside of it, most notably the System Event Log, Field Replacable Unit and Sensor Data Record. 

## System Event Log (SEL)
* SEL is a log maintained by the BMC that records important system events, errors, and warnings.
* SEL provides a chronological record of events such as hardware failures, temperature excursions, power supply changes, and system initialization.
* SEL entries include timestamps, event types, event descriptions, and additional relevant data.
* Administrators can access the SEL to diagnose system issues, track hardware failures, and perform troubleshooting.
* SEL helps Administrators maintain a server and prevents unexpected crashes, which are crucial in servers in huge corporations such as Google.

## Sensor Data Records (SDR)
* SDRs store information about various sensors in the server, such as temperature, voltage, fan speed, and power consumption.
* SDRs define the sensor's type, location, thresholds, and current readings.
* The BMC continuously monitors sensor data and compares it against predefined thresholds to detect abnormalities.
* SDRs facilitate real-time monitoring, alerting, and system health management.
* SDRs are important to make sure a server does not have unreasonable sensor readings.

## Field Replacable Unit (FRU)
* FRUs are replaceable components in the server hardware that can be serviced or swapped independently.
* Each FRU has a unique identifier, such as part number, serial number, and asset tag, stored in the BMC.
* The BMC maintains a FRU inventory that includes details about installed FRUs, their locations, and associated information.
* FRU information helps administrators identify faulty components, track warranty status, and perform hardware maintenance and replacements.

## Power Control
* The BMC enables remote power control capabilities for the server.
* Administrators can remotely power on, power off, restart, or cycle power to the server.
* Power control features are valuable for managing and troubleshooting systems located in remote or inaccessible environments.

## Firmware Management
* The BMC facilitates firmware management for various components, including the BMC firmware, server BIOS, and other embedded devices.
* It allows administrators to update firmware versions, apply bug fixes, and deploy security patches.
* Firmware management enhances system stability, security, and compatibility with the latest enhancements and features.

## Remote Configuration & Inventory
* The BMC allows remote configuration of server settings, network parameters, and hardware configurations.
* It maintains an inventory of installed hardware components, including details such as model numbers, serial numbers, and firmware versions.
* Remote configuration and inventory management streamline administration, deployment, and maintenance tasks.

## Security & Authentication
* The BMC includes security features to ensure secure remote management.
* It provides authentication mechanisms, access control, encryption, and secure communication protocols to protect sensitive data.
* Security measures safeguard against unauthorized access and ensure the integrity and confidentiality of management operations.

Overall the Baseboard Management Console provides a lot of features for smoother server management. Huge providers such as Google and Amazon, use BMC technology in their servers to help manage their servers and gain constant updates. Using BMC technology major technology companies are able to stay ahead and regulate server crashes with huge companies only having around 5 minutes of downtime. Overall the Baseboard Management Console is a really useful chip and is essential to know about to get into the firmware development field.
