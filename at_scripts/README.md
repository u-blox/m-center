## Table of content ##

| **Folder** | **Description** |
| :---  | :---  |
| `audio` | This directory contains scripts releated to modems audio interfaces, devices audio tuning, eCall, DTMF and other tones. |
| `cell_modem` | This directory contains modem basic features (modem control, calls, SMS, IMS, data contexts, phonebook), concepts about cellular networks and 3GPP standards. Some of the areas we go through are: network related commands, testing CTS/RTS/DSR/DTR lines, read/write/edit/delete phone book, modem settings, testing SMS behavior, URC codes.|
| `common_lib` | This directory can be used if some reusable functions needs to be maintained separately for multiple scripts. Some of the functions you can find here are: sending AT commands, printing the date time variable, converting bitstream in string format to int type, logical operations, bit shift returns.|
| `debug-ability` | This directory contains scripts that have the general purpose to collect debug information from the target module or help configuring the target module. |
| `EVK` | This directory contains m-center scripts that are AT commands examples reported on the EVK user guide documents. |
| `firmware_update` | This directory contains firmware (FW) update-related scripts. |
| `internet_applications` | This directory contains m-center scripts related to the internet applications: such as TCP socket, UDP socket, HTTP app, LWM2M app and uFOTA app. Some of the areas we go through are: activate PSD profile, demonstrate a FTP/TCP/UDP connections, demonstrate the MQTT Anywhere service, demonstrate the use of internal HTTP application.|
| `local_connectivity` | This directory contains scripts for communication between modem and external devices scripts along with a script to demonstrate a basic file system read/write. |
| `location_features` | This directory contains scripts for interfacing with u-blox GNSS modules, GNSS aiding features, location services. Some of the areas we go through are: use of CellLocate, demonstrate the use of the GNSS chip Integrated into the modules.|
| `mno_certifications` | This directory contains MNO policies. Certification of end-devices related scripts. |
| `power_management` | This directory contains power management scripts. Some of the areas we go through are: configure the cellular device after cold booting and  interact with Thingstream MQTT-Anywhere IoT Platform. |
| `sim` | This directory contains scripts related to SIM cards, SIM chips and related features (SIM Toolkit, SAP). |
| `system_functionalities` | This directory contains AT Scripting related features, embedded filesystem (FS) and other system features. Some of the areas we go through are: identify the modem baud rate, test the basic File-system macros, test the filesystem integration and its functions, test different macro functionality on m-center, test the AT port macros, to open/close/send data on the module MUX channels, set trace parameters and start the trace, handle an USB reboot using specific "port" macro. |
