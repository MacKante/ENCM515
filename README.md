# Reading Log

# Week of Jan 13

- Went over course specifics and details

- Started introduction lecture on motivations and platforms

- Reviewed embedded systems and computer architecture as well as ISAs

    - RISC (Reduced Instruction Set Computers): size of instruction word is the same and requires simpler decoding hardware
    - CISC (Complex Instruction Set Computers): size of instruction word are not all the same and could require more complex decoding hardware
    - VLIW (Very Long Instruction Word): parallel operations per operation

- Review of processors and what they do
    - Fetching: access memory to get next instruction
    - Decoding: interpret bits
    - Execution: perform operations

- Von Neumann vs. Harvard  Computer Architecture
    - Von Neumann architecture has a shared block of memory for both instructions and data while harvard has separate blocks for each


# Week of Jan 20

- Reviewed last week, specifically GPP vs ASIP, benefits and complications of both

- NRE (Non-recurring engineering)

- Field Programmable Gate Array (FPGA)
    - when software is not "good enough", when there is too much in parallel
    - logic circuits that are configurable to meet requirements to handle lots of inputs
    - FPGAs are good at handling lots of inputs at the same time
    - useful in high speed interfaces
    - **BUT**, hardware is hard

- Dr. Tan said if you dont want to be replaced by AI, look into ASIC design. Look into ASIC design.

- Application Specific Integrated Circuit (ASIC)
    - Most expensive due to the high NRE cost
    - strict and extreme performance requirements, no flexibility
    - Able to meet ultra-low power consumption
    - once ya got it, ya gotta stick with it

- Look into hobbyist stuff: TinyTapeout

- When it comes to Hardware/Software Co-Design...
    - Hardware/Software Codesign is the partitioning and design of an application in terms of fixed and flexible components
    - More flexibility would result in less efficiency in power consumption and vice versa
    - When we want to find the *"best"* solution, we need to deal with both software and hardware.
