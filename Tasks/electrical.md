![Team Banner](/images/Team%20Banner.png)

# ⚡ Team Prometheus — Electrical Recruitment Task 2026–27

Welcome to the **Electrical Team Recruitment 2026–27** for **Team Prometheus**.  
This repository contains **two tasks** designed to evaluate your understanding of electrical engineering concepts, circuit design, and hardware integration in the context of **robotic soccer**.

---

## 🧩 Task 1: Balance and Motion Control System

### 🔍 Overview
In this task, you will:

- **Design a Balance Control Prototype** in TinkerCAD  
  - Use an **MPU6050** to detect tilt and orientation.  
  - Interface the sensor with an **Arduino** or **ESP32** microcontroller.  
  - Use **servo motors** to simulate real-time balancing correction.

- **Implement Feedback & Safety Indicators**  
  - Use **LEDs** or a **buzzer** to indicate loss of balance or error states.  
  - Display real-time sensor readings (angles or acceleration) on the **Serial Monitor**.

### 💡 Clarification
A **Balance and Motion Control System** is crucial in humanoid robots to help them remain upright and recover from disturbances — similar to how humans adjust their body posture.

### 📦 Deliverables
- A **TinkerCAD** simulation showing active balance correction using feedback control.  
- **Arduino implementation** of sensor-based motion correction.  
- A **report** including:
  - Component justification (e.g., why MPU6050, why servos, etc.)  
  - Control logic explanation (how tilt translates to motor correction)  
  - Relevance of the system in humanoid soccer applications  

---

## 🔋 Task 2: Power and Sensor Management PCB

### 🔍 Overview
In this task, you will:

- **Design a Single-Layer PCB** for Power Distribution and Sensor Integration  
  - Include a **microcontroller (ESP32)**  
  - Add ports for **sensors** (MPU6050, ultrasonic, temperature) and **servo outputs**  
  - Implement **voltage regulation (LM7805)**  
  - Use **diagnostic LEDs** to indicate power and signal status.

### 🎯 Focus Areas
- Clean and compact routing suitable for a humanoid robot’s constrained structure.  
- Stable power delivery and minimal electrical noise.  
- Expandability for future sensor or actuator modules.  

### 💡 Clarification
Your PCB should act as a **central hub** connecting the robot’s sensors, actuators, and control unit — think of it as the **“nervous system”** of your humanoid robot.

### 📦 Deliverables
- **Schematic and PCB layout** (KiCad, Eagle, or Altium).  
- **Gerber files** ready for fabrication(optional).  
- A **report** detailing:
  - Design reasoning and component selection.  
  - PCB layout strategy (trace routing, decoupling, ground plane usage).  
  - Challenges faced and how they were resolved.  

---

## 📘 Summary
| Task | Description | Tools | Key Deliverables |
|------|--------------|--------|------------------|
| **Task 1** | Balance and Motion Control | TinkerCAD, Arduino/ESP32 | Simulation, Code, Report |
| **Task 2** | Power & Sensor Management PCB | KiCad/Eagle/Altium | Schematic, PCB, Gerber, Report |

---

### 🧠 Note
> Ensure all your files are **clearly named**, your **simulation links are accessible**, and your **report is concise yet descriptive**.

---

**Team Prometheus — Electrical Recruitment Task 2026–27**
