# 6-bit Signed/Unsigned Comparator

## 📖 Overview
This project focuses on designing a 6-bit comparator that supports both signed and unsigned numbers.

The design was implemented using:
- Structural modeling (logic gates)
- Behavioral modeling (for verification)

The system was later converted into a synchronous circuit using registers and a clock signal.

## ⚙️ Technologies Used
- Verilog HDL
- Active-HDL Simulator
- Digital Logic Design (gates-level implementation)

## 🧩 Design Components
- Unsigned Comparator
- Signed Comparator (MSB-based logic)
- Synchronous Comparator (with clock & registers)
- Behavioral Comparator (used as reference model)

## 🚀 Key Features
- Gate-level design using basic logic gates (AND, OR, XOR, XNOR, etc.)
- Support for both signed and unsigned comparison
- Synchronization using clock (posedge triggering)
- Custom gate delays implementation
- Glitch handling through clock tuning

## 🧪 Verification & Testing
- Full testbench covering all possible input combinations
- Behavioral model used as a reference for validation
- Automatic error detection using counters
- Simulation confirms correctness ("All tests passed")
