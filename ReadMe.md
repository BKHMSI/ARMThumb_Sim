/******************************************************************************\             

                   
               *§                              
              **§§              
             ***§§§             
            ****§§§§            
           *****§§§§§           BADR ALKHAMISSI
          ******§§§§§§          ARM THUMB SIMULATOR
         *******§§§§§§§         
          ******§§§§§§          
           *****§§§§§           
            ****§§§§            
             ***§§§             
              **§§              
               *§  


\******************************************************************************/             


Features:


1. Assembler directives
    1. .text / .code
    2. .data
    3. .byte
    4. .short
    5. .word
    6. .asciiz 
    7. .space
2. Debugging
    1. Breakpoints
    2. Stepping
    3. Highlighting machine code being executed
    4. Printing output
    5. Printing generated assembly code
    6. Registers values reflect current state 
    7. Condition flags values reflect current state 
    8. Memory values reflect current state 
3. Software Interrupts
    1. Reading integer
    2. Reading null-terminated string
    3. Reading character 
    4. Printing integer
    5. Printing null-terminated string
    6. Printing character
4. GFX Display (320x240)
    1. Frame-Rate adjustable
    2. Zoom by a factor of 2
5. Syntax highlighting for ARM assembly 
6. Change theme of code-editor
7. Importing/Exporting Machine/Assembly Code and Sample Code
8. Creating user account
    1. Saving projects 
    2. Making them private or public
9. Convertors
    1. Converting machine code into different formats 
    2. Convertor in the bottom of the page for convenience 
10. Four Sample Programs 
11. Comments 

Pseudo Instructions:

1. MOV Rd,Rs
2. LDR Rd, =label | =offset

CPU:

1. Memory 4MB
2. Data Segment  2 MB —> 4 MB
3. Stack Segment 1 MB —> 2 MB
4. Text Segment  0 MB —> 1 MB
5. 15 Registers: 7 Low / 8 High including SP/LR/PC

