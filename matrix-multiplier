# Matrix Multiplication Accelerator
> **Tools:** Verilog, Intel Quartus, ModelSim, Dual-Port RAM

## 🎯 Project Objective
To architect a hardware engine capable of $8 \times 8$ matrix multiplication while maximizing data throughput and maintaining 19-bit precision.



## 🛠 Technical Implementation
* **Parallel MAC Units:** Instantiated dual Multiply-Accumulate units to compute two matrix elements per clock cycle.
* **Precision:** 8-bit signed 2’s complement arithmetic with a 19-bit accumulator to ensure zero overflow during summation.
* **Memory Stride:** Engineered an FSM to manage memory addressing, effectively overcoming the Von Neumann bottleneck.

## 🔍 R&D Insight
**Challenge:** Data hazards during simultaneous RAM reads.
**Solution:** Implemented synchronous Dual-Port RAM with a pipeline-aware FSM to account for 1-cycle read latency.
