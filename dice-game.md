# FPGA-Based Dice Game Controller
> **Tools:** Verilog, Intel DE10-Lite (MAX 10), One-Hot Encoding

## 🎯 Project Objective
Design a robust digital game system ("23") utilizing synchronous logic and modular data paths.



[Image of Mealy Finite State Machine state diagram]


## 🛠 Technical Implementation
* **Control Path:** Mealy FSM with **One-Hot Encoding** to minimize combinational depth and maximize $F_{max}$ at 50MHz.
* **BCD Logic:** Custom Ripple Carry Adder logic to convert binary sums to Decimal for 7-segment display.
* **Debouncing:** Synchronous switch debouncing to prevent metastability from asynchronous user inputs.

## 🔍 R&D Insight
Used a "Win-Hack" multiplexer to bypass standard logic paths during testing, demonstrating the ability to design for testability (DFT).
