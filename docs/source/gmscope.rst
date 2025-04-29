.. index:: GM scope

GM Scope
=========

VIP
---
 
GM will own the SW components which built the main and central VCU Statelogic and co-ordinate with SW parts on the SOC.

OS: AUTOSAR (Vector MICROSAR)
-----------------------------

**SystemStateController**
Determine and manage the system-state and propagate these to the state consumers in RTOS and Android.

**SoC PLC State Controller**
Determine and manage the power-state of the VCU and propagate these to the state consumers in RTOS and Android.

**SUM_SUSD**
SUM_SUSD is the StartupShutdown submodule of GM's standard-utility-module library, coordinating the applicationst in terms of startup/shutdown with the underlying Autosar standard BSW modules and the StateControllers.
