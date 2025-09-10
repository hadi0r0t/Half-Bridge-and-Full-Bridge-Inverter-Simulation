# Half-Bridge and Full-Bridge Inverter Simulation (MATLAB/Simulink)

This repository contains MATLAB/Simulink simulations for **Half-Bridge** and **Full-Bridge** inverter topologies.
MATLAB/Simulink models for half-bridge and full-bridge inverter topologies. Includes simulation of output waveforms, modulation index effects, and voltage fundamentals. Useful for power electronics study, inverter design, and comparing performance between bridge configurations.

---

## 🔑 Key Results

- **Half-Bridge Inverter (V1 fundamental)**
  \[
  V_{1,peak} = \frac{m}{2} \cdot V_{dc}
  \]
  \[
  = \frac{0.8}{2} \cdot 400 = 160 \, V
  \]

- **Full-Bridge Inverter (V2 fundamental)**
  \[
  V_{2,peak} = m \cdot V_{dc}
  \]
  \[
  = 0.8 \cdot 400 = 320 \, V
  \]

Where:
- `m` = modulation index (here, 0.8)  
- `Vdc` = DC link voltage (here, 400 V)

---

## 📂 Contents

- `HB_FB_1ph_inverter.slx` → Simulink model containing both half-bridge & full-bridge circuits  
- `results/` → Simulation results plots 
- `README.md` → Project documentation  
- `LICENSE` → Apache-2.0 license 

---

## ▶️ Usage

1. Open `HB_FB_1ph_inverter.slx` in MATLAB/Simulink.
2. Run the simulation.
3. Inspect waveforms for both **half-bridge** and **full-bridge** inverters.
4. Modify `m` (modulation index) and `Vdc` to observe changes.

---

## 📖 Applications

- Power electronics education & research  
- Comparison of inverter topologies  
- Harmonic analysis & PWM studies  

---

## 👨‍💻 Author
**Hadi Rafat Talab**  
*GitHub:* [@hadi0r0t](https://github.com/hadi0r0t)  
*Email:* hadi0r0t@gmail.com
*Telegram:* @hadi0r0t



  Open to collaborations in power electronics, renewable energy systems, and control strategies.

