### [**Describe the difference between a flip-flop and a latch**](https://nandland.com/part-2-the-interview/#26dc0b8b91615542c)

- **Clock Dependency**: The main difference is that a flip-flop uses a clock as an input, while a latch does not.  
  - The clock input on the flip-flop is used to transfer the D input to the Q output.  
  - A latch, being level-sensitive, latches or holds the output steady without requiring a clock signal.

- **Usage in FPGA Design**: Flip-flops are commonly used in FPGA designs, while latches are generally avoided due to their potential for creating timing issues.

- **Speed**: Latches are faster than flip-flops because they do not rely on a clock edge to operate.
