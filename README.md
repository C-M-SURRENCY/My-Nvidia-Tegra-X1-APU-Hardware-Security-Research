# My-Nvidia-Tegra-X1-APU-Hardware-Security-Research
This repository documents and provides the accompanying code for my hardware security research project focused on the NVIDIA Tegra X1 (T210/T214) System-on-Chip (SoC).

![1764306568650](https://github.com/user-attachments/assets/8b5ca193-82f9-4ab1-a928-500a9c3f5cae)

This is a picture showing the hardware glitching setup used during the Tegra X1 secure-boot research. Several fine wires are soldered to key pads on the APU package, routing signals to the Raspberry Pi Pico and the transistor-based switching stage (based off of a previous design of mine for a laser module driver). This wiring allowed precise voltage-fault injection during the boot sequence, forming the core of the fault-testing process. 
