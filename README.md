This project is a PCB design for controlling a Liftmaster gate operator from Home Assistant. 

The PCB design was done in KiCad 8.0, which is an open source electronic design tool. This project includes all of the KiCad project files so that you can modify the PCB if needed. I've also included a GERBER.ZIP file that can be used to simply have the PCB printed by someplace like JLPCB.

This project includes a bill of materials with URLs for all the parts necessary to build the board. I've sourced the part from DigiKey and Amazon.

The integration of the gate controller into Home Assistant is accomplished using ESPHome. This project includes the YAML file necessary to build and flash the firmware into the gate controller. You'll need to edit the YAML file and change the lines specified to customize to your environment.

This project includes datasheets for every component used on the gate controller board.

The gate controller board uses an ESP32-WROOM-32U microcontroller. This variant of the ESP32 uses an external antenna to improve the Wifi connectivity.
