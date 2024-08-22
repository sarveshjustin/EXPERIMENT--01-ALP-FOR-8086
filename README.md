

# EXPERIMENT--01-ALP-FOR-8086
### Name : SARVESH.S
### Roll no : 212222230135
### Date of experiment : 22/08/24
## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.

 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	 Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.

 ![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)
10.	Click on emulate to start emulation 


![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)
11.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 


![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations
## Addition  of 8 bit ALP 
```
org 100h
mov AL,59h;
mov BL,79h;
ADD AL,BL;
HLT
ret
```
## Output  
![Screenshot 2024-08-22 091913](https://github.com/user-attachments/assets/6f9f0922-3330-49c6-94cf-8bdd6e5cf85f)

## Subtraction   of 8 bit numbers  ALP 
 ```
org 100h
mov AL,83h;
mov BL,33h;
SUB AL,BL;
HLT
ret
```
## Output  
![Screenshot 2024-08-22 092350](https://github.com/user-attachments/assets/633f8bdc-ebc1-4163-ae14-96f49f4bb752)

## Multiplication alp 
```
org 100h
mov AL,75h;
mov BL,12h;
MUL BL;
HLT
ret
```
 ## Output  
![Screenshot 2024-08-22 092429](https://github.com/user-attachments/assets/29ee8395-92c4-4108-8421-a40cb46d53a6)

## Division alp 
```
org 100h
mov AL,65h;
mov BL,15h;
DIV BL;
HLT
ret
```
## Output  
![Screenshot 2024-08-22 092557](https://github.com/user-attachments/assets/ecf6d044-2490-4754-bc03-8139aa0652af)


## Programs for logical operations
## AND
```
org 100h
mov AL,66h;
mov BL,70h;
AND AL,BL;
HLT
ret
```
## Output  

![Screenshot 2024-08-22 131708](https://github.com/user-attachments/assets/1ca1e6f1-8d6f-4fc2-928e-bee6f70fc17d)


## OR
```
org 100h
mov AL,66h;
mov BL,70h;
OR AL,BL;
HLT
ret
``` 
## Output
![Screenshot 2024-08-22 131756](https://github.com/user-attachments/assets/dd760257-4446-441a-b83a-9a1d0e3c15b7)

## NOT
```
org 100h
mov AL,66h;
NOT AL;
HLT;
ret
```
## Output  
![Screenshot 2024-08-22 131831](https://github.com/user-attachments/assets/b097d1ff-19de-4212-b386-ef5d37b3b882)


## XOR 
```
org 100h
mov AL,66h;
mov BL,70h;
XOR AL,BL;
HLT
ret
```
## Output  
![Screenshot 2024-08-22 131902](https://github.com/user-attachments/assets/079a51e8-cfbc-4875-96ef-19f9a247e08d)


## Result :
 Thus the  ALP on fundamental arithmetic and logical operations executed successfully.






