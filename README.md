# IBM i operating system

This is intended to give a guideline on the eternal IBM i operating system.

![alt text](./images/ibmi_logo.png)

The special term in computer science is **abstraction**. There are levels of abstraction, basically from the atom to the internet. 

Here, we are going to start from the silicon up to get a better understanding of what is going on behind the green screen.

Silicon has some nice properties to make transistors. With transistors, you make logical gates; these logical gates perform boolean operations, which turn into logical units that form a circuit, and in the middle we have the CPU, which has its corresponding architecture and instruction set architecture. 

We are familiar with the (*x86*)[] (*x64*)[] archs. IBM has the (*PPC64*)[https://en.wikipedia.org/wiki/Ppc64] processor architecture with the (*Power ISA*)[https://en.wikipedia.org/wiki/Power_ISA] instruction set architecture which is a (*RISC*)[https://en.wikipedia.org/wiki/Reduced_instruction_set_computer] instruction set (yeah, RISC like (RISC-V)[https://en.wikipedia.org/wiki/RISC-V])

The original computer architecture was a (Von Neuman)[https://en.wikipedia.org/wiki/Von_Neumann_architecture] single-operator machine, but due to the increase in complexity due to increasing requirements, there was a need for a better way to manage resources and scale; that's when the *HLS* (Higher Level System) came into play. A better way to virtualize computer processing, which was in hand with the virtualization of storage with *LSI*. This also allows modularization and separations at different levels of abstraction of the machine and let each one be optimized independently while maintaining a well-defined communication interface. You can see similitudes to this idea on the network stack ((OSI Model)[https://en.wikipedia.org/wiki/OSI_model], (TCP/IP)[https://en.wikipedia.org/wiki/Internet_protocol_suite] ) and the internet ((REST arch)[https://en.wikipedia.org/wiki/REST]). This idea is all over the computer science field.

HSL permites directly job excecution or by emulation (like for the system/360)

This idea set a firm base for the future of IBM.

This also lets compile a languaje into a middle representations which in tourns is transtaled on the fly with no downtime. 

The languaje does not match the machine instruction set direclty.

## Little history recap

## IBM I system resources

## IBM I program excecution

## Command navigation

## OPM

## ILE