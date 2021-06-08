# LinearVariableStiffnessHoneycomb

![SetupPhotoExp](https://user-images.githubusercontent.com/63325614/121165913-71712700-c872-11eb-8d9a-d0bc4e8ffad9.jpg)

This repository contains files of different types and extensions related to my project "Linear Negative Stiffness Honeycomb Actuator with Integrated Force Sensing".

T. Galimzhanov, A. Zhakatayev, R. Kashapov, Z. Kappassov and H. A. Varol, "Linear Negative Stiffness Honeycomb Actuator with Integrated Force Sensing," 2020 IEEE/ASME International Conference on Advanced Intelligent Mechatronics (AIM), 2020, pp. 1589-1594, doi: 10.1109/AIM43001.2020.9158855.

The code was designed and tested in Microsoft Visual Studio.

The "Source.cpp" file is an example of a working code. All the other variations of the codes are presented in the "Scripts" folder.
They are presented in txt format so you will only need to copy-paste them to your source code. 

Also it is very important to properly install the Dynamixel and Daq libraries for C.

The "ForceSensor.zip" file contains schematic project of designed PCB to acquire data from the CGQ-MH Load Cell.
The "PCB_Magnet_sensor_linear.zip" file contains the schematic project of designed PCB to acquire data from magnetic sensor AD22151, Analog Devices.
All PCB schematic projects were made in Altium Designer software.

The "PrintedParts.zip" file contains .cad/.stl files of all parts and details involved in project. All the files were designed in SolidWorks software and printed with Ultimaker 3D printer using polylactide (PLA) material.

The link to the paper based on this project: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9158855

For Dynamixel library this link will be useful: http://emanual.robotis.com/docs/en/software/dynamixel/dynamixel_sdk/library_setup/c_windows/#c-windows

For using NI-DAQ in different softwares NIDAQMX will be usefull:
https://www.ni.com/ru-ru/support/downloads/drivers/download.ni-daqmx.html#333268

Extra: The "3Axial_magnetic_field_sensor" file contains the schematic project of designed PCB to acquire data from magnetic sensor MLX90333, Melexis. This information may be useful for follow-up projects.
