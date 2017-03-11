CPUs
====

Central Processing Unit (CPU) manages the entire computer by performing calculations, controlling I/O, and telling other processors what to do.

Modern CPUs are very complex, containing billions of transistors to achieve high performance.

- Multiple cores
- Multiple roles
- Protection and Privilege
- Hardware Priorities
- Generality
- Data size
- High speed

The hardware for CPUs have different modes of execution to handle complex operations and features. Items commonly associated with CPU mode of execution include:

- the subset of instructions that are valid
- the size of data items 
- the region of memory that can be accessed
- the functional units that are available
- the amount of privilege

There are two ways the CPU can change execution modes:

- Automatic: initiated by hardware, like an I/O device
- Manual: mode changes under a running program, like the operating system

Three different mechanism are used to change modes:

- CPU includes an instruction to set the current mode
- CPU contains a special-purpose mode register to control the mode (responds to the store command by changing the mode)
- the side-effect of another instruction can change the mode (e.g. an app makes an operating system call by using an instruction from a CPU instruction set)

CPUs can prevent unintentional or malicious changes with different levels of privilege that limit the operations that are allowed. CPUs that run apps have at least two levels of protection. The operating system has the highest privilege, and apps run with limited privilege.



 
