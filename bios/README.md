# Dell XPS 13 9360 System BIOS

## Changelog

### 1.3.2

* Improved the USB 3.0 to LAN Stability
* Correct the ThunderBolt / USB Option in BIOS Setup Menu

### 1.3.5

* Updated Intel ME Firmware to address security advisory CVE-2017-5689 / INTEL-SA-00075

### 2.3.1

* Enhance system stability

### 2.4.2

* Updated the handling of physical presence checks in firmware.
* Updated the handling of pre-boot authentication information by firmware.
* Updated UEFI variable input validation.
* Updated the handling of 3rd party Option ROM loading.
* Updated SPI flash command configuration settings.
* Optimize CPU loading to Improve EE noise.

### 2.5.1

* Updated Intel ME Firmware to address security advisories INTEL-SA-00086 (CVE-2017-5705, CVE-2017-5708, CVE-2017-5711 & CVE-2017-5712) & INTEL-SA-00101(CVE-2017-13077, CVE-2017-13078 & CVE-2017-13080)
* Update to the latest CPU microcode to address CVE-2017-5715 and associated Intel Reboot issue

### 2.6.2

* Fixed incorrect Windows operating system logon message.
* Enhanced SMM Security Mitigation feature.
* Updated Embedded Controller Engine Firmware.
* Updated Realtek USB LAN firmware.

### 2.7.1

* Improve startup stability when the RTC battery voltage is low
* Support eGFX devices

### 2.8.1

* Updated Intel ME Firmware to address security advisories INTEL-SA-00112 (CVE-2018-3628 CVE-2018-3629 CVE-2018-3632) & INTEL-SA-00118(CVE-2018-3627)
* Updated CPU microcode to address security advisory Intel Security Advisory INTEL-SA-00115 (CVE-2018-3639 & CVE-2018-3640)

### 2.9.0

* Update Intel ME Firmware to address security advisories INTEL-SA-00125 (CVE-2018-3655), Intel-SA-00131 (CVE-2018-3643 CVE-2018-3644) & INTEL-SA-00141 (CVE-2018-3657 CVE-2018-3658 CVE-2018-3616)
* Fixed a potential system hang issue when an incorrectly formatted password is
  entered at the BIOS Security Manager (BIOS pre-boot password) prompt.
* Enhance Killer Wifi stability.
* Added TPM PPI Bypass for Clear Command support.

### 2.10.0

* Added BIOS Password Feature: Master Password Lockout.
* Enhanced the stability of Linux operating system.
* Fixed the issue where random programs launch unexpectedly when multiple keys
  are pressed together.
* Improved keyboard typing experience for users.

### 2.11.0

* Fixed an issue with Secure Boot Option ROM Signature Verification.
* Firmware updates to address security advisory INTEL-SA-00185 (CVE-2018-12188 CVE-2018-12190 CVE-2018-12191 CVE-2018-12192 CVE-2018-12199 CVE-2018-12198 CVE-2018-12200 CVE-2018-12187 CVE-2018-12196 CVE-2018-12185).
* Firmware updates to address security advisories INTEL-SA-00191(CVE-2018-12201, CVE-2018- 12202, CVE-2018-12203).
* Fixes the issue where the mouse lags when the Dell TB16 dock is unplugged or plugged in.
* Supports Dell Dock Station WD19.

### 2.12.0

* Firmware updates to address security advisory INTEL-SA-00213 (CVE-2019-0086, CVE-2019-0091, CVE-2019-0092, CVE-2019-0093, CVE-2019-0094 and CVE-2019-0096)
* Firmware updates to address security advisories INTEL-SA-00233(CVE-2018-12126, CVE-2018-12127, CVE-2018-12130 and CVE-2019-11091)
* Removed the pre-boot Intel RST Manager Optimized Defaults option.
* Fixed the issue where BitLocker may prompt for recovery if Auto Power On option in BIOS setup is set to wake up system at a specific time.

### 2.13.0

* Firmware updates to address security advisory INTEL-SA-00241 (CVE-2019-0169, CVE-2019-11088, CVE-2019-11104, CVE-2019-0131, CVE-2019-11090, CVE-2019-0166, CVE-2019-0168, CVE-2019-11087, CVE-2019-11101, CVE-2019-11100, CVE-2019-11106, CVE-2019-11132, CVE-2019-11131, and CVE-2019-11147).
* Firmware updates to address Intel security advisories INTEL-SA-00260 (CVE-2019-0154) and INTEL-SA-00254 (CVE-2019-0185).
* Firmware updates to address Intel security advisories INTEL-SA-00219 (CVE-2019-0117), INTEL-SA-00220 (CVE-2019-0123), and INTEL-SA-00270 (CVE-2019-11135).
* Fixed a BIOS Setup configuration issue that occurs after clearing the CMOS.
* Fixed an issue with preboot TPM detection and error logging.
* Removed the IpSec driver and application.
* Fixed the issue where the BitLocker prompts for recovery. It occurs when Auto Power On option in BIOS setup is set to wake up the system at a specific time.
* Added a new feature to automatically suspend BitLocker before upgrading the firmware. After the firmware upgrade is complete, BitLocker is automatically enabled.

### 2.14.2

* Firmware updates to address the Intel Security Advisories INTEL-SA-00289 (CVE-2019-11157) and INTEL-SA-00317 (CVE-2019-14607).
* Firmware updates to address security advisory INTEL-SA-00295 (CVE-2020-0531, CVE-2020-0532, CVE-2020-0534, CVE-2020-0535, CVE-2020-0536, CVE-2020-0537, CVE-2020-0538, CVE-2020-0539, CVE-2020-0540, CVE-2020-0541, CVE-2020-0542, CVE-2020-0594, CVE-2020-0595, CVE-2020-0596, and CVE-2020-8674).
* Firmware updates to address the Intel Security Advisory INTEL-SA-00322 (CVE-2020-0528 and CVE-2020-0529).
* Firmware updates to address the Intel Security Advisory INTEL-SA-00320 (CVE-2020-0543).
* Firmware updates to address the Intel Security Advisory INTEL-SA-00329 (CVE-2020-0548 and CVE-2020-0549).
* Firmware updates to address CVE-2020-5362.
* Firmware updates to address the Intel Technical Advisory INTEL-TA-00404 (CVE-2020-8758).
* Fixed the issue where the SMM Security Mitigation gets disabled while loading BIOS defaults.
* Fixed an issue with the hard drive master password reset not functioning.

### 2.15.1

* Firmware updates to address the Intel Technical Advisory INTEL-TA-00391 (CVE-2020-8753, CVE-2020-8745, CVE-2020-8705, CVE-2020-8757, CVE-2020-8756, CVE-2020-8760, CVE-2020-8751, CVE-2020-8754, CVE-2020-8747, CVE-2020-8746, CVE-2020-8749 CVE-2020-8752, CVE-2020-12303, CVE-2020-12355, and CVE-2020-12356).
* Firmware updates to address the Intel Security Advisory INTEL-SA-00358 (CVE-2020-0587, CVE-2020-0591, CVE-2020-0592, and CVE-2020-0593).
* Firmware updates to address the Intel Security Advisory INTEL-SA-00381 (CVE-2020-8696 and CVE-2020-8698).
* Firmware updates to address the Intel Security Advisory INTEL-SA-00389 (CVE-2020-8694 and CVE-2020-8695).
* Firmware updates to address the Intel Technical Advisory INTEL-TA-00473 (CVE-2020-24586, CVE-2020-24587, and CVE-2020-24588).

### 2.16.0

* Firmware updates to address the Intel Security Advisory INTEL-SA-00459 (CVE-2020-24507 and CVE-2020-8703).
* Firmware updates to address the Intel Security Advisory INTEL-SA-00464 (CVE-2020-24512).
* Firmware updates to address security vulnerabilities.

### 2.17.0

* Firmware updates to address security vulnerabilities.

### 2.18.0

* Firmware updates to address the Intel Security Advisory INTEL-SA-00562 (CVE-2021-0157).
* Firmware updates to address security vulnerabilities.

### 2.19.0

* Firmware updates to address security vulnerabilities.
* Firmware updates to address the Intel Security Advisory INTEL-SA-00527 (CVE-2021-0107, CVE-2021-0111, CVE-2021-0114, CVE-2021-0115, CVE-2021-0116, CVE-2021-0117, CVE-2021-0118, CVE-2021-0119, CVE-2021-0124, CVE-2021-0125, CVE-2021-0156).
* Firmware updates to address the Intel Security Advisory INTEL-SA-00532 (CVE-2021-0127).

### 2.20.0

* Firmware updates to address security vulnerabilities including (Common Vulnerabilities and Exposures - CVE) such as CVE-2019-14584, CVE-2021-28210, CVE-2021-28211, CVE-2022-21123, CVE-2022-21125, CVE-2022-21127, CVE-2022-21166, CVE-2022-0005, CVE-2022-21151, CVE-2022-0004 and CVE-2022-21181.

### 2.21.0

* Improved the stability of the system.

### Links

* [1.3.2][bios132]
* [1.3.5][bios135]
* [2.3.1][bios231]
* [2.4.2][bios242]
* [2.5.1][bios251]
* [2.6.2][bios262]
* [2.7.1][bios271]
* [2.8.1][bios281]
* [2.9.0][bios290]
* [2.10.0][bios2100]
* [2.11.0][bios211]
* [2.12.0][bios212]
* [2.13.0][bios213]
* [2.14.2][bios2142]
* [2.15.1][bios2151]
* [2.16.0][bios2160]
* [2.17.0][bios2170]
* [2.18.0][bios2180]
* [2.19.0][bios2190]
* [2.20.0][bios2200]
* [2.21.0][bios2210]

[bios132]: http://www.dell.com/support/home/nz/en/nzdhs1/Drivers/DriversDetails?driverId=4F61T
[bios135]: http://www.dell.com/support/home/nz/en/nzdhs1/Drivers/DriversDetails?driverId=8C84P
[bios231]: http://www.dell.com/support/home/nz/en/nzdhs1/drivers/driversdetails?driverId=JGCWT
[bios242]: http://www.dell.com/support/home/nz/en/nzdhs1/drivers/driversdetails?driverId=YFTT1
[bios251]: http://www.dell.com/support/home/nz/en/nzdhs1/drivers/driversdetails?driverId=FW1RC
[bios262]: http://www.dell.com/support/home/es/es/esdhs1/drivers/driversdetails?driverId=G05NR
[bios271]: https://www.dell.com/support/home/es/es/esdhs1/drivers/driversdetails?driverId=KXP8F
[bios281]: https://www.dell.com/support/home/es/es/esdhs1/drivers/driversdetails?driverId=8M0KH
[bios290]: https://www.dell.com/support/home/es/es/esdhs1/drivers/driversdetails?driverId=RCKDK
[bios2100]: https://www.dell.com/support/home/es/es/esdhs1/drivers/driversdetails?driverId=T7XJF
[bios211]: https://www.dell.com/support/home/nz/en/nzdhs1/drivers/driversdetails?driverid=R5TYT
[bios212]: https://www.dell.com/support/home/nz/en/nzbsd1/drivers/driversdetails?driverid=02gcf
[bios213]: https://www.dell.com/support/home/us/en/04/drivers/driversdetails?driverid=c9j4k
[bios2142]: https://www.dell.com/support/home/en-nz/drivers/driversdetails?driverid=0cy6w
[bios2151]: https://www.dell.com/support/home/en-nz/drivers/driversdetails?driverid=pc6h3
[bios2160]: https://www.dell.com/support/home/en-nz/drivers/driversdetails?driverid=v4581
[bios2170]: https://www.dell.com/support/home/en-nz/drivers/driversdetails?driverid=wfgmn
[bios2180]: https://www.dell.com/support/home/en-nz/drivers/driversdetails?driverid=dk08c
[bios2190]: https://www.dell.com/support/home/en-nz/drivers/driversdetails?driverid=3gght
[bios2220]: https://www.dell.com/support/home/en-nz/drivers/driversdetails?driverid=0h104
[bios2210]: https://www.dell.com/support/home/en-nz/drivers/driversdetails?driverid=xkrg8
