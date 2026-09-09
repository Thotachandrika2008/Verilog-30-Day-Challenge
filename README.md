![Verilog](https://img.shields.io/badge/Language-Verilog-blue)
![Challenge](https://img.shields.io/badge/Challenge-30_Days-green)
![Status](https://img.shields.io/badge/Day-02_Completed-orange)

### 🔗 Live Repo
https://github.com/Thotachandrika2008/Verilog-30-Day-Challenge

# Verilog 30-Day Challenge 🚀

> 30-day journey learning Verilog from basic gates to FSM. Daily practice on EDA Playground.

### 🔥 Progress
| Day | Project | Status | EDA Link |
|-----|---------|--------|----------|
| 01 | AND Gate | ✅ Done | [https://edaplayground.com/x/ASir] |
| 02 | Half Adder | ✅Done | https://edaplayground.com/x/kd2U|
| 03 | Full Adder | ⏳ Pending | |

### 🛠️ Tools Used
- EDA Playground
- Icarus Verilog
- GitHub Mobile

### 👩‍💻 Author
Thota Chandrika - ECE | VLSI Aspirant | Hyderabad

---
⭐ Star this repo if you are also learning!

 # Day 01: AND Gate
Truth Table Verified ✅
Output: 0,0,0,1

Proof: ![https://edaplayground.com/x/ASir](waveform.png)
## Day 02: Half Adder

Truth Table Verified ✅ 
- Sum: 0,1,1,0
- Carry: 0,0,0,1

Proof: [https://edaplayground.com/x/kd2U]

Files:
- `02_HALF_ADDER/half_adder.v`
- `02_HALF_ADDER/half_adder_tb.v

## Day 03: Full Adder in Verilog

Truth Table Verified ✅
- Sum: 0,1,1,0,1,0,0,1
- Cout: 0,0,0,1,0,1,1,1

Proof: [https://edaplayground.com/x/YmRh]

Files:
- 03_FULL_ADDER/full_adder.v
- 03_FULL_ADDER/full_adder_tb.v

### Full Adder in Verilog

live stimulation link:
https://edaplayground.com/x/YmRh

Logic:
- Sum = a XOR b XOR cin
- Cout = (a & b) | (b & cin) | (a & cin)

Truth Table:
| a | b | cin | Sum | Cout |
|---|---|-----|-----|------|
| 0 | 0 | 0   | 0   | 0    |
| 0 | 0 | 1   | 1   | 0    |
| 0 | 1 | 0   | 1   | 0    |
| 0 | 1 | 1   | 0   | 1    |
| 1 | 0 | 0   | 1   | 0    |
| 1 | 0 | 1   | 0   | 1    |
| 1 | 1 | 0   | 0   | 1    |
| 1 | 1 | 1   | 1   | 1    |