RISC-V Talent Development Program

The program, powered by Samsung Semiconductor India Research (SSIR) and VLSI System Design (VSD) , is focused on developing talent in the RISC-V ecosystem.

Participant Details:

•	Name: Vinayakgouda S A

•	Institution: Sahyadri College of Engineering & Management, Mangaluru

•	Email: Vinayakgouda.ec22@sahyadri.edu.in

•	GitHub: Vinayakgouda-Sahyadri-ECE

Task 1: Development and Compilation of a Parameterized C Program

1.	Setting Up the Virtual Machine: I used VirtualBox to set up a virtual environment with Ubuntu 18.04:
	
           a. Opened VirtualBox and clicked "New" to create a new virtual machine.
	
           b. Selected Linux as the operating system and Ubuntu 18.04 as the version.
	
           c. Allocated memory and selected an existing virtual hard disk (the unzipped VDI file).
	
           d. Launched the virtual machine and verified that it booted successfully.
	
           e. Writing, Compiling, and Running the C Program Locally: I wrote a parameterized C program (sum1ton.c) to compute the sum of numbers from 1 to ( n ). This program uses a loop for computation and 
              dynamically accepts ( n ) as input from the user during execution.
	
           f. Sum of Numbers from 1 to ( n ):
	
                • The sum of the first ( n ) natural numbers is mathematically calculated as: [ \text{Sum} = 1 + 2 + 3 + \dots + n = \frac{n \cdot (n + 1)}{2} ]

                • However, in the program, the sum is computed iteratively using a loop for practice with programming constructs.

2.	Steps:

    • Used a text editor (e.g., leafpad) to write the program.

    • Compiled the program locally using the GCC compiler (gcc).

    • Executed the compiled binary (./a.out) and provided various inputs for ( n ) to validate the output.

![Screenshot 2025-01-07 235426](https://github.com/user-attachments/assets/87ba8b60-d10c-4ac6-8399-fbf93f03cc53)


![Screenshot 2025-01-07 235115](https://github.com/user-attachments/assets/e1224d92-38e7-4285-b3b5-bf6932b5bb83)


3.	Cross-Compiling for RISC-V Architecture: I cross-compiled the same C program for the RISC-V architecture 
  
4.	Used the RISC-V GCC Cross-Compiler (riscv64-unknown-elf-gcc) to compile the program with the following options:

    o Optimization flags: -O1 and -Ofast to improve performance.

    o ABI: -mabi=lp64 to specify the Application Binary Interface.

    o Architecture: -march=rv64i for the 64-bit RISC-V instruction set.

5.	Verified the creation of the optimized object file (sum1ton.o), ready for execution in a RISC-V simulation or hardware environment. 
  
6.	Setting up a virtual development environment provides a controlled platform for development and testing.
   
7.	Understanding the mathematical formula for the sum of numbers from 1 to ( n ) helps in validating the program logic.
    
8.	Writing and compiling a parameterized C program locally ensures correctness before targeting specific hardware.
	
9.	Cross-compilation using architecture-specific tools and optimizations is crucial for efficient code execution on embedded systems like RISC-V.




