# 🚦 Traffic Light Controller using Verilog

This project implements a basic **Traffic Light Controller** using **Verilog HDL** based on a **Finite State Machine (FSM)** approach. It simulates the behavior of a traffic light system at a typical intersection, managing red, yellow, and green signals with fixed timing logic.

---

## 🔧 Features

- Built using Verilog HDL
- FSM-based design for sequential control logic
- Handles Red → Green → Yellow transitions in a timed loop
- Includes a testbench for simulation and verification

---

## 📁 Files Included

- `traffic_light_controller.v` – Main Verilog module with FSM logic
- `traffic_light_tb.v` – Testbench to simulate and verify output states
- `README.md` – Project documentation

---

## 🧠 How It Works

The controller cycles through three states:
1. **Red**
2. **Green**
3. **Yellow**

Each state is assigned a timer, and transitions are handled by a **clock-driven FSM**. The outputs are controlled based on the current state.

---

## ▶️ Simulation

You can simulate this project using tools like:
- [EDA Playground](https://edaplayground.com/)
- ModelSim
- Vivado

Steps:
1. Paste the code into your simulation environment
2. Run the testbench
3. Observe waveform outputs or console messages

---

## 📚 What I Learned

- Basics of Verilog syntax and module structure
- FSM design and implementation
- Testbench creation and signal simulation
- How to simulate and debug digital designs

---

## 📌 Future Improvements

- Add pedestrian crossing signals
- Add real-time sensor-based inputs
- Expand to 4-way junction

---


