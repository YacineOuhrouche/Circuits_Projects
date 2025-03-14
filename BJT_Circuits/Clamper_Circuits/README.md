# 📘 Clamper Circuits – A Comprehensive Guide

## ✨ Introduction
Clamper circuits, also known as **DC level shifters**, are electronic circuits that **add** or **subtract** a DC voltage to an AC signal without changing its shape. They are commonly used in TV receivers, oscilloscopes, and signal processing applications.

## 🔹 Types of Clamper Circuits
Clamper circuits can be categorized into different types based on the polarity of the clamping voltage:

1. **Positive Clamper**
2. **Negative Clamper**
3. **Biased Clamper** (With a DC bias voltage)
4. **Combination Clampers**

---

## 📌 Positive Clamper Circuit
📷 **Schematic Diagram:**

🔹 **How It Works:**
- The **diode** is placed in **parallel** with the output and conducts during the **negative half-cycle**.
- During this time, the **capacitor** charges to the peak value of the AC signal.
- During the **positive half-cycle**, the capacitor shifts the waveform **upward**, ensuring that the entire waveform moves **above** the zero reference level.



## 📌 Negative Clamper Circuit
📷 **Schematic Diagram:**


🔹 **How It Works:**
- The **diode is reversed**, so it **conducts during the positive half-cycle**.
- The **capacitor charges** to the peak voltage and shifts the entire waveform **downward**, keeping the waveform below the zero reference.

---

## 📌 Biased Clamper Circuit
📷 **Schematic Diagram:**



🔹 **How It Works:**
- A **DC bias voltage** is added in series with the **diode**.
- This allows us to shift the waveform to a **specific DC level**.
- Used in **TV receivers** and **oscilloscopes** to adjust signal positioning.

---

## 📌 Applications of Clamper Circuits
✅ **Waveform Shifting** – Moves signal up or down in voltage.
✅ **DC Restoration** – Used in TV receivers to restore signal levels.
✅ **Oscilloscope Positioning** – Adjusts the reference level of signals.
✅ **Modulation Circuits** – Used in AM and FM communication systems.

---

## 📌 Summary Table
| Type of Clamper | Function |
|----------------|----------|
| **Positive Clamper** | Moves waveform **upward** |
| **Negative Clamper** | Moves waveform **downward** |
| **Biased Clamper** | Moves waveform to a **specific DC level** |

---

## 💡 Conclusion
Clamper circuits are essential in **signal processing** and **waveform adjustment** applications. They help shift signals to a desired **DC reference level** while **preserving the waveform's shape**.


