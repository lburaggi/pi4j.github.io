---
title: Welcome to Pi4J
---

## Welcome to Pi4J

{{% notice note %}}Looking for the V1-versions of Pi4J which are compatible with Java 8?
[Click here...](/about/previous-version-v1/){{% /notice %}}

---

### Brief History

**The Pi4J Project** was started in **2012**, the same year the Raspberry Pi was introduced 
as a tool to provide Java developers a simple and familiar object-oriented interface library 
to access the low-level I/O capabilities of the Raspberry Pi including **GPIO**, **I2C**, 
**SPI**, **PWM** and **Serial** communications. 

---

### Project Mission/Goals

**The Pi4J Project's** mission is to provide a rich and powerful, yet simple to use, 
Java-friendly API library enabling programmatic access to the low-level hardware I/O 
capabilities of embedded platforms such as the Raspberry Pi.

![](/assets/about/home/pi4j-overview.jpg)

**As of Version 2.0, Pi4J will no longer include support for peripheral devices and 
add-on chipsets/boards as part of the core project.  A new plugin model has been introduced 
in version 2.0 that should help enable third-party development and support third-party 
add-ons which may be developed and maintained independently of the core Pi4J project.**

---

### Project Status Summary

Pi4J V.2 is finally starting to come together and is _almost_ ready for some real-world 
BETA testing.  Significant progress has been made on the general architecture and primary 
user-facing interfaces.  Pi4J V.2 is a complete re-write and **does not maintain API 
compatibility** with previous versions.  It is not intended to be a drop-in replacement 
for previous versions of Pi4J.  Version 2.0 is a completely new design bringing with it 
modern conventions, development practices, extensibility support, and a simplified integration 
experience for Pi4J consumers.  

The Pi4J V.2 source code is available in this GitHub repository:  
[Pi4J V.2 GitHub Repository](https://github.com/Pi4J/pi4j-v2)  

```shell
git clone https://github.com/Pi4J/pi4j-v2
```

(Please note, this repository is only temporary, and the sources will be moved to the 
main Pi4J repo. Thus, any forks from this temporary repository will be broken after the move.)

Pi4J V.2 is still considered **EXPERIMENTAL** at this point. While many parts of the 
project are working, there are still a number of areas that require further development 
and certain APIs are subject to change without notice. A significant portion of the code 
is presently undocumented and hardware integration testing is incomplete. It is not 
recommended to use Pi4J V.2 in any production workload at this time.

For a more detailed account of the project status, please see this page:  
[**About > Project Status**](/about/). 
