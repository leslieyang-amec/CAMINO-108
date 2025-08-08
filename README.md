# CAMINO-108
CAMINO-108

Download page
https://github.com/leslieyang-amec/CAMINO-108/releases

| Date | Firmware Version | Description of changes |
| -- | -- | -- |
| 2025-08-06 | 1.2.8.14 | - NMEA 2000 fast packet sequence ID with incorrect order under CAN bus heavy loading.</br> - Fix NMEA0183 GNSS data output format cannot change to NMEA 0183 V4.0 format.</br> - Fix NMEA 2000 PGN 60928, when the destination ID is 252 ~ 254 will still process the message issue.</br> - NMEA 2000 PGN 129029, GNSS position data, altitude no data. |
| 2024-07-30 | 1.2.8.13 | Support output NMEA 0183 GNSS satellite system information about Galileo and BeiDou. |
| 2024-03-22 | 1.2.8.12 | Fixed the bug that the device has abnormal rebooting itself on the date of February 29th in a leap year (2024, 2028, etc.) |
| 2023-07-14 | 1.2.8.11 | Fix the issue that, when use external GNSS data, ship dimensions will become all 0. |
| 2020-10-28 | 1.2.8.09 | * Add GNSS system’s configuration-setting support for Galileo and BeiDou selection.<br/>* When NAIS-500 is powered by USB only, the device will output following NMEA 0183 sentence every 5 second:<br/>$PAMC,R,TXT, The transceiver is in lower power, Tx stop*2D |


