# EXPERIMENT--01-ALP-FOR-8086
### Name : ANISH RAJ P
### Register no : 212222230010
### Date of experiment : 13.08.2024

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


<img src='https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png' width=50%>












9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)









10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






<img src='https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png' >

## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AL,74H
MOV BL,69H
ADD AL,BL
HLT
```
## Output  
<img src='https://github.com/lisianathiruselvan/EXPERIMENT--01-ALP-FOR-8086/assets/119389971/d10c9662-401a-4f39-a50a-22e730c823d5' width=50%>

## Subtraction   of 8 bit numbers  ALP 
```
MOV AL,84H
MOV BL,63H
SUB AL,BL
HLT

```
## Output 
<img src='https://github.com/lisianathiruselvan/EXPERIMENT--01-ALP-FOR-8086/assets/119389971/a13930e9-005d-4312-a867-011ec465b22d' width=50%>

## Multiplication alp 
```
MOV AL,75H
MOV BL,32H
MUL BL
HLT
```
 ## Output  
<img src='https://github.com/lisianathiruselvan/EXPERIMENT--01-ALP-FOR-8086/assets/119389971/61272bcc-5773-42d6-800c-ba2c15f796b0' width=50%>

## DIVISION of 8 bit ALP
```
MOV AL,68H
MOV BL,18H
DIV BL
HLT
```
## Output 
<img src='https://github.com/lisianathiruselvan/EXPERIMENT--01-ALP-FOR-8086/assets/119389971/1f20576c-3f1f-4d33-9252-abf5f7acc44f' width=50%>

## AND of 8 bit ALP
```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
## Output
<img src='https://github.com/lisianathiruselvan/EXPERIMENT--01-ALP-FOR-8086/assets/119389971/da0ec872-95ff-4d75-8923-6c8d2f002739' width=50%>

## OR of 8 bit ALP
```
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```
## Output
<img src='https://github.com/lisianathiruselvan/EXPERIMENT--01-ALP-FOR-8086/assets/119389971/fa599619-17bc-416a-b662-94c2197c0c42' width=50%>

## NOT of 8 bit ALP
```
MOV AL,65H
NOT AL
HLT
```
## Output
<img src='https://github.com/lisianathiruselvan/EXPERIMENT--01-ALP-FOR-8086/assets/119389971/7ca3fde6-6b68-44c7-a4e6-3fb8e2ec15e9' width=50%>

## XOR of 8 bit ALP
```
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```
## Output
<img src='https://github.com/lisianathiruselvan/EXPERIMENT--01-ALP-FOR-8086/assets/119389971/3c2e879d-70a2-4bbb-bc5f-ce2e1a5d83c4' width=50%>

## Result :
Thus, A Program Is Develope To Write And Execute ALP On Fundamental Arithmetic And Logical Operations.
