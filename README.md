# EMG-Based Muscle Strength Indicator

This project is an **Electromyography (EMG)-based Strength Indicator** that visually represents muscle activation levels using LEDs. It uses dry electrodes, analog signal processing, and a comparator-driven LED display to give real-time muscle feedback. This is ideal for physiotherapy, prosthetics, sports analysis, and educational purposes.

---

## 📦 Features

- Real-time feedback of muscle activity
- Signal conditioning with amplifier, filters, and rectifier
- LED indication for strength levels
- Affordable and beginner-friendly
- Modular circuit design for easy learning

---

## 📊 Block Diagram

The following block diagram illustrates the system flow:

![Block Diagram](images/block_diagram.png)

---

## 🔌 Circuit Diagram

This project consists of three major analog circuit stages:

### 1. INA128 Instrumentation Amplifier  
Amplifies the differential EMG signals from the electrodes.

![INA128 Amplifier Circuit](images/ina128_circuit.png)

---

### 2. Sallen-Key Low-Pass Filter  
Filters out high-frequency noise from the amplified EMG signal.

![Low-Pass Filter Circuit](images/low_pass_filter.png)

---

### 3. Full-Wave Precision Rectifier  
Converts the AC EMG signal into a unipolar (positive-only) signal suitable for LED comparison.

![Precision Rectifier Circuit](images/rectifier_circuit.png)

---

## 🔨 Breadboard Layout

The layout below shows how to implement the circuit on a breadboard for prototyping.

![Breadboard Layout](images/breadboard_layout.png)

> Tip: Keep analog signal lines short and use a common ground for all modules.

---

## 🧪 Applications

- **Physiotherapy:** Muscle engagement monitoring for rehab patients
- **Prosthetics:** Detect muscle signals to trigger movement
- **Sports Science:** Analyze muscle performance during exercise
- **Education:** Demonstrates core bio-signal processing concepts

---

## 📷 Demo

Here’s a demo of the system in action:

![Demo GIF](images/demo.gif)

---

## 📁 Folder Structure

