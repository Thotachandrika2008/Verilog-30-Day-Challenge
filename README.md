

### 🔗 Live Repo
https://github.com/Thotachandrika2008/Verilog

# Verilog 

> learning Verilog from basic gates to FSM. Daily practice on EDA Playground.

### 🔥 Progress
 | Project | Status | EDA Link |
|---------|--------|----------|
 | AND Gate | ✅ Done | [https://edaplayground.com/x/ASir] |
| Half Adder | ✅Done | https://edaplayground.com/x/kd2U|
| Full Adder | ✅Done | https://edaplayground.com/x/YmRh|

### 🛠️ Tools Used
- EDA Playground
- Icarus Verilog
- GitHub Mobile

### 👩‍💻 Author
Thota Chandrika - ECE | VLSI Aspirant | Hyderabad

---
⭐ Star this repo if you are also learning!

 ## 01 AND Gate
Truth Table Verified ✅
Output: 0,0,0,1

Proof: ![https://edaplayground.com/x/ASir](waveform.png)
##  02 Half Adder

Truth Table Verified ✅ 
- Sum: 0,1,1,0
- Carry: 0,0,0,1

Proof: [https://edaplayground.com/x/kd2U]

Files:
- `02_HALF_ADDER/half_adder.v`
- `02_HALF_ADDER/half_adder_tb.v

##  03: Full Adder in Verilog

Truth Table Verified ✅
- Sum: 0,1,1,0,1,0,0,1
- Cout: 0,0,0,1,0,1,1,1

Proof: [https://edaplayground.com/x/YmRh]

Files:
- 03_FULL_ADDER/full_adder.v
- 03_FULL_ADDER/full_adder_tb.v


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