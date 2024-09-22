# ⚙️ **AT89C51_LCD_Frequency_Counter_Assembly_Proteus**

A Frequency Counter using the **8051 MCU (AT89C51)** and **Assembly Language Programming**.

<p align="center">
  <img src="https://user-images.githubusercontent.com/78910261/202845941-c30e82bc-39cf-4593-b0f1-e8936b186b6c.png" alt="AT89C51 Frequency Counter" width="70%">
</p>

---

## 📖 **Overview**

This project demonstrates a **Frequency Counter** using the **[AT89C51](https://www.atmel.com/products/microcontrollers/8051.aspx)** Microcontroller, part of the **[8051 MCU](https://en.wikipedia.org/wiki/Intel_MCS-51)** family. The frequency measurement is displayed on an **LCD** and controlled via external components, making it an excellent tool for various applications in electronics and communications.

The program is written in **[Assembly language](https://en.wikipedia.org/wiki/Assembly_language)**, optimized for efficiency and speed, and the circuit is simulated using **[Proteus](https://www.labcenter.com/)** (Version 8.9). This repository includes:
- **[Assembly Code](https://en.wikipedia.org/wiki/Assembly_language)** for the frequency counting algorithm
- **Precompiled HEX File** for easy microcontroller programming
- **[Proteus Simulation Circuit](https://www.labcenter.com/)** demonstrating the project functionality

The project has been successfully tested on both simulation and real hardware setups, ensuring reliability and accuracy.

---

## 🔑 **Keywords**

**[AT89C51 Microcontroller](https://www.atmel.com/products/microcontrollers/8051.aspx)** | 
**[8051](https://en.wikipedia.org/wiki/Intel_MCS-51)** | 
**[Assembly Language](https://en.wikipedia.org/wiki/Assembly_language)** | 
**[Simulation](https://www.labcenter.com/)** | 
**[Proteus](https://www.labcenter.com/)** | 
**[Microcontroller Programming](https://en.wikipedia.org/wiki/Microcontroller)** | 
**[Frequency Counter](https://en.wikipedia.org/wiki/Frequency_counter)**

---

## ⚙️ **Key Features**

<div align="center">

| Feature                      | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| 📏 **Frequency Measurement**    | Accurately measures frequency and displays it on a high-contrast LCD        |
| 🎛️ **Control Interface**       | User-friendly interface controlled via external push buttons                |
| 🖥️ **Proteus Simulation**      | Ready-to-use simulation circuit compatible with Proteus 8.9                |
| 💾 **Assembly Programming**    | Optimized assembly code for efficient execution on the AT89C51              |
| 🛠️ **Real Hardware Support**   | Successfully tested on actual hardware for reliable performance              |

</div>

---

## 📦 **Contents**

<div align="center">

| File                          | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| `AT89C51_Frequency_Counter.asm`  | Assembly source code for the AT89C51 microcontroller                        |
| `AT89C51_Frequency_Counter.hex`  | Precompiled HEX file for direct microcontroller upload                      |
| `Proteus_Simulation.pdsprj`    | Proteus Design Suite simulation file                                        |
| **Screenshots**                | Visual demonstrations from the Proteus simulation                          |

</div>

---

## 🛠️ **Hardware & Circuit Information**

<div align="center">

| Hardware Component             | Description                                                                 |
|---------------------------------|-----------------------------------------------------------------------------|
| **AT89C51 Microcontroller**     | Central unit managing frequency measurement and display                     |
| **LCD**                         | 16x2 LCD for visual output of the frequency value                          |
| **Push Buttons**                | Controls for starting/stopping measurement and resetting the display        |
| **Transistors (e.g., NPN)**     | Used to interface the microcontroller with the LCD and other components     |
| **Resistors**                   | Current-limiting resistors to protect components from overcurrent          |
| **Power Supply**                | A 5V DC power supply for the microcontroller and LCD circuit               |

</div>

---

### **Circuit Explanation**:

The **LCD** in this project displays the measured frequency, with the microcontroller processing input signals from an external source to calculate frequency values. The LCD provides a clear readout, making it easy to monitor frequency in real time.

Each control component, such as push buttons, is connected to input pins on the microcontroller. Resistors are used throughout the circuit to ensure proper current control, preventing damage to the microcontroller and display.

---

## 🖥️ **Installation & Usage**

### **Step-by-Step Guide:**

1. **Clone this repository**:
   ```bash
   git clone https://github.com/gmostofabd/AT89C51_LCD_Frequency_Counter.git
   ```

2. **Compile the Assembly Code**:
   Open the `AT89C51_Frequency_Counter.asm` file in **MIDE-51** or any compatible IDE, and compile it to generate the **HEX file**.

3. **Simulate in Proteus**:
   Open **Proteus Design Suite**, load the provided simulation file, and run the simulation to observe the frequency measurement.

4. **Program the Microcontroller**:
   For real hardware applications, upload the **HEX file** to the AT89C51 microcontroller using a compatible programmer.

5. **Test the Circuit**:
   Assemble the hardware according to the provided circuit diagram, power it on, and verify the functionality by pressing the control buttons.

---

## 🔗 **Additional Information**

### **LCD Display**:
The **16x2 LCD** displays the frequency value measured by the microcontroller. The data is updated in real time, providing immediate feedback on the measurement process.

### **Push Button Functionality**:
- **Start/Stop Button**: Begins or halts the frequency measurement.
- **Reset Button**: Resets the measured frequency value to zero.

For a deeper understanding of the circuit and code, explore the **Proteus simulation** and review comments within the assembly source file for explanations of specific code sections.

---

## 🤝 **Contributing**

We welcome contributions! If you have suggestions for improvements or additional features, feel free to submit pull requests or open issues regarding any bug fixes, feature enhancements, or optimizations to the assembly code.

---

## 📧 **Contact**

For any inquiries, feedback, or assistance, please reach out at [mostofa.melab@gmail.com](mailto:mostofa.melab@gmail.com).

---

<p align="center">
  <img src="your-contact-graphic.png" alt="Contact Graphic" width="50%">
</p>

If you found this project helpful, please give it a ⭐ on GitHub!
```
