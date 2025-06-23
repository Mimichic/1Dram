# Two-dimensional RAM
Implementation of a two-dimensional RAM that stores eight bits

## Problem at hand
We are to implement a storage device which is capable of both reading and writing bits using Verilog programming.

## Methodology
The problem is subject to a rather simple few lines of code with the inputs containing of:
- data_in: containing 8 bits we will feed to the ram
- clk: a clock input
- read and write bits: we input a logic '1' in either of the two bits to read or write respectively
- address: to locate the space in the RAM where you want to read/write data
