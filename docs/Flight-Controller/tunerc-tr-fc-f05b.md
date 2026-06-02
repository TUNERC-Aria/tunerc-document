# POLY Document

## Hardware Versions
The POLY currently has multiple hardware versions. You can identify the specific version by checking the silk-screen printing (marking) on the PCB. The differences are as follows:
#### Silk-screen: **22W12** or **22W19**  
Description: The PCB color is black, and the silk-screen marking is usually 22W19. This iteration was sold from May 2022 to June 2024. It stands as the first official retail version and is commonly referred to as V1.1 or the Original Version.
#### Silk-screen: **24W26**  
Description: The PCB color is green, with "24W26" and "POLY F405 1.2" printed on the back of the board. This iteration was sold from July 2024 to April 2026.  
Compared to the previous version, it features the following improvements:  
1. Enlarged power pads for easier soldering.  
2. Significantly improved current meter accuracy. The current scale (ammeter scale) has been adjusted from 45.3mV/A in the previous version to 50.0mV/A.  
3. Resolved the bootloader issue from the previous version, where pressing the boot button would occasionally fail to enter boot mode.  
4. Increased Flash memory from 4M Byte to 8M Byte.  
5. Upgraded the 3.3V LDO.  
6. Upgraded the UART4 signal inverter. The new inverter operates automatically when required, eliminating the need for bridging the jumper pads. It also delivers superior performance and functions without causing any interference or negative impact on connected non-inverted (normal signal) devices.  
#### Silk-screen: **26W17** 
Description: The PCB color is green, with "26W17" and "POLY F405 1.3" printed on the back of the board.  
Compared to the previous version, it features the following improvements:  
1. Optimized the 5V BEC to deliver lower electrical noise and enhanced stability.  
2. Modified the package of certain components.  
