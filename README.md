# Computer Systems - Notes:  

 **Jan 9th 2024**
  
  Day one starting *computer systems a programmers's persepctive.*
    
## Chapter 1: A tour of comptuer systems  

>Quesiton: What is a unix or unix shell
  
### 1.1 Information is bits + context
  
  All information in a system is represented as a bunch of bits. Programmers need to learn how a system is read and translated by a program. Everything can be understood in this order;
  - Bits = 0 or 1s
  - Bytes = 8-bit characters
  - Text Characters translate to to ASCII 
  - ASCII is a common standard that represents each character with a unque *byte sized* interger value.   
### 1.2 Programs are translated by other programs into different forms  
  
  Quick look at the **compilation system**  
  - A system of phases that take human text and convert it into readable binary to create an excutable program.  
    - Preprocessing phase
    - Compilation phase
    - Assembly phase
    - Linking phase   
  
This is the process by which human code gets brought into a compiler into binary then into a executable object - useable program.  
> ??? what exsactly is **Linux**  
  
>??? What is the differance between UNIX and GNU  
  
### 1.3 It pays to understand how Compliation systems work  
Three reasons:  
- Optimizing program preformance
- Understanding link time errors
- Avoiding security holes  

### Side Study - What is UNIX  
Unix is an operating system similar to linux in many ways they are the same and for the most part should be considered as such.  

### 1.4 what do processors do  
*Read and interpret insturcitons stored in memory*   
    
**(1)**
- hardware layout of a computer
    - Buses
        - moving the information
    - I/O devices
        - Input out put connection (mouse, keybord, ect) 
    - Main Memory
        - Where info is temporarly stored so that a pogram and data can be run
    - Processor
        - The brain of the system, everything runs through the processor  

**(2)**
- running a program on hardware (super simple version)
    - I/O (keybord) send info to the main memory. Info as to what was input from the I/O is pulled from the disk. They both survie in the main memory and then are sent to the PC (via buses) and then spit back out to the Graphics Adapter (GCU) where the executale program will be completed on the display.  

### 1.5  
