# location_features

This directory contains scripts for interfacing with u-blox GNSS modules, GNSS aiding features, location services (CellLocate, LCS, etc.).


| **Script** | **Description** | **Modules** | **Tested On** |
| :---:  | :---:  | :---:  | :---:  |
| `location_saraR5_saraR42_CellLocateFixOverTcp_basic` | This script has the purpose to demonstrate the use of CellLocate and sockets to send the received CellLocate location to a server using TCP connection. Script needs a valid CellLocate thingstream token and an activated internal context. Also a server_ip address is needed. | All products | LARA-R6, LARA-L6, SARA-R5, SARA-R42 |
| `location_saraR5_saraR42_aiding_advanced` | This script has the purpose to demonstrate the use of the GNSS chip Integrated into the modules. This script needs a "Start!" greeting message active on boot. The greeting text can be activated using the command AT+CSGT=1,"Start!" and using a fixed baud rate. | SARA-R510M8S, SARA-R422M8S | SARA-R510M8S, SARA-R422M8S |
| `location_saraR5_saraR42_aiding_advanced` | This script has the purpose to demonstrate the use of the GNSS chip Integrated into the modules. This script needs a "Start!" greeting message active on boot. The greeting text can be activated using the command AT+CSGT=1,"Start!" and using a fixed baud rate. | SARA-R510M8S, SARA-R422M8S | SARA-R510M8S, SARA-R422M8S |
| `location_saraR5_saraR42_gnssFixOverMQTT_basic` | This script has the purpose to demonstrate the use of the GNSS chip Integrated into the modules. This script needs a "+STARTUP" greeting message active on boot. The greeting text can be activated using the command AT+CSGT=1,"+STARTUP" and using a fixed baud rate.  | All products | SARA-R510M8S, SARA-R422M8S, SARA-R422M10S, SARA-R510S |
| `location_saraR5_saraR42_laraR6_gnssCellInfo_advanced` | The script retrives info about the mobile network status together with the GNSS position in which the info are collected. The script encapsuletes the info with two set strings in order to make the results easy to parse. | SARA-R5, SARA-R42, LARA-R6 | SARA-R5, SARA-R42, LARA-R6 |
