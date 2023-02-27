# Destription
This repository is a meta-repo for the Scout project code.  This exists only to aggregate the repos in one place.  The actual repos are git modules and refer to their own repositories.


## Repository descriptions

| Repository | Description |
|------------|-------------|
| paikea-firmware | Micropython modules for the microcontrollers.  All microcontrollers use the same module repo |
| paikea-device-server | A websocket server to communicate between devices and the device webpage |
| paikea-micropython-heltec | micropython customization patch for the fs-corruption issue |
| paikea-pcb | schematics and fabrication outputs for pcbs |
| paikea-server-backend | Backend server which handles messaging and serves up the front-end pages |
| scout-firmware-binaries| Micropython binary files to flash on the microcontrollers used in the buoy and handset |

See the README in each repository for details
