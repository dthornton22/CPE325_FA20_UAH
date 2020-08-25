# CPE325_FA20_UAH
Using Code Composer Studio
Search “5529” for find the board MSP430F5529

Build -> MSP430 Compiler -> Processor Options

Silicon version = msp

Code memory model = small

Data memory model = small

Build -> MSP430 Compiler -> Optimization

Optimization level = off

Build -> MSP430 Compiler -> Advanced Options -> Language Options

Level of printf/scanf support required = full

Build -> MSP430 Compiler -> Advanced Options -> Assembler Options

Generate listing file = true

Build -> MSP430 Linker -> Basic Options

Heap size for C/C++ dynamic memory allocation = 300
