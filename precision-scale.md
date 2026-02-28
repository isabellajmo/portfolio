# High-Resolution Jelly Bean Counting Scale
> **Tools:** INA125, Wheatstone Bridge, MATLAB, M2K Discovery

## 🎯 Project Objective
Bridge analog sensors with digital processing to achieve a 0.5g resolution scale.



## 🛠 Technical Implementation
* **Signal Chain:** Two-stage conditioning using an **INA125 Instrumentation Amp** for high CMRR.
* **Noise Mitigation:** Utilized twisted-pair differential signaling to preserve $\mu V$ signals against EMI.
* **Calibration:** Linear mapping of 12-bit ADC values to grams via MATLAB-based statistical analysis.

## 🔍 R&D Insight
Ensuring linearity across a 0–2kg range required precise gain-setting resistor selection to stay within the Op-Amp's linear saturation limits.
