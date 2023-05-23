# Enhanced--32-Bit-RISC-Processor
## Design and Implementation of 32-Bit MIPS RISC Processor with Flexible 5-Stage Pipelining and Dynamic Thermal Control
The project involved the design and implementation of a 32-bit RISC-V processor with a 5-stage flexible pipeline using SystemVerilog. The primary objective was to develop a processor based on the MIPS instruction set architecture (ISA) with stages including instruction fetch, instruction decode, execute, memory access, and write back. The design also incorporated dynamic thermal management techniques for improved thermal stability.

RISC-V processors are widely used in various computational tasks, particularly in scientific computing domains like digital signal processing (DSP) and digital image processing (DIP). The reduced instruction set architecture allows for pipelined execution of instructions, resulting in enhanced performance and throughput.

The design was implemented using SystemVerilog, a hardware description language (HDL), and was simulated and synthesized to perform basic arithmetic logic unit (ALU) operations and generate the desired outputs. The simulation achieved significant improvements in speed, thanks to the flexible pipeline technique, while maintaining low power consumption.

The processor design was based on a synchronous technique, known for its speed and reliability in the industry. It utilized dynamic frequency scaling for thermal stability and operated at a high clock frequency to achieve higher speeds.

The design was successfully simulated with a UVM testbench, providing a total simulation time of *3* microseconds. The resulting total cell area was measured to be *1353.7984 micrometers*.

For future work, the design could be expanded to support a greater number of instructions and improved frequency scaling for better performance. It could also be extended to a 64-bit RISC architecture.

In conclusion, the project successfully accomplished the design and implementation of a 32-bit RISC-V processor with a 5-stage flexible pipeline. The project demonstrated the creation of various components such as the control unit, data path, instruction register, and memory interfaces. The design followed the principles of RISC architecture, offering simplicity and efficiency. Through simulation and testing in Logisim software, the processor executed different types of instructions and interacted with program and data memory, providing a comprehensive understanding of designing and simulating digital circuits.
