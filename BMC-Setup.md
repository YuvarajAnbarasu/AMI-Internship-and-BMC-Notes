# Setting up a BMC
* BMCs can be set up on many different machines. During my internship I set up a BMC in a QEMU Virtual Machine, Raspian OS and Yocto.
* It is important to note BMCs are made of ARM architecture, while current day computers use x86 Intel Architecture.
  
# QEMU BMC
* As aforementioned BMCs use ARM architecture, in order to support this ARM architecture we must use QEMU. QEMU is a virtual machine that can run a virtual BMC.
* To start the BMC build process please refer to the links I have provided below to boot the BMC image.
* https://github.com/facebookarchive/openbmc-qemu/blob/main/README.md
* https://github.com/openbmc/docs/blob/master/development/dev-environment.md

# QEMU BMC Status Script
* Here I have provided a script you can use on VIM to run a status check on the BMC.
* The script purposefully does not check for certain commands to avoid errors and potentially crashing the BMC.
* Note in order to run this script you will need access to the command obmcutil.

```
obmcutil bmcstate   
obmcutil bootprogress
obmcutil chassiskill
obmcutil chassisstate
obmcutil hoststate
obmcutil osstate      
obmcutil power 
obmcutil state
obmcutil status
obmcutil listbootblock
obmcutil listlogs
```

