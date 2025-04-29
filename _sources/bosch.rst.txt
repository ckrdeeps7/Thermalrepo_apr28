.. index:: Bosch

Bosch Scope
===========

VIP
---

The power master is located on the VIP. This processor is connected to battery power and handles power switching for all purposes.

OS: AUTOSAR (Vector MICROSAR)
-----------------------------

Bosch will implement **SystemManager** module, **PowerManager** module and **VoltageMonitor** sub-module. 

ASIL components for SoC state supervision and critical voltage monitoring, as described in detail by the SafteyApps concept, will have connections to System Manager and Power Manager module.

**EcuM/BsWM** These are AutoSAR stack components which together act as power state controller for the VIP AutoSAR domain. They maintain the ECU states based on their interaction with two sub-controllers, namely the SUM_SUSD and SysMgr, and broadcast relevant changes to all AutoSAR components. 

**SystemManager** is response to coordinate low level sequences utilizing Bosch service SW modules.
