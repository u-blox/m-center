# internet_applications

This directory contains all m-center scripts related to internet applications.


| **Script** | **Description** | **Modules** |
| :---  | :---  | :---  |
| `ipApp_all_activatePsdProfile_basic` | This script has the purpose to activate PSD profile. | All Products |
| `ipApp_all_continueSocketEchoTest_advance` | This script has the purpose to continuously test a UDP socket connection with an ECHO server test. | All Products |
| `ipApp_all_EchoStatsCollector_advance` | This script has the purpose to measure RTT and PLR computed performing ping ECHO request on a test server. The module must be connected to internet and the internal context must be activated. | All products |
| `ipApp_all_ftpClientTest_basic` | This script has the purpose to demonstrate a FTP client connection to specific server. The module must be connected to internet and the internal context must be activated. |
| `ipApp_all_socketCongestionAvoidance_advance` | This script has the purpose to demonstrate a TCP socket connection with congestion avoidance by monitoring the TX queue. The module must be connected to internet and the internal context must be activated. | All products supporing +USOCTL option 11 |
| `ipApp_all_socketCongestionTest_basic` | This script has the purpose to test and demonstrate a TCP socket connection with congestion and respective handling. The module must be connected to internet and the internal context must be activated. | All products |
| `ipApp_all_socketEchoTest_advance` | This script has the purpose to demonstrate a TCP/UDP socket connection with an ECHO server test. The module must be connected to internet and the internal context must be activated. | All products |
| `ipApp_all_tcpUdpDataTest_basic` | This script has the purpose to test TCP and UDP data connections. | All Products |
| `ipApp_laraR6_httpDemo_basic` | This script has the purpose to demonstrate the use of internal HTTP application available in u-blox LARA-R6. | LARA-R6 |
| `ipApp_laraR6_thingstreamDualApnDemo_basic` | This script has the purpose to demonstrate the activation of two differnt APNs at the same time. Thingstream IoT SIM card is required for the correct execution of this script. APN "TSUDP" is used for  the MQTT Anywhere service provided by u-blox Thingstream. While, APN "TSIOT" is used to perfom generic data traffic. | LARA-R6 |
| `ipApp_lenaR8_httpDemo_basic` | This script has the purpose to demonstrate the use of internal HTTP application available in u-blox LENA-R8. | LENA-R8 |
| `ipApp_saraR5_awsExpressLinkDemo_basic` | This script has the purpose to demonstrate the MQTT use for communication between the u-blox SARA-R510AWS module and the AWS server. As an application's example, it simply sends 10 times the time to the AWS server. | SARA-R510AWS |
| `ipApp_saraR5_saraR42_FTP_retrieve_basic` | This script has the purpose to present a simple FTP retrieve. Some configurations, such as FTP server address, username and password must be set. The module must be connected to internet and the internal context must be activated. | SARA-R5, SARA-R42 |
| `ipApp_saraR5_saraR42_mqttAnywhereDemo_basic` | This script has the purpose to demonstrate the MQTT Anywhere service provided by u-blox Thingstream. Thingstream IoT SIM card is required for the correct execution of this script. | SARA-R5, SARA-R42 |