# High Frequency Magnetic Loop Antenna Auto-Tuner for Amateur Radio

**PLEASE NOTE THIS REPOSITORY IS BEING UPDATED TO VERSION 2**

This is the repository for a magnetic loop antenna controller which is patterned after a design published in the book "Microcontroller Projects for Amateur Radio" by Jack Purdum W8TEE and Albert Peter AC8GY.  The author's firmware for the antenna controller was developed in the Arduino IDE.  The book includes a detailed information and a detailed construction guide for both the antenna and the controller.

This derivative design replaces the STM32 ''Blue Pill'' controller module with a Raspberry Pi Pico.  I noticed the Pi Pico was very similar in size to the STM32 board, and had the necessary GPIOs and ADC (Analog to Digital Converter) to perform the same function as the Blue Pill board.  Another reason to use the Pi Pico is that it has not been affected by ``supply chain'' problems which have plagued other electronic endeavors.  

The project's firmware was developed using Visual Studio Code and the Pi Pico C/C++ SDK.  A future branch may support the Arduino IDE.

# Documentation

**Documentation for Version 2 in progress and will be uploaded soon.**

Included in this repository is the file "magloop_pico_book.pdf" which includes sufficient information to construct both the controller and a single-loop antenna.

Included within this respository are five submodules which include the design data for the project, including printed circuit board and 3D printing files.

Use these commands to clone this repository and the submodules:

git clone https://github.com/Greg-R/magloop_pico_project  
cd magloop_pico_project  
git submodule update --init  

Use these commands to update the project:

cd magloop_pico_project  
git pull  
git submodule update  




