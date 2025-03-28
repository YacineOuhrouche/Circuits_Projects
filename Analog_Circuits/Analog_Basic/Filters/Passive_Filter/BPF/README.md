# 🎛️ Band Pass Filter

Welcome to the **Band Pass Filter** project repository! 🎉  
This project demonstrates how to design and build a **Band Pass Filter (BPF)** — a fundamental circuit in analog electronics.

---

## 🧰 What is a Band Pass Filter?

A **Band Pass Filter** is an electronic circuit that **allows a specific range of frequencies to pass while attenuating (blocking) frequencies outside this range**. It combines both **high-pass and low-pass filtering** to isolate a desired frequency band.

---

## 🛠️ What Does It Do?

The Band Pass Filter is often used to:

✅ Extract a specific frequency range (e.g., radio stations)  
✅ Reduce noise outside the target frequency band  
✅ Enhance features in audio and signal processing  

---

## 📐 Schematic Diagram

### Image:

![Screenshot 2025-03-08 112111](https://github.com/user-attachments/assets/c60a31b4-d963-482c-9aa3-0a797ce38878)

---

## 📊 What is a Bode Plot?

A **Bode plot** is a graph used to visualize how a circuit's gain (output signal strength) varies with frequency. It has two key components:

### 📈 Magnitude Plot (dB Gain vs. Frequency)
- Shows how much a signal is **amplified or attenuated** at different frequencies.
- **Frequencies below the lower cutoff** are attenuated (**negative dB gain**).
- **Frequencies above the upper cutoff** are also attenuated.
- **Frequencies within the passband** remain unaffected (**0 dB gain**).

### 🔄 Phase Plot (Phase Shift vs. Frequency)
- Shows how the signal's **phase changes** as frequency increases.
- At **low frequencies**, phase shift starts at **+90°** (like HPF).
- At the **center frequency**, phase shift is **0°**.
- At **high frequencies**, phase shift approaches **-90°** (like LPF).

---

## 📏 Cutoff Frequencies

A **Band Pass Filter** has two important cutoff frequencies:

1. **Lower Cutoff Frequency** (\(f_L\)): This is the frequency below which the filter attenuates the signal. Frequencies lower than \(f_L\) are blocked.

2. **Upper Cutoff Frequency** (\(f_H\)): This is the frequency above which the filter attenuates the signal. Frequencies higher than \(f_H\) are blocked.

The **bandwidth** of the filter is the difference between the upper and lower cutoff frequencies:

\[
\text{Bandwidth} = f_H - f_L
\]

The center frequency (\(f_c\)) of the filter, which is where the maximum signal passes through with no attenuation, is given by the formula:

\[
f_c = \sqrt{f_L \cdot f_H}
\]

Where:
- \(f_L\) is the lower cutoff frequency.
- \(f_H\) is the upper cutoff frequency.

---

## 💻 Applications

- **Wireless Communication** (isolating specific frequency bands)  
- **Audio Processing** (enhancing specific tones)  
- **Biomedical Signal Processing** (extracting ECG or EEG signals)  

---

## 🧰 Tools Used

- **Falstad Circuit Simulator** for quick testing  
- **Oscilloscope** to view real-world output  
