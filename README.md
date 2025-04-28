# 16-bit CPU Design in Logisim

This repository contains the Logisim circuit design files for a custom 16-bit CPU. This project demonstrates a fundamental computer architecture implemented entirely within the software circuit emulator Logisim.

**Key Features:**

* **Comprehensive ALU Operations:** The CPU is capable of performing a variety of arithmetic and logic unit (ALU) operations, including addition, subtraction, multiplication, and more.
* **Complex Instructions:** Beyond basic ALU functions, the instruction set includes support for complex operations such as:
    * **MATMULT:** Matrix multiplication.
    * **BLOCK LOAD:** Efficiently loading a block of data into memory.
    * **BLOCK STORE:** Efficiently storing a block of data from memory.
* **Memory Integration:** The design incorporates a working memory unit for data storage and retrieval.
* **Clock-Cycle Execution:** All operations are meticulously designed to execute within discrete clock cycles, providing a clear understanding of instruction timing.
* **Pipelined Architecture:** The CPU implements a pipelined architecture, leveraging a clock signal to improve instruction throughput and overall performance.
* **Fundamental Components:** The design utilizes essential digital logic components such as adders, subtractors, multipliers, and decoders to realize the CPU's functionality.

This project serves as a valuable educational resource for understanding the inner workings of a CPU, the implementation of complex instructions, memory interaction, and the benefits of pipelining within a digital circuit. Explore the Logisim files to delve into the detailed hardware implementation of this 16-bit processor.
