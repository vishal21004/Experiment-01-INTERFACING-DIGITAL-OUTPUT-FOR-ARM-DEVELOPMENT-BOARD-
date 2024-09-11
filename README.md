## EXPERIMENT--01-ALP-FOR-8086
## Name : VISHAL M.A

## Roll no : 21222223017

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086 emulator
## Theory
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.

## Running the Emulator :
1.Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory

2.Run emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color

 3.write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
 
4.Compile the program and check for the errors

5.Run (once there is no syntax error)

6.Click OK to see/view the output of your program on the Emulator screen.

7.After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,

8.
![189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04](https://github.com/user-attachments/assets/bace2e68-d36b-4e6c-8e49-35c6900e9f81)



9.Click on emulate to start emulation

![189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc](https://github.com/user-attachments/assets/ad7d228a-0e3a-4039-890c-cfbc629990cf)


10.If no errors are found click on run the program and check the status of various flags in the flags tab as shown below

![189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe](https://github.com/user-attachments/assets/7c16fb74-8cfa-4593-aa85-c5330e3fab71)


## Programs for arithmetic operations
## Addition of 8 bit ALP
```
org 100h
MOV al,11h;
MOV bl,20h;
ADD al,bl;
MOV [6379h],al;
ret
```
## Output:
![pmc out 1](https://github.com/user-attachments/assets/9ab02158-48d9-46eb-8920-8fb7b28e582d)


## Subtraction of 8 bit numbers ALP:
```
org 100h
MOV al,20h;
MOV bl,[8778h];
SUB bl,al;
MOV [8798h],bl;
ret
```
## output:
![pmc out2](https://github.com/user-attachments/assets/507c8c3b-7146-4b24-8bc3-efd3798bd866)


## Multiplication alp:
```
org 100h
 MOV al,13h;
 MOV bl,2h;
 MUL bl;
 MOV [6063h],bl;
 ret
```
## Output:
![pmc out3](https://github.com/user-attachments/assets/abc274eb-8ee9-4b7c-af94-9c5aaf518b53)


## Division alp:

```
org 100h
 MOV al,26h;
 MOV bl,[2369h];
 DIV bl;
 MOV [2399h],al;
 ret
```
## output:
![pmc out4](https://github.com/user-attachments/assets/86233d9a-78c7-44f7-82e9-019d9055830b)


## Programs For Logical Operators:
## AND
```
org 100h
mov bx,1000h;
and bx,1111h;
mov [0040h+02],bx;
ret
```
## output:
![pmc out5](https://github.com/user-attachments/assets/c3d0a597-388c-48b7-b0d5-4ecc8d87debf)


## or:
```
MOV SI,0532H;
MOV AX,0A32H;
MOV BX,0B13H;
OR AX,BX;
```
## output:

![pmc out 6](https://github.com/user-attachments/assets/8f5edf8e-79f9-48f3-a4d0-c4df91f183f6)


## NOT:
```
org 100h
mov bx,0040h;
mov ax,[bx]; 
not al;
mov [0040h+04],ax;
ret
```
## output:
![pmc out7](https://github.com/user-attachments/assets/1bd916f4-fc1f-43b2-bcbd-4b55125fb7c5)


## XOR:
```
MOV [SI+2],AX;
MOV AX,0A32H;
MOV BX,0B13H;
XOR AX,BX;
```
## output:
![pmc out 8](https://github.com/user-attachments/assets/d0fc7d0a-0422-4c0f-b50f-e8742209d33b)

## Result:Thus, to write and execute ALP on fundamental arithmetic operations and Logical operations is successful.
 
 
 
