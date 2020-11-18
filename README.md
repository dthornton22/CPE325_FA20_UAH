# CPE325_FA20_UAH
Further demonstration code can be found [here](https://github.com/uah-lacasa/CPE325_MSP430f5529). This code is intended for educational purposes only. Misuse of the Software, as described in the [license](LICENSE), is subject to copyright law.

[Lab 01 Report](Course_Files/Reports/Thornton_David_Lab_01_Report.pdf) </br>
[Lab 02 Report](Course_Files/Reports/Thornton_David_Lab_02_Report.pdf) </br>
[Lab 03 Report](Course_Files/Reports/Thornton_David_Lab_03_Report.pdf) </br>
[Lab 04 Report](Course_Files/Reports/Thornton_David_Lab_04_Report.pdf) </br>
[Lab 05 Report](Course_Files/Reports/Thornton_David_Lab_05_Report.pdf) </br>
[Lab 06 Report](Course_Files/Reports/Thornton_David_Lab_06_Report.pdf) </br>
[Lab 07 Report](Course_Files/Reports/Thornton_David_Lab_07_Report.pdf) </br>
[Lab 08 Report](Course_Files/Reports/Thornton_David_Lab_08_Report.pdf) </br>
[Lab 09 Report](Course_Files/Reports/Thornton_David_Lab_09_Report.pdf) </br>
[Lab 10 Report](Course_Files/Reports/Thornton_David_Lab_10_Report.pdf) </br>

Using Code Composer Studio
Search “5529” for find the board MSP430F5529

1. Build -> MSP430 Compiler -> Processor Options

- Silicon version = msp

- Code memory model = small

- Data memory model = small

2. Build -> MSP430 Compiler -> Optimization

- Optimization level = off

3. Build -> MSP430 Compiler -> Advanced Options -> Language Options

- Level of printf/scanf support required = full

4. Build -> MSP430 Compiler -> Advanced Options -> Assembler Options

- Generate listing file = true

5. Build -> MSP430 Linker -> Basic Options

- Heap size for C/C++ dynamic memory allocation = 300
