---
id: generic-commands-reputation
title: Generic Reputation Commands
---


## Background and motivation

XSOAR has an abudance of integrations with reputation providers for example VirusTotal, AlienVault OTX, MISP etc. 
Every Integration that returns a reputation about an indicator must implement the generic repuation commands and calculate [DBot Score](../dbot)

## Generic Reputation Commands needs to be supported

### **file**

**Description:** Runs reputation on a File.

### **ip**

**Description:** Runs reputation on an IP.

### **url**

**Description:** Runs reputation on a URL.

### **domain**

**Description:** Runs reputation on a Domain.

### **email**

**Description:** Runs reputation on an Email.

### **cve**

**Description:** Runs reputation on a CVE.


## Integrations for reference

[AutoFocus](https://github.com/demisto/content/tree/master/Packs/AutoFocus/Integrations/AutofocusV2) 
[MISP](https://github.com/demisto/content/tree/master/Packs/MISP/Integrations/MISP_V2)
[DeHashed](https://github.com/demisto/content/tree/master/Packs/DeHashed/Integrations/DeHashed)