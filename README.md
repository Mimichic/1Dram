# Two-dimensional RAM
Implementation of a one-dimensional RAM that stores eight bits

## Problem at hand
We are to implement a storage device capable of reading and writing bits using Verilog programming.

## Methodology
The problem is subject to a rather simple few lines of code, with the inputs consisting of:
- data_in: containing the 8 bits we will be feeding to the RAM
- clk: a clock input
- read and write bits: we input a logic '1' in either of the two bits to read or write, respectively
- address: to locate the space in the RAM where you want to read/write data
- data_out: the 8-bit output obtained when an address is specified.
  
