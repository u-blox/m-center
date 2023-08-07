# power_management

This directory contains power management scripts

There are two types of script, one uses PSM and the other powers off the module.

For each type you have the option of using QoS: 1 with Acknowledgement or QoS: -1 with no acknowledgement, but with the added benefit of not needing to connect to the broker first. 


| **Script** | **Description** | **Modules** |
| :---  | :---  | :---  |
| `powerMng_saraR5_lpwa_first_configuration_psm_advanced` | This script has the purpose to configure the cellular device after cold booting. This script waits for registration and then configures PSM, +UPSV. It turns off Auto-Bauding and sets the greeting message. The greeting message is used for the publish script to know when the module has been turned on. | SARA-R510-01B |
| `powerMng_saraR5_lpwa_first_configuration_pwr_off_advanced` | This script has the purpose to configure the cellular device after cold booting. This script waits for registration and then configures +UPSV. It turns off Auto-Bauding and sets the greeting message. The greeting message is used for the publish script to know when the module has been turned on. | SARA-R510-01B |
| `powerMng_saraR5_lpwa_wake_up_and_publish_QoS-1_pms_advanced` | This script is used to publish a message to the Thingstream MQTT-Anywhere IoT Platform using QoS: -1. | SARA-R510-01B | 
| `powerMng_saraR5_lpwa_wake_up_and_publish_QoS-1_pwr_off_advanced` | This script is used to publish a message to the Thingstream. | SARA-R510-01B | 
| `powerMng_saraR5_lpwa_wake_up_and_publish_QoS1_psm_advanced` | This script is used to publish a message to the Thingstream. | SARA-R510-01B |
| `powerMng_saraR5_lpwa_wake_up_and_publish_QoS1_pwr_off_advanced` | This script is used to publish a message to the Thingstream. | SARA-R510-01B |
