CPU/Processor - executes program instructions (low-level machine code) based on instruction set. program instructions and data needs to be stored in main memory.
Performance:
Clock Speed -  Number of FDE cycles per second (could be one instruction per cycle), can be increased (overclocking) but leads to more heat which can damage components.
Cores - Number of FDE cycles at one point in time, allows for parallelization and pipelining for programs that support it to speed them up but single core programs do not benefit.
Cache - Different levels of cache (close tends to have separate cache for data and instructions) very fast access memory (better than main memory), very expensive.
Pipelining - Assembly line, once each subtask is done then the resources are freed for another subtask while the task moves on e.g. stages of the FDE cycle. 

Registers:
Program Counter - Holds the address of the next instruction to be executed
Memory Address Register - Holds the address of the data/instruction to be read/written from/to main memory
Memory Data Register - Holds the data/instruction that has been read/will be written to main memory
Current Instruction Register - Holds the current instruction being executed.
Accumulator - holds the result of the ALU calculation

Components of CPU:
ALU - performs operations such as addition, subtraction and bit shifts
CU - decodes instructions and sends and manages signals on the control bus

FDE:
Fetch - PC -> MAR, Read Signal, MDR -> CIR, PC ++
Decode - OPCODE (Instruction), OPERAND (data/ where to find data)
Execute - uses ALU or other components to perform the instruction

Instruction Sets:
RISC - reduced instruction set, low instructions, each takes one clock cycle, easy to measure time, programs take more space in RAM, limited addressing, software over hardware
CISC - Complex Instruction Set, high instructions, more than one clock cycle, hard to measure time, programs take less space in RAM, lots of addressing, hardware over software

Buses:
Data - reads and writes data and instructions between the memory, secondary storage, cpu and I/O
Address -  used to specify address of memory location to read or write unidirectional.
Control Bus - Used to send read/write signals, bus request/grant/busy signals, interrupts and clock signals.

Architecture:
Von Neumann - one main memory for data and instructions, less expensive, less complex
Harvard - two separate main memories for data and instructions, more expensive, more complex, faster

GPU:
Kind of like a separate computer with its own memory, processor etc.
Many cores, used for stuff that requires a lot of parallel processing e.g. linear algebra for graphics/AI.
