# Static Timing Analysis (STA)

## 📌 Overview
This project focuses on understanding the fundamental concepts of Static Timing Analysis (STA), which is critical in ensuring correct operation of digital circuits in ASIC design.

## ⚙️ Design Description
- Implemented a simple **counter circuit in Verilog**
- Applied timing constraints using SDC format

## ⏱️ Key Timing Concepts
- **Setup Time**: Minimum time before clock edge data must be stable  
- **Hold Time**: Minimum time after clock edge data must remain stable  
- **Slack**: Difference between required time and actual arrival time  
- **Critical Path**: Longest delay path determining maximum clock frequency  

## 📊 Analysis Approach
- Defined clock and I/O delays using SDC constraints  
- Studied timing behavior and identified potential violations  
- Analyzed how timing impacts circuit reliability  

## 🧠 Key Learnings
- Importance of timing constraints in digital design  
- Identification of setup and hold violations  
- Role of slack in determining timing closure  
- Understanding critical paths in circuits  

## ⚠️ Note
This project emphasizes **conceptual understanding of STA**, which is essential for timing closure in ASIC design.
