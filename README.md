# Mobilithon

## Accounts
IoT Services account
* M2X account
* Control Center Account
* MBED account

1. create StarterKit flow and M2X device

2. compile binary in MBED
  * change server, URL and device name

3. activate the SIM on http://starterkit.att.com/app/sim-cards
  * make sure the SIM card status is "Activated"

4. Initial HW setup
  * make sure the development board (NXP FRDM-K64F) is running the 0226 FW from [MBED](developer.mbed.org/handbook/Firmware-FRDM-K64F) Do not follow the link to [NXP](http://www.nxp.com/products/software-and-tools/run-time-software/kinetis-software-and-tools/ides-for-kinetis-mcus/opensda-serial-and-debug-adapter:OPENSDA?tid=vanOpenSDA#FRDM-K64F), I was unable to flash that FW.
  * make sure cellular shield is running latest FW - 11.50.164451 as of 3/26/2017. Install the HW driver, and connection manager and check the version on Firmware tab of Connection Manager. https://starterkit.att.com/tutorials/cellular-shield-firmware-upgrade
 
5. Assemble the kit

6. Upload the code

7. Install terminal SW and watch debug output
  * don't forget to change speed to 115200
