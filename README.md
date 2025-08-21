# Servo Motors Project

**Arduino-based control system for 6 servo motors.**

---

## 🔧 Project Description
This project demonstrates how to control **six servo motors** using an Arduino.  
The servos first run a **sweep motion** for 2 seconds, then automatically return and stay fixed at **90°** (neutral position).

In addition, a simple **walking algorithm** was designed for a humanoid robot using servo motors.

---

## 🦾 Walking Algorithm
1. All servos start at 90° (standing position).
2. Move the **right leg** forward:
   - Increase right hip angle.
   - Bend right knee.
3. Shift body weight onto the right leg.
4. Return the right leg to neutral.
5. Repeat the same sequence with the **left leg**.
6. Alternate between legs → continuous walking motion.

---

## 📂 Files
- `servo_control.ino` → Arduino code for servo sweep + neutral position.
- `README.md` → Project documentation & walking algorithm.


---

## 📸 Preview
<img width="600" alt="Servo Robot" src="https://github.com/user-attachments/assets/416b63e5-399d-420a-ac45-43ef7ac7a678" />

---


