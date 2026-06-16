# Gesture Controlled Robot Using NRF24L01 and Arduino

An untethered, gesture-controlled robotic vehicle that translates physical hand movements into wireless directional commands. The system utilizes a glove- or hand-mounted transmitter to steer the robot chassis remotely, offering an intuitive, hardware-driven alternative to traditional joystick controllers.

---

## 📸 Project Showcase

(./<img width="900" height="800" alt="Overview of project 1" src="https://github.com/user-attachments/assets/f761ed90-eef5-4f64-8941-0260e87ee9bc" />)

*Figure 1: Wireless gesture-controlled robot chassis and transmitter assembly.*

---

## 🛠️ How It Works

* **The Transmitter (Hand/Glove Node):** An **Arduino Nano** reads positional data from a gesture sensor (like an accelerometer) and transmits the corresponding steering vectors wirelessly using an **NRF24L01 (2.4GHz)** radio module.
* **The Receiver (Robot Chassis):** An **Arduino Uno** equipped with a second NRF24L01 module catches the incoming radio signals. A **24V 47µF capacitor** is placed across the NRF module's power lines to suppress voltage ripples and ensure stable communication during motor spikes.
* **Motor Control:** The Arduino Uno decodes the signals and commands an **L298N Motor Driver** to regulate speed and direction for the dual-shaft gear motors and wheels.

---

## 🔋 Hardware Components Used

* **Microcontrollers:** Arduino Uno (Receiver Hub), Arduino Nano (Transmitter Node)
* **Wireless Transceivers:** NRF24L01 2.4GHz Radio Modules (2x)
* **Motor Driver:** L298N Dual H-Bridge Motor Driver
* **Actuators:** Dual-Shaft Gear Motors & High-Traction Wheels
* **Power Stability:** 24V 47µF Electrolytic Capacitor (For NRF voltage decoupling)
* **Power & Essentials:** Battery Packs, Battery Holders, and Breadboard Jumper Wires


(./

https://github.com/user-attachments/assets/2a84cee1-3fdb-4aa9-b5e4-2ac8d532b37f

)
