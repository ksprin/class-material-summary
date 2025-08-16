# class-material-summary
Due to UVA policy I can not post my work items from some of my courses. I provided a summary of what I have done in courses where I built more complex projects, but am not able to post them publicly, below.

# ECE 3430 Intro to Embedded Computer Systems
Class Items
* Worked with Embedded C to program a STM32G071 Microcontroller
* Used STM32CudeIDE
* Used HAL and LL libraries
* Configured GPIO Pins for input, output, UART, SPI, IC2, Serial Memory
* Reading/Writing to Registers
* Interrupt and Polling Based Finite State Machines
* Used Internal Timers
* Configured ADC and DAC

Project Descriptions
* Real Time Signal Processing: I designed a program for a STM32G071 that collected analog sensor data and converted it with the ADC, stored that data in external serial flash data using a custom memory map to connect virtual address to physical ones, communicated with one memory device with SPI and the other with I2C, and finally the signal was converted back to analog with the DAC and output. 
* Decoder: I designed an interrupt-based Finite State Machine to decode a 2-bit quadrature encoded signal with a STM32G071. Both the level and frequency of the input signals were considered to determine an output. When the signal was determined to be clockwise it output low, and high for counter clockwise. 

# ECE 2600 Electronics
* Designed, built, and tested circuits on a breadboard
* Verified physical circuits with an AD2 and WaveForms
* Modeled circuits with Multisim (SPICE based software)

# ECE 2330 Digital Logic Design
* Used VHDL and schematic capture to build digital circuit designs
* Symbolic Circuit Analysis 
* Formatted results with canonical forms
* Decoders, Encoders, Multiplexer
* Minimization Theorems
* Karnaugh Maps
* Combinational and Sequential Systems
* Digitally designed, built, and tested a CPU, including the operation decoder, instruction sequencer, control signals logic unit, and a datapath with an ALU.



# CS 3130 Computer Systems and Organizations II
Class Items
* C Programming
  * Created and Utilized Makefiles
  * Memory Management
  * Created user defined signal handlers
  * Created multi-threaded programs
  * Avoiding Race Conditions with Locks
* Worked in a Linux Environment
  * User Management with the POSIX standard
* Caches
* Network Layers

Project Descriptions
* Implemented a multi-level page table data structure in C that maps virtual address to simulated physical address
* Used Valgrind to analyze cache performance 

# CS 3710 Introduction to Cyber Security
* Used a variety of cyber security tools within a Kali Linux environment
  * Linux Networking Tools (ping, nslookup, dig…)
  * Network Scanning with nmap
  * Packet Analysis with Wireshark
  * Network Traffic Analysis with Snort
  * Symmetric and Asymmetric Key Cryptography
* Developed own implementation of a RSA algorithm
* Malware Analysis Techniques
* Dynamic and Static Code Analysis tools

