# dc-motor-PID-simulink
MATLAB/Simulink project for modeling and controlling a DC motor using a PID controller. Includes a plant model, closed-loop feedback, and scope visualization of motor position response.
# ⚙️ DC Motor Control with PID (Simulink)

This project demonstrates the **modeling and control of a DC motor** using **MATLAB/Simulink**.  
It consists of a **plant model** (the DC motor) and a **PID controller** for regulating the motor shaft position.

---

## 📌 Project Overview

### 🔹 Plant Model
- The DC motor is modeled as a **Simulink subsystem**.
- **Input:** Armature voltage  
- **Output:** Shaft position  
- Includes:
  - Armature current dynamics
  - Mechanical dynamics (angular speed & position)
  - State integrators for motor behavior

### 🔹 PID Controller
- A **PID block** regulates the motor position.  
- The controller compares the **desired reference position** with the **actual motor position** and adjusts the input voltage.  
- The closed-loop system ensures **stability, accuracy, and fast response**.

---

## 🛠️ Features
- Realistic **DC motor mathematical model**
- **PID tuning** for better control performance
- Modular design:
  - `Plant model of DC motor` subsystem
  - `PID(s)` controller subsystem
- **Scope visualization** to observe system response

---

## 📈 Applications
This project serves as a foundation for:
- Learning **motor control systems**
- Practicing **PID tuning**
- Extending to advanced control strategies (LQR, adaptive control, state observers, etc.)

---

## ▶️ How to Run
1. Open the project in **MATLAB Simulink**.
2. Run the simulation.
3. Adjust PID parameters (`Kp`, `Ki`, `Kd`) to observe changes in response.
4. Check the **scope output** for system performance.

---

## 📷 System Diagrams

### Plant Model of DC Motor
![DC Motor Plant](images/dc_motor_plant.png)

### Closed-Loop System with PID
![DC Motor with PID](images/dc_motor_pid.png)

---



---
