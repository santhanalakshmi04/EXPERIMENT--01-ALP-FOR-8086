# EXPERIMENT--01-ALP-FOR-8086

Name : K.SANTHANA LAKSHMI

Roll no : 212222240091

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

## Addition  
```python
org 100h
MOV al,11h;
MOV bl,20h;
ADD al,bl;
MOV [6379h],al;
ret
```
## Output  
 ![image](https://github.com/santhanalakshmi04/EXPERIMENT--01-ALP-FOR-8086/assets/119475762/8ba7f5ca-08f7-4bc1-8a31-4c1cb3bf5c5f)

 
## Subtraction 
```python
org 100h
MOV al,20h;
MOV bl,[8778h];
SUB bl,al;
MOV [8798h],bl;
ret
```
## Output
![image](https://github.com/santhanalakshmi04/EXPERIMENT--01-ALP-FOR-8086/assets/119475762/1dd3268e-0d0b-44cb-81b1-1e0fdd9ddd8c)


## Multiplication
```python
org 100h
MOV al,13h;
MOV bl,2h;
MUL bl;
MOV [6063h],bl;
ret
```
 ## Output  
![image](https://github.com/santhanalakshmi04/EXPERIMENT--01-ALP-FOR-8086/assets/119475762/ee477ca8-0fe7-4f44-aefa-9b44d9b1cd9f)


## Division
```python
org 100h
MOV al,26h;
MOV bl,[2369h];
DIV bl;
MOV [2399h],al;
ret
```
## Output  
![image](https://github.com/santhanalakshmi04/EXPERIMENT--01-ALP-FOR-8086/assets/119475762/d4ed33a4-6be9-4ee5-af4b-53b474860b6c)

## Programs for logical  operations

## AND
```python
org 100h
MOV bx,1000h;
AND bx,1111h;
MOV [0040h+02],bx;
ret
```
## Output 
![image](https://github.com/santhanalakshmi04/EXPERIMENT--01-ALP-FOR-8086/assets/119475762/08ab4880-c0aa-4dfb-afd3-5f9e384eaed2)


## OR
```python
org 100h
MOV ax,[0070h];
MOV bx,1000h;
OR ax,bx;
MOV [0060h],ax;
ret
```
## Output
![image](https://github.com/santhanalakshmi04/EXPERIMENT--01-ALP-FOR-8086/assets/119475762/39afebe3-4023-43ef-81ed-31422996e8d7)

## NOT
```python
org 100h
MOV bx,0060h;
MOV ax,[bx]; 
NOT al;
MOV [0060h+04],ax;
ret
```
## Output
![image](https://github.com/santhanalakshmi04/EXPERIMENT--01-ALP-FOR-8086/assets/119475762/75e7aeef-9249-439c-b4c5-1991218d343b)


## XOR
```python
org 100h
MOV bx,0050h;
MOV ax,[bx]; 
XOR ax,bx;
MOV [0050h+03],ax;
ret
```
## Output
![image](https://github.com/santhanalakshmi04/EXPERIMENT--01-ALP-FOR-8086/assets/119475762/d69bf9ee-e2df-4128-8d3e-e879adc29d0b)


## Result :
Thus, ALP for fundamental arithmetic and logical operations are executed successfully.
 



