---
layout: page
title: Welcome 
tagline: 
---
{% include JB/setup %}

###Source
[Available on Github](https://github.com/PracticalMaker/ARO-MicrOS)

###  Commands
1. [configureise](/configureise.html)
  - This command is used for configuring Ion Specific Electrodes (ISE). You would use this command to configure pH, Nitrate, ORP etc. probes
2. [readise](/readise.html)
  - This command uses the configuration data from configureise and returns a value. Use this to read pH, Nitrate, ORP etc. probes
3. [identify](/identify.html)
  - This command will return a unique ID for the device. This isn't really used on the device currently, but is useful for external communication routing