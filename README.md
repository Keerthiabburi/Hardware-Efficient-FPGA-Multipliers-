# Hardware-Efficient Accurate and Approximate Multipliers Using Booth Encoding

This project focuses on the design of FPGA-optimized accurate and approximate multipliers for use in error-tolerant applications like 5G wireless communication. Two multiplier architectures were developed: one accurate using Booth encoding, and one approximate using LSB truncation with probabilistic compensation.

## ⚙️ Project Description

The project implements and compares:

- **Area-Mult**: An accurate 10×10 multiplier based on Booth encoding.
- **Pro-AppT8**: A 10×10 approximate multiplier that uses LSB truncation and a probability-based correction mechanism.

These designs aim to balance accuracy, performance, area, and power for use in FPGA-based low-power systems.

## 🛠 Tools Used

- **Xilinx Vivado 2018.3**
- **Verilog HDL / VHDL**
- **Vivado Simulator**
- **Power and Timing Analyzer**

## 🚀 Key Features

- Booth encoding for reduced partial products.
- Accurate multiplier with full-width addition.
- Approximate multiplier with LSB truncation and error compensation.
- Resource-optimized designs for FPGA implementation.
- Testbenches for validation using sample test cases.

## 📊 Results

| Metric     | Accurate Multiplier | Approximate Multiplier |
|------------|---------------------|-------------------------|
| Area       | Higher              | ~45.5% LUT reduction    |
| Power      | 92%                 | 87%                     |
| Timing     | Slightly more       | Better                  |
| Accuracy   | Exact               | BER degradation < 8×10⁻⁴ |

## 📌 Applications

- 5G Wireless Systems  
- Image Processing  
- Edge Computing  
- Low-Power Signal Processing

## 👥 Contributors

- **A Sai Keerthi**
- **B A V N Hasini**
- **Megha Elango**
- **Mentor**: Ms. Sonali Agarwal

## 📚 Reference

Wang et al., "Hardware-Efficient Accurate and Approximate FPGA Multipliers for Error-Tolerant Applications," IEEE MWSCAS, 2023. [DOI:10.1109/MWSCAS57524.2023.10406016](https://doi.org/10.1109/MWSCAS57524.2023.10406016)

---

Feel free to contribute or fork this repository!
