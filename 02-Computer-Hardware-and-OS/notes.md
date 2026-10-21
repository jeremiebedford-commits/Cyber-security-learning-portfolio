# Computer Hardware and Operating Systems

> Study notes transcribed from my personal learning document. These are works in progress, not verified technical guidance.

## How the computer works

The motherboard: acts as the nervous/skeletal system of the computer holding them together  
The CPU: is the brains executing instructions to the other parts  
The PSU(Power supply): is the heart and lungs sends power to the rest of the components  
RAM(Random acces memory for short term storage)  
Graphics cards: are the eyes converting digital info into visual  
SSD/HDD are the permanent memory  
Network adapter: allows communication between the computer and any other devices in the network  

## System booted

the power is pressed and the system sends a signal to the PSU which then starts sending power to the whole computer  
the BIOS/UEFI (Unified Extensible Firmware Interface) allows the components to start up  
the UEFI/BIOS now performs a self on test to make sure everything is working before turn on if not alarms will be sent  
The bootup starts from a priority list  
After the bootup is done its moves to the RAM to later be forgotten  

## Os

Layers of permission to the main computer system  
Kernel space: The privileged, locked-down core of the OS. This is where the kernel, the part of the operating system that directly manages hardware and system resources, runs. It has unrestricted access to the CPU, memory, storage, and all hardware components.  
User space: Where all standard applications run. Applications in the user space are deliberately prevented from accessing hardware directly. Whenever they need to open or save a file, play a sound, or connect to Wi-Fi, they must make a system call and request that the kernel act on their behalf.  
