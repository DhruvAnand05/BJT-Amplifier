# ⚡ BJT Common Collector Amplifier – ELECENG 2EI4 (McMaster University)

## 📖 Project Overview  
This project focused on the **design, simulation, and testing** of a **BJT common collector amplifier** for McMaster University’s **ELECENG 2EI4** course.  
The circuit was designed to achieve a **midband gain ≥ 0.9** while operating linearly at **1 kHz, 1 Vpp input**.  

🎥 **Project Video:** [Watch on YouTube](https://youtu.be/C1Gav9spkGM)  

---

## 🛠️ Tools & Components  
- **OrCAD PSpice** – Circuit simulation  
- **Analog Discovery 3 (AD3)** – Hardware testing  
- **WaveForms Software** – Data visualization & spectrum analysis  
- **2N3904 NPN BJT**, **10 kΩ bias resistors**, **100 Ω load resistor**  
- **Capacitors:** 10 µF (input coupling), 100 nF (output coupling)  

---

## 🔍 Design Details  
- **Transistor:** 2N3904 (β ≈ 100)  
- **Topology:** Common Collector (emitter follower)  
- **Biasing:** 2 × 10 kΩ resistors (parallel equivalent 5 kΩ)  
- **Theoretical Gain:** 0.961 (meets requirement ≥ 0.9)  
- **Power Rails:** ±5 V  

---

## 📊 Simulation Results (PSpice)  
- **Gain:** 0.926  
- **Linearity:** Maintained at 1 kHz input, no significant distortion  
- **Phase Shift:** Minimal, only noticeable at higher frequencies  
✅ Design satisfied all project specifications  

---

## 🔬 Physical Implementation & Testing  
- Circuit assembled on breadboard and tested with AD3  
- **Measurements:**  
  - Input vs Output waveform comparison  
  - Gain Plot (XY mode → consistent slope)  
  - Spectrum Analysis → all input frequencies preserved at output  
- **Observed Gain:** ~0.93 (close to theory & simulation)  
- **Noted Noise:** Present at input (from AD3 hardware, not the circuit)  

---

## 🚀 Key Learnings  
- Tradeoffs of **BJT vs MOSFET** for low-current amplifier design  
- Practical differences between **simulation and hardware performance**  
- Validating **linearity through spectrum analysis**  
- Influence of test equipment on measured results  

---

## 📚 References  
1. ELECENG 2EI4 Lab Guide – *Amplifier Design*  
2. ON Semiconductor – *2N3904 Datasheet*  
3. PSpice Simulation Documentation  

---

✍️ **Author:** Dhruv Anand  
📅 **Date:** February 2025  

---
