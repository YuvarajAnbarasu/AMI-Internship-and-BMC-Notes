# BMC
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
* a

## Firmware Management
* a

## Remote Configuration & Inventory
* a

## Security & Authentication
*
