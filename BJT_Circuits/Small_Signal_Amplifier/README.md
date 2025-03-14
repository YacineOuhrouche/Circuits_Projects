# 📘 Small-Signal Amplifiers Using BJT (NPN)

## ✨ Introduction
Small-signal amplifiers are fundamental analog circuits used to amplify weak signals while preserving their shape. These amplifiers are widely used in audio processing, sensor signal conditioning, and RF communication.

This repository contains explanations, schematics, and simulation results for different types of **small-signal amplifiers using BJT (NPN)**.

---

## 🔹 Types of Small-Signal Amplifiers
Small-signal amplifiers can be classified based on their transistor configurations:

1. **Common-Emitter (CE) Amplifier** – High voltage & current gain
2. **Common-Collector (CC) (Emitter Follower)** – Buffer, impedance matching
3. **Common-Base (CB) Amplifier** – High-frequency applications

---


## 1️⃣ Common-Emitter (CE) Amplifier

### 📌 Circuit Description
- **Input Signal:** Applied to the **base**.
- **Output Signal:** Taken from the **collector**.
- **Emitter:** Connected to ground (or through an emitter resistor for stability).
- **Biasing:** Uses voltage divider biasing to maintain transistor in active region.
- **Phase Shift:** The output is **180° out of phase** with the input.

### ⚡ How It Works
- When the **input signal increases**, the transistor conducts more, pulling the **collector voltage down**, causing **inversion**.
- When the **input signal decreases**, the transistor conducts less, raising the **collector voltage**.
- This results in **high voltage gain** and **moderate input impedance**.

### 📷 Schematic Diagram

![Screenshot 2025-03-15 143407](https://github.com/user-attachments/assets/f402c8be-ce1f-4dcb-9baf-73af8304d364)

### 🛠 Simulation Result

![Screenshot 2025-03-15 143419](https://github.com/user-attachments/assets/2fb35035-b8ab-46ed-b778-2dba7034d4ec)

---

## 2️⃣ Common-Collector (CC) Amplifier (Emitter Follower)

### 📌 Circuit Description
- **Input Signal:** Applied to the **base**.
- **Output Signal:** Taken from the **emitter**.
- **Collector:** Connected to power supply.
- **Phase Shift:** The output is **in-phase** with the input.

### ⚡ How It Works
- Provides **no voltage gain** but **high current gain**.
- Acts as a **buffer**, preventing signal loss due to impedance mismatch.
- Output voltage **follows** input voltage, making it useful for **impedance matching**.

### 📷 Schematic Diagram


### 🛠 Simulation Result


---

## 3️⃣ Common-Base (CB) Amplifier

### 📌 Circuit Description
- **Input Signal:** Applied to the **emitter**.
- **Output Signal:** Taken from the **collector**.
- **Base:** Held at a fixed voltage (common reference).
- **Phase Shift:** The output is **in-phase** with the input.

### ⚡ How It Works
- **Low input impedance**, making it useful for **high-frequency applications**.
- **High voltage gain**, suitable for **RF amplifiers**.
- **No current gain** (current gain ≈ 1).

### 📷 Schematic Diagram


### 🛠 Simulation Result


---

## 📌 Applications of Small-Signal Amplifiers
✅ **Audio amplification** – Used in microphones, speakers, and hearing aids.
✅ **Sensor signal processing** – Amplifies weak signals from temperature and motion sensors.
✅ **RF communication** – Used in radio frequency circuits for signal amplification.
✅ **Impedance matching** – Ensures maximum power transfer in electronic circuits.

---

## 📌 Summary Table
| Amplifier Type | Gain | Input Impedance | Output Impedance | Phase Shift |
|---------------|------|----------------|-----------------|------------|
| **Common-Emitter** | High | Medium | Medium | **Inverted** |
| **Common-Collector** | ~1 | High | Low | **No Inversion** |
| **Common-Base** | High | Low | High | **No Inversion** |

---

## 💡 Conclusion
Small-signal amplifiers are crucial in electronics for amplifying weak signals without distortion. Understanding their working principles helps in designing efficient analog circuits.












