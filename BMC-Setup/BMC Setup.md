# Setting up a BMC
* BMCs can be set up on many different machines. During my internship I set up a BMC in a QEMU Virtual Machine, Raspian OS and Yocto.
* It is important to note BMCs are made of ARM architecture, while current day computers use x86 Intel Architecture.
  
## QEMU BMC
* As aforementioned BMCs use ARM architecture, in order to support this ARM architecture we must use QEMU. QEMU is a virtual machine that can run a virtual BMC.
* To start the BMC build process please refer to the links I have provided below to boot the BMC image.
* https://github.com/facebookarchive/openbmc-qemu/blob/main/README.md
* https://github.com/openbmc/docs/blob/master/development/dev-environment.md

## QEMU BMC Status Script
* Here I have provided a script you can use on VIM to run a status check on the BMC.
* The script purposefully does not check for certain commands to avoid errors and potentially crashing the BMC.
* If issues arise to debug simply place an exit block in vim where you believe the error is occuring.
* To run the command type ```./"cmdname".sh ```
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

## Raspian BMC
* In order to build a BMC in a Raspberry Pi you must download the BMC image from the Github below and run the image following the instructions in the Github.
* https://github.com/joshuaboniface/rpibmc
* Unlike most BMCs, in my personal opinion Raspian BMCs were the most useful and helped me gain the most understanding over a BMC. To setup a BMC using a Raspberry Pi functionally please follow the link below.
* https://www.boniface.me/a-raspberry-pi-bmc/
* Although setting up a Raspian BMC is very useful in understanding the different parts of a BMC, alternative options such as piKVMs provide much better options in understanding many complex aspects of BMCs and especially KVMs.
* https://www.pikvm.org

## Yocto Project
* Yocto is a framework that is derived from Linux, through the use of Yocto we can build a BMC on the Yocto framework.
* To start off install the Yocto image from the Github below and build the BMC image.
* https://github.com/openbmc/docs/blob/master/yocto-development.md
* Follow the steps on the Github to successfully build the Yocto image.

## Bonus 
* Most BMCs provided above required the use of an image to build a demo BMC.
* The challenge is to build a BMC without the an image and to build a BMC from scratch.
* You can start by using the Github below as a start to building the BMC.
*  I will warn you many errors will appear and you will need to do research as well as use already existing knowledge to successfully fix these errors.
* https://github.com/openbmc/docs/blob/master/development/dev-environment.md

Thank you for reading my notes over Baseboard Management Consoles, I hope they were helpful.
