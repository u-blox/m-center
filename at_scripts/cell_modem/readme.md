# cell_modem

 This directory contains modem basic features such as: modem control, calls, SMS, IMS, data contexts, phonebook along with concepts about cellular networks, 3GPP standards.


| **Script** | **Description** | **Modules** |
| :---  | :---  | :---  |
| `cell_all_hexCmd_networkReg_basic` | The scope is to test the network registration using SENDHEX() macro. | All Products |
| `cell_all_hfc_ctsrts_basic` | The scope is to test the flow control line status using CTS and RTS lines.| All Products  |
| `cell_all_hfc_dsrdtr_basic` | The scope is to test the flow control line status using DSR and DTR lines.| All Products  |
| `cell_all_network_genericCommands_basic` | The scope is to test network related generic commands.| All Products  |
| `cell_all_network_registrationCommands_advance` | The scope is to test network related advance commands.| All Products  |
| `cell_all_network_urc_advance` | The scope is to test the network registration with URC using AT scripting macros.| All Products  |
| `cell_all_phoneBook_functionality_advance` | The scope is to read, write, edit, delete phone book. | All Products  |
| `cell_all_readNameAndFirmware_basic` | The scope is to read modem name, firmware version and submodule series. | All Products  |
| `cell_all_registrationTime_basic` | The scope is to measure the time elapsed for the network registation. Some initial configurations are necessary in order to run the script. | All Products  |
| `cell_all_settings_genericCommands_basic` | The scope is to check a few settings of the modem. | All Products  |
| `cell_all_sms_functionality_PDU_advance` | The scope is to test the SMS behavior in PDU mode with set character GSM 7-bit and proper connected SIM and antenna. The script first reads and deletes the first message (number #0) in the list. After that it sends a new PDU message and display all the messages in PDU mode. The operations is repeated a number of times  equal to the parameter "loop-count". | All Products  |
| `cell_all_sms_functionality_advance` | The scope is to test the SMS behavior with proper connected SIM and antenna. | All Products  |
| `cell_all_startup_genericCommands_basic` | The scope is to send some AT commands that are sent on startup. | All Products  |
| `cell_all_urc_configuration_basic` | The scope is to properly set the unsolicited result code (URC) indications in u-blox devices. When a unsolicited configuration is not supported by the target module, an error is received and the script continues | All Products  |