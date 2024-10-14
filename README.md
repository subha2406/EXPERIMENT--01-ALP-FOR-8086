# EXPERIMENT--01-ALP-FOR-8086
Name : Subha Shree U
Roll no : 2305002025
Date of experiment : 27-08-2024





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


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 

MOV AL,74H
MOV BL,69H
ADD AL,BL
HLT

## Output  
![image](https://github.com/user-attachments/assets/4fc9da5d-60db-4d81-8ba2-5579486e13e9)

 
## Subtraction   of 8 bit numbers  ALP 
MOV AL,84H
MOV BL,63H
SUB AL,BL
HLT
 
## Output  
![image](https://github.com/user-attachments/assets/af5845ac-2226-4f5f-a035-c8f0d1a804c1)

## Multiplication alp 
MOV AL,75H
MOV BL,32H
MUL BL
HLT

 ## Output  
 
![image](https://github.com/user-attachments/assets/8e040b27-2e36-4363-8d24-9b0a35342968)


## Division alp 
MOV AL,68H
MOV BL,18H
DIV BL
HLT


## Output  
![image](https://github.com/user-attachments/assets/e679dce3-c978-487f-be77-d6396de305eb)

## AND of 8 bit ALP
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT

## output
![image](https://github.com/user-attachments/assets/6e7a595e-9121-40d7-a89b-4b0d488813d9)

## OR of 8 bit ALP
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT

## output
![image](https://github.com/user-attachments/assets/1277ef08-d93e-4bfb-a1e4-663ae9c2e6b0)

## NOT of 8 bit ALP
MOV AL,65H
NOT AL
HLT

## output
![image](https://github.com/user-attachments/assets/293985d6-0303-4834-8eb7-6a6b2ff5ed9d)


## XOR of 8 bit ALP
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT

## output
![image](https://github.com/user-attachments/assets/3fedd279-92cc-4633-b9e2-b96f9faf1cbf)





## Result :
 

Thus to Write and execute ALP on fundamental arithmetic and logical operations are verified
successfully.






