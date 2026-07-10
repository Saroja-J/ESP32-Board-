# 📡 ESP32-WROOM-32D Development Board

A custom **ESP32-WROOM-32D Development Board** designed in **KiCad** for IoT and embedded applications. The board integrates USB-to-UART programming, power management, automatic reset and boot circuitry, and GPIO expansion, providing a compact platform for developing Wi-Fi and Bluetooth-enabled systems.

---

## 📖 Overview

This project is based on the **ESP32-WROOM-32D**, a Wi-Fi and Bluetooth-enabled microcontroller module from Espressif. The board includes a **CH340C USB-to-UART interface**, **LM2596 buck converter**, automatic reset and boot circuitry, GPIO headers, and supporting passive components. It supports **UART, SPI, I²C, PWM, ADC, and GPIO** interfaces, making it suitable for IoT, embedded systems, automation, and rapid prototyping.

---

## 📷 PCB Images

> Add your PCB images below.

| 2-Layer PCB | 4-Layer PCB |
|--------------|--------------|
| <img width="825" height="739" alt="Image" src="https://github.com/user-attachments/assets/1b99829b-7a14-4b55-9ef7-00a02ba3b1c0" /> | <img width="825" height="739" alt="Image" src="https://github.com/user-attachments/assets/1b99829b-7a14-4b55-9ef7-00a02ba3b1c0" />|

---

## ⚙️ Working

1. The board is powered through USB or an external power source.
2. The **LM2596 buck converter** provides a regulated power supply for the board.
3. The **CH340C** enables USB-to-UART communication for programming and serial debugging.
4. The automatic **Reset** and **Boot** circuit allows easy firmware uploading.
5. After programming, the ESP32 communicates with external peripherals through its GPIO and communication interfaces.

---

## ✨ Features

-  ESP32-WROOM-32D Wi-Fi & Bluetooth Module
-  CH340C USB-to-UART Interface
-  LM2596 Buck Converter
-  Automatic Reset & Boot Circuit
-  GPIO Expansion Headers
-  Supports UART, SPI, I²C, PWM & ADC
-  Designed using KiCad

---

## 🛠️ Components

| Component | Description |
|-----------|-------------|
| ESP32-WROOM-32D | Main Wi-Fi & Bluetooth microcontroller |
| CH340C | USB-to-UART programming interface |
| LM2596 | Buck converter for power regulation |
| USB Connector | Power input and programming |
| NPN Transistors | Automatic Reset & Boot switching |
| Push Buttons | Manual Reset & Boot |
| Capacitors | Power filtering and decoupling |
| Resistors | Pull-up, pull-down and current limiting |
| GPIO Headers | External peripheral connections |

---

## 🚀 Applications

- 🌐 Internet of Things (IoT)
- 🏠 Home Automation
- 🤖 Robotics
- 📡 Wireless Sensor Nodes
- 📊 Data Logging
- 🎛️ Embedded System Development

---

## 📐 Design Details

- Designed by referring to the **ESP32-WROOM-32D Datasheet**, **Hardware Design Guidelines**, and supporting component datasheets.
- Recommended resistor and capacitor values were used throughout the design.
- Decoupling capacitors were placed close to the ESP32 power pins for stable operation.
- A copper-free keep-out zone was maintained around the ESP32 antenna for better RF performance.
- NPN transistors were used for the automatic **Reset** and **Boot** switching circuit.
- The **4-layer PCB** uses copper-filled planes for improved power distribution and grounding.
- Both the **2-layer** and **4-layer** PCB designs were completed with **0 DRC errors**.
- The **LM2596** buck converter was designed using its datasheet. For different input voltages or output currents, refer to the datasheet to select the appropriate inductor and capacitor values.
- An **ESD protection diode** recommended in the ESP32 Hardware Design Guidelines is **not included** in this revision and can be added in future designs.

---

## 📄 License

This project is shared for **educational and learning purposes**.
