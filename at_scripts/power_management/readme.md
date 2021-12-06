# power_management

Abstract: Power management scripts.

LPWA - Publishing a MQTT-SN message via MQTT-Anywhere 

powerMng_saraR5_lpwa_wake_up_and_publish scripts require another script to be run first, to configure them module for the main script. This is the powerMng_saraR5_lpwa_first_configuration script

There are two types of script, one uses PSM and the other powers off the module.

For each type you have the option of using QoS: 1 with Acknowledgement or QoS: -1 with no acknowledgement, but with the added benefit of not needing to connect to the broker first. 