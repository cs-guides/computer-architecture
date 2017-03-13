Assembly Languages
==================

High-Level Language (HLL) has these characteristics:

- one-to-many translation: 
  - each statement corresponds to multiple machine instructions
- hardware independent: 
  - programmers don't need to know details about underlying hardware
- application orientated: 
  - allows programmers to create application programs
  - HHL includes I/O facilities and allow programmers to define complex data objects
- general-purpose: 
  - not restricted to a specific task
- powerful abstractions: 
  - allows programmers to express complex tasks 

Low-Level Language has these characteristics:

- one-to-one translation: 
  - each statement corresponds to one instruction in the underlying processor
- hardware dependence: 
  - low-level language created for one type of processor can't be used with another type of processor 
- systems programming orientation:
  - allows programmers to create software that can directly control the hardware
- special-purpose: 
  - low-level language is only used when control and efficiency is needed
- few abstractions:
  - does not provide complex data structures or control statements
  
### Assembly Language

Assembly language is a low-level language. Since it uses the instruction set and operands from a specific processor, many assembly languages exist. However, many different assembly languages share the same structure.

##### Statement Format

A single assembly language statement corresponds to one machine instruction. The general format is:

label: opcode operand1, operand2, ...

- label is used for branching
- opcode specifies one possible instruction, separated by whitespace from other items
- operands are separated by commas 

##### Opcode Names

Assembly Languages use short abbreviations like add or br (branching) 

##### Commenting Conventions

Programmers often add comments after each line of assembly code to explain the purpose of the statement:

ld r5,r3 # load the address of list into r5

##### Operand Order

Operand order may change between assembly languages. In following statement, the first operand is the target register (the destination register), and the second operand is the source register:

ld r5,r3 # load the address of list into r5

Some assembly language specify the opposite order, where the target register is on the right:

ld r3,r5 # load the address of list into r5
