# MKS_Monster8v2_Ender5plus
Printer configuration file to install a MKS Monster8 v2 board in an Ender 5 Plus.

Note 1: Z-axis connections.
The Monster8 board has 9 connectors for 8 drivers. It has two sockets for Z-axis steppers that are connected together.  For separate dual Z-axis control, plug the second z-axis stepper motor into one of the spare extruder connectors and populate the corresponding driver socket. I used socket E1 and the printer.cfg file has the pin definitions for that setup.

Note 2: Bltouch. 
Connect the 3-pin BLtouch plug to the "3DTOUCH" connector. The 
2-pin plug from the BL-Touch goes to the Z-axis endstop connector.

Note 3: Set driver voltages. 
I used 0.8v for all steppers, but this requires adjustment based on the stepper type. If using UART mode you define the stepper motor current in the printer.cfg file.
