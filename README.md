# IBM i operating system

This is intended to give a guideline on the eternal IBM i operating system.

![alt text](./images/ibmi_logo.png)

The special term in computer science is **abstraction**. There are levels of abstraction, basically from the atom to the internet. 

Here, we are going to start from the silicon up to get a better understanding of what is going on behind the green screen.

Silicon has some nice properties to make transistors. With transistors, you make logical gates; these logical gates perform boolean operations, which turn into logical units that form a circuit, and in the middle we have the CPU, which has its corresponding architecture and instruction set architecture. 

We are familiar with the (*x86*)[] (*x64*)[] archs. IBM has the [*PPC64*](https://en.wikipedia.org/wiki/Ppc64) processor architecture with the [*Power ISA*](https://en.wikipedia.org/wiki/Power_ISA) instruction set architecture which is a [*RISC*](https://en.wikipedia.org/wiki/Reduced_instruction_set_computer) instruction set (yeah, RISC like [RISC-V](https://en.wikipedia.org/wiki/RISC-V]))

The original computer architecture was a [Von Neuman](https://en.wikipedia.org/wiki/Von_Neumann_architecture) single-operator machine, the [the IBM 701](https://en.wikipedia.org/wiki/IBM_701). 

but due to the increase in complexity and requirements, there was a need for a better way to manage resources and scale; that's when the ideas of *LSI* (virtualization of storage), *HLS* (Higher Level System) and [Future Systems project (FS)](https://en.wikipedia.org/wiki/IBM_Future_Systems_project) came into play. 

The main principle was to have a machine that natively executed high level procedural languages (FORTRAN, COBOL, PL/i, APL, RPG) without interpretation. Needless to say, this was an incredibly ambitious project that needed a large number of breakthroughs in many areas, which lead to the project being terminated. 

After that, ibm released the [System/38](https://en.wikipedia.org/wiki/IBM_System/38) which actually had some of those ambitious ideas: programs were compiled into a high-level instruction set, which was not *interpreted* but rather *translated* into a lower-level machine instruction set to be executed. The operating system was the [Control Program Facility](https://en.wikipedia.org/wiki/Control_Program_Facility). Before that ibm had the (System Support Program)[https://en.wikipedia.org/wiki/System_Support_Program] operating system for the [System/34](https://en.wikipedia.org/wiki/IBM_System/34), [System/36](https://en.wikipedia.org/wiki/IBM_System/36). These were actually considered midrange computers.

The idea of modularization and separations at different levels of abstraction is a patter found on many areas of computer science. For example: the network stack ([OSI Model](https://en.wikipedia.org/wiki/OSI_model), [TCP/IP](https://en.wikipedia.org/wiki/Internet_protocol_suite) ) and the internet ([REST arch](https://en.wikipedia.org/wiki/REST)).

After that, came the famous [AS/400](https://en.wikipedia.org/wiki/IBM_AS/400) which leveraged on this idea of different levels of abstractions.

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