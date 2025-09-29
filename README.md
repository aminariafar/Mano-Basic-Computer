# 💻 Basic Computer (Logisim Project)

A simple educational **digital computer** built in **Logisim 2.7.1**.  
This project demonstrates the construction of a CPU from the ground up using logic gates, registers, ALU, and control circuits.  

## ✨ Features
- Modular design with **30 circuits** (adder, ALU, registers, BUS, SC, etc.)
- Main circuit: **`main`**
- Arithmetic logic (adder, increment units, ALU)
- Control unit & simple bus architecture
- Step-by-step educational design to learn computer organization

## 🧱 Project Structure
```
_Basic Computer.circ   # Main Logisim project file
```

Contains subcircuits such as:
- `adder (1 bit)`
- `increment (16 bit)` / `increment (12 bit)`
- `ALU (1 bit)` / `ALU`
- `16bit reg.` / `12 bit reg.`
- `BUS`, `SC`, and others

## 🔧 Requirements
- [Logisim](http://www.cburch.com/logisim/) **2.7.1** or later  
  (or [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution))

## 🚀 Run the Project
1. Open `_Basic Computer.circ` in Logisim.  
2. Load the **main** circuit.  
3. Use the clock and input pins to simulate instruction execution.  

## 🎮 Usage
- ⚙️ Run clock to step through instructions  
- 🔍 Use probes to inspect values in registers and buses  
- 🖥️ Observe how the ALU and control unit cooperate to execute operations  

---

Made for learning ❤️ — explore, modify, and expand your own CPU in Logisim!
