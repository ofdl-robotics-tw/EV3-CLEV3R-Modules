# OFDL EV3 CLEV3R Modules
![image](https://github.com/ofdl-robotics-tw/EV3-CLEV3R-Modules/assets/17724013/78f696ac-4754-4451-a845-948c0143ae47)


This is a universal modules made by the OFDL team for [CLEV3R IDE (EV3 Basic Plus)](https://clev3r.ru/), which allows users to read information from various commonly used (Yuh I mean WRO and FLL :-D) sensors through the module.

Basiclly 90% of our OFDL EV3-G Blocks function has been convert to BASIC, the BASIC have faster speed (3x faster) to execute the program and reading sensor, with our modules can help you write BASIC faster and more conveniently.

## How to use?
1. Please download [CLEV3R IDE](https://clev3r.ru/), and extract to the path you want to save ( recommend C:\ or D:\ )
2. Copy the help folder(the one you download here) to the root directory of CLEV3R (the folder have Clever.exe) and replace the existing files/folder.
3. Run CLEV3R IDE and associate the file extension.
4. Open the Main_test.bp and have fun!

Notice: Unlike EV3-G blocks, when you need the module in your program, you need to copy the module folder (Sensors, Tool...etc) to your program path, of course you can just copy the module(bpm) you need.

## Manual or Helps
Please refer to the Help panel in the CLEV3R IDE.

## Support Sensors
1. EV3 Color Sensor
2. EV3 Color Sensor (Normalization Light mode)
3. EV3 Gyro Sensor
4. EV3/NXT Ultrasonic Sensor
5. EV3/NXT Touch Sensor
6. NXT Color Sensor (9694-1) (Normalization Light mode support)
7. NXT Light Sensor (9844) (Normalization Light mode support)
8. HiTechnic Color Sensor V2
9. HiTechnic IRSeeker V2
10. HiTechnic Compass Sensor
11. Pixy2 Camera
12. SPIKE/RI Color Sensor (TBD)
13. SPIKE/RI Force Sensor (TBD)
14. SPIKE/RI Ultrasonic Sensor (TBD)
15. HuskyLens Camera (TBD)
16. OpenMV Camera (TBD)
17. MindSensors series Sensor (TBD)

## Movement module (Algorithm part)
1. PD Controller
2. Sync Controller
3. ACC Controller

## Tools module (Useful ToolBox Block BASIC version)
1. getArrayMaxMin()
2. select()
3. constrain()
4. wrap()
5. map()
6. atan2()

## License
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Copyright (C) 2023 OFDL Taiwan
-   Licensed under the GNU General Public License v3.0 (the "License").
-   You may not use this project or any file except in compliance with the License.
-   You may obtain a copy of the License at [https://www.gnu.org/licenses/#GPL](https://www.gnu.org/licenses/#GPL).

👍And Thanks to the Author of CLEV3R: [CLEV3R-Github-Repos](https://github.com/iCheh/Clev3r-1)
