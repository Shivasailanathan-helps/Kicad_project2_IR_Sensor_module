# Kicad_project2_IR_Sensor_module
A compact, 2-layer Infrared (IR) Obstacle Detection Sensor Module designed in KiCad using the LM358 op-amp. Features a hybrid THT/SMD component layout, adjustable sensitivity potentiometer, dual ground planes, and production-ready Gerber files for robotics and proximity sensing applications.

## Description:
This repository holds the hardware design files for a compact, two-layer Infrared (IR) Obstacle Detection Module created in KiCad. Tailored for autonomous mobile robots, line-following buggies, and industrial proximity sensing, the module utilizes an analog comparator circuit based on the LM358 operational amplifier to translate optical reflections into clear digital outputs.

The schematic features a dual-diode optical front end paired with a calibrated voltage reference network. A 5mm IR emitting diode continuously projects light onto the target area, while a reverse-biased photodiode monitors the reflected radiation. The resulting analog voltage feeds the non-inverting input of the LM358 comparator. An onboard Bourns 3296W multi-turn vertical potentiometer allows precise threshold voltage tuning at the inverting input, ensuring reliable calibration across different surface colors, textures, and ambient light levels.

The double-sided FR4 PCB implementation uses a hybrid THT and SMD component selection strategy to balance mechanical durability with spatial efficiency. Through-Hole (THT) footprints are assigned to the optical pair and the potentiometer, ensuring superior resistance to physical strain during adjustment and allowing easy alignment of the optical lenses. Surface-Mount Device (SMD) 1206 footprints are chosen for passive resistors and the output status indicator LED, keeping the overall footprint minimal, reducing drill-hole counts, and freeing copper routing channels.

Key PCB layout details include filled ground planes on both top (F.Cu) and bottom (B.Cu) copper layers to minimize noise, thermal relief connections on grounded pads for effortless hand-soldering, and clean under-IC via transitions (F.Cu to B.Cu) to route traces beneath the DIP-8 footprint without external jumpers. Power and signal connections are exposed through a standard 3-pin 2.54mm pitch header (+5V, GND, OUT) for seamless integration with microcontrollers like Arduino, STM32, or ESP32. The repository contains full KiCad schematic and board design files, Gerber production outputs, and 3D render preview assets for immediate hardware fabrication and prototyping.

##Outputs:
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/220d3b01-5ae7-4675-8459-1f7196c16243" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/619d8349-228f-4571-8f91-5a8bad928d41" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/4c6baba7-9fa6-411a-8952-8adddf3f59bd" />
<img width="1600" height="902" alt="image" src="https://github.com/user-attachments/assets/a98c2c46-62ac-48ea-80c7-10b1afa58524" />
<img width="1600" height="891" alt="image" src="https://github.com/user-attachments/assets/ff84fe27-0cfa-4e4d-9741-06e9a27727ee" />
<img width="1305" height="604" alt="image" src="https://github.com/user-attachments/assets/430216a8-53e4-4230-9262-2557f3ea3dd9" />





