# 🔊 Power Amplifiers with BJTs

## ✨ Introduction
Power amplifiers are essential in audio systems, RF transmission, and motor control, where they boost small signals to **high power levels** to drive **speakers, actuators, and high-current loads**.

This repository provides detailed explanations, **schematics**, and **simulations** of various **power amplifier classes** and circuit designs using **BJT transistors**.

---

## ⚡ Power Amplifier Classes

### 1️⃣ **Class A Amplifier** (High Linearity, Low Efficiency)
- **How it Works**: The transistor conducts **100% of the time** (full cycle).
- **Pros**: Low distortion, high fidelity.
- **Cons**: Low efficiency (~25%-30%), high power dissipation.

📷 **Circuit Diagram:**  
![Class A Amplifier](./images/class_a_amplifier.png)

🛠 **Simulation Result:**  
![Simulation](./images/class_a_simulation.png)

---

### 2️⃣ **Class B Amplifier** (Higher Efficiency, Crossover Distortion)
- **How it Works**: Uses **two complementary transistors**; each conducts **50% of the time**.
- **Pros**: Efficiency up to **70%**.
- **Cons**: Crossover distortion at **zero crossing**.

📷 **Circuit Diagram:**  
![Class B Amplifier](./images/class_b_amplifier.png)

🛠 **Simulation Result:**  
![Simulation](./images/class_b_simulation.png)

---

### 3️⃣ **Class AB Amplifier** (Balanced Performance)
- **How it Works**: Uses **slight biasing** to keep both transistors slightly on, reducing crossover distortion.
- **Pros**: **Compromise** between Class A and B—better efficiency (~50-70%) and lower distortion.
- **Cons**: Requires careful biasing.

📷 **Circuit Diagram:**  
![Class AB Amplifier](./images/class_ab_amplifier.png)

🛠 **Simulation Result:**  
![Simulation](./images/class_ab_simulation.png)

---

### 4️⃣ **Class D Amplifier** (Switching Mode, High Efficiency)
- **How it Works**: Uses **PWM (Pulse Width Modulation)** and switching transistors.
- **Pros**: **Very high efficiency (~90%+), low heat dissipation**.
- **Cons**: Requires filtering to remove switching noise.

📷 **Circuit Diagram:**  
![Class D Amplifier](./images/class_d_amplifier.png)

🛠 **Simulation Result:**  
![Simulation](./images/class_d_simulation.png)

---

## 🔹 Implementation Circuits

### **Push-Pull Amplifier (Class B & AB)**
- Uses **two complementary BJTs** for **better efficiency**.
- Common in **audio applications**.
- **Solves** the low-efficiency issue of Class A but introduces **crossover distortion**.

📷 **Circuit Diagram:**  
![Push-Pull Amplifier](./images/push_pull_amplifier.png)

🛠 **Simulation Result:**  
![Simulation](./images/push_pull_simulation.png)

---

### **Darlington Power Amplifier**
- Uses a **Darlington pair** (two BJTs in cascade) for **very high current gain**.
- Common in **Class A & AB amplifiers**.

📷 **Circuit Diagram:**  
![Darlington Amplifier](./images/darlington_amplifier.png)

🛠 **Simulation Result:**  
![Simulation](./images/darlington_simulation.png)

---

## 📊 Comparison of Amplifier Classes
| Class | Efficiency | Distortion | Heat Dissipation | Application |
|--------|------------|------------|------------------|-------------|
| **Class A** | ~25-30% | Low | High | Hi-Fi audio |
| **Class B** | ~70% | High (Crossover) | Medium | RF, PA systems |
| **Class AB** | ~50-70% | Low | Medium | Audio, Power amps |
| **Class D** | ~90%+ | PWM artifacts | Low | Subwoofers, Wireless |

---

## 🔥 Conclusion
Understanding **power amplifier classes** and their circuit implementations allows engineers to choose the right design for different applications. Push-pull and Darlington designs improve efficiency and gain, making them vital for **audio and RF systems**.

✅ **Class A** – Best linearity, worst efficiency.  
✅ **Class B** – Efficient, but has crossover distortion.  
✅ **Class AB** – Best balance between distortion and efficiency.  
✅ **Class D** – Best for high-power, low-heat applications.

---

📌 **Next Steps**: Try simulating these circuits using **LTSpice**, **Proteus**, or **Multisim** to visualize their performance! 🚀
