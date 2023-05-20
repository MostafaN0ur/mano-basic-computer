# mano-basic-computer
A basic computer architecture with Verilog programming language
Programming and simulation
The Nono Basic Computer is a simple computer designed to perform basic arithmetic and logic operations.

 It consists of a central processing unit (CPU), memory, input/output devices, and a control unit. The CPU performs calculations and logical operations on data stored in memory, while the input/output devices allow the user to interact with the computer. The control unit manages the flow of data between these components.
 
 Data Bus
 The memory bus is used to transfer data between the CPU and memory, and is distinct from the I/O bus used for input/output operations. Memory reference is an essential part of programming for the Nono architecture.
 
fech
 In the Nono, the fetch operation is the first step of the instruction cycle. It involves retrieving the next instruction from memory and loading it into the instruction register (IR), using the program counter (PC) to keep track of the memory address of the next instruction. The fetch operation is followed by the decode and execute phases of the instruction cycle.
 
decode
 The decode operation in the Nono interprets the instruction loaded in the instruction register during the fetch phase. It extracts the values of the instruction fields to determine the operation to be performed and the operands involved. Once decoded, the computer proceeds to the execute phase to perform the specified operation..
 
Indirect
 the indirect operation is used to access memory locations indirectly. It involves using a memory address that points to another memory address, which contains the actual data or instruction to be accessed. This allows for more flexible and dynamic memory access in certain programming scenarios.

Memory reference
 memory reference involves the use of memory to store and retrieve data.
The Nono has 16 memory locations, each of which can hold a 8-bit value*

Register reference
 Register references in the Nono architecture involve the use of the accumulator register AC to hold data that is being processed.
 
 Output/Input reference
  In the Nono architecture, input/output (I/O) operations are handled by the INP and OUT instructions,
 which allow the CPU to communicate with external devices. I/O devices are connected to the CPU through a separate I/O bus, which is distinct from the memory bus.
