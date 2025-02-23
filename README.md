# RAM-DESIGN

COMPANY NAME:CODE TECH IT SOLUTIONS PVT.LTD

NAME:GudipalliMounika

INTERN ID:CT12GUG

DOMAIN:VLSI

BATCH DURATION:January 20th,2025 to March 20th,2025

MENTOR NAME: NEELA SANTHOSH

DESCRIPTION:The RAM operates on a clock signal (clk) and supports both read and write operations. It is parameterized, meaning the data width and address width can be modified as needed.

Clock-Controlled: All operations occur on the rising edge of the clock.

Write Operation (we = 1): Data is stored at the specified address (addr).

Read Operation (we = 0): Data from addr is output on data_out.

Memory Array: Stores 2^ADDR_WIDTH locations, each DATA_WIDTH bits wide.

Module (synchronous_ram): Implements RAM with read/write functionality.

Testbench (synchronous_ram_tb): Simulates write and read operations with clock synchronization.

Clock Generation: Uses a 10ns period for synchronous operation.

Expected Output: Successfully retrieves stored data from memory locations.

Used in FPGA/ASIC designs, embedded systems, caches, and high-speed processors where synchronized memory access is required.
