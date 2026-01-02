# 4-STAGE-PIPELINED-PROCESSOR-USING-VERILOG

This repository contains the Verilog implementation of a 4-stage pipelined processor as part of my CODTECH Internship – Task 3.

## Overview

This mini processor implements a simple 4-stage pipeline:
1. Instruction Fetch (IF)
2. Instruction Decode (ID)
3. Execute (EX)
4. Write Back (WB)

It supports a small instruction set including:
- ADD
- SUB
- LOAD
- NOP

The processor uses an 8-bit data path with a small register file and instruction/data memory. Instructions are preloaded into instruction memory with a mini program that demonstrates pipelined execution.

## 🛠 Tools Used
- Verilog HDL
- EDA Playground
- Icarus Verilog 12.0 (Simulator)

## 📁 Files in This Repository

cpu4stage.v ---> Implementation of the 4-stage pipelined processor 
cpu4stage_tb.v ---> Testbench that simulates the processor 
vlsi_task3.png ---> Screenshot of the simulation output 
cpu4stage_Report.pdf ---> Detailed report of Task-3 
README.md ---> This file 

## ▶️ How to Run (EDA Playground)

1. Go to https://edaplayground.com
2. Set Language → SystemVerilog (or Verilog)
3. Set Tool → Icarus Verilog 12.0
4. Paste cpu4stage.v in the Design panel
5. Paste cpu4stage_tb.v in the Testbench panel
6. Click Run
7. View the console output

## 📌 Notes

The simulation demonstrates correct pipelined execution of a simple instruction sequence. At the end, the processor’s register values reflect the expected outputs from the pipelined instructions.

## 🏁 Submission

Project completed as Task 3 of CODTECH Internship — "Pipeline Processor Design in Verilog".

⭐ Happy to help you with the next task too! 🚀
