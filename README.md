# EXPERIMENT--01-ALP-FOR-8086
```
Name : Hariharan A
Roll no : 212223110013
Date of experiment : 21.02.2024
```


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

### Addition  of 8 bit ALP 
```
org 100h


MOV Ax,24H
MOV Bx,45H
ADD Ax,Bx


ret
```

### Subtraction   of 8 bit numbers  ALP 
```
org 100h

MOV Ax,24H
MOV Bx,45H
SUB Ax,Bx

ret
```

### Multiplication alp 
```
org 100h

MOV Ax,24H
MOV Bx,45H
mul Bx
HLT

ret
```

### Division alp 
```
org 100h

MOV Ax,24H
MOV Bx,45H
div Bx
HLT

ret
```

## Output :

### Addition  of 8 bit ALP 
![image](https://github.com/Raji1009/EXPERIMENT--01-ALP-FOR-8086/assets/89059861/df0b443c-3358-4f73-a79e-06c82e876e59)


### Subtraction   of 8 bit numbers  ALP 
![image](https://github.com/Raji1009/EXPERIMENT--01-ALP-FOR-8086/assets/89059861/56e53da5-dc55-453d-8ef2-7c0b6e9b708f)


### Multiplication alp 
![image](https://github.com/Raji1009/EXPERIMENT--01-ALP-FOR-8086/assets/89059861/6fa61681-f75f-459a-997a-58863a2d6c92)


### Division alp
![image](https://github.com/Raji1009/EXPERIMENT--01-ALP-FOR-8086/assets/89059861/f1a9f266-25ba-4cd8-b6c2-959189fb37b6)

## Programs for Logical  operations:

### AND gate 
```
org 100h

MOV Ax,24H
MOV Bx,45H
AND Ax,Bx
HLT

ret
```

### OR gate
```
org 100h
                                   
MOV Ax,24H
MOV Bx,45H
OR Ax,Bx
HLT
     
ret
```

### XOR gate
```
org 100h

MOV Ax,24H
MOV Bx,45H
XOR Ax,Bx
HLT

ret
```

### NOT gate
```
org 100h

MOV Ax,24H
NOT Ax
HLT

ret
```


## OUTPUT:
### AND gate 
![Screenshot 2024-03-29 190642](https://github.com/Raji1009/EXPERIMENT--01-ALP-FOR-8086/assets/89059861/ac8e2d89-6f3a-4243-bf33-895b2788ed51)

### OR gate
![Screenshot 2024-03-29 190725](https://github.com/Raji1009/EXPERIMENT--01-ALP-FOR-8086/assets/89059861/2b5dc5ff-de02-473d-b0bc-ee9ba223a635)

### XOR gate
![image](https://github.com/Raji1009/EXPERIMENT--01-ALP-FOR-8086/assets/89059861/69775505-b9ee-40c0-9d59-217c2d098202)

### NOT gate
![image](https://github.com/Raji1009/EXPERIMENT--01-ALP-FOR-8086/assets/89059861/27718bc7-ffe9-4eeb-a3ea-680a6244a177)


## Result :
 Thus, A Program Is Develope To Write And Execute ALP On Fundamental Arithmetic And Logical Operations.
