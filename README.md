# 🔥 Simple Fire Alarm Circuit (Electronics Project)

A compact and beginner-friendly **fire detection system** built using basic electronic components.  
This project demonstrates how **infrared radiation from flames** can activate a transistor-based alarm system without requiring any microcontroller or programming.

---

## 📌 Project Overview

This fire alarm system uses an **IR LED** to sense infrared emissions from a flame. When fire is detected, a **BC547 transistor** gets activated, which triggers an **LED indicator** and a **buzzer**, giving both visual and audible alerts.

The design is simple, low-cost, and suitable for students, hobbyists, and academic electronics labs.

---

## 🎯 Objectives

- Build a **low-cost and compact fire detection circuit**
- Demonstrate **IR-based flame sensing**
- Provide **visual and audible alerts**
- Create a project suitable for **electronics lab courses**

---

## ✨ Features

- ✔️ Simple & cost-effective  
- ✔️ Beginner-friendly (no microcontroller needed)  
- ✔️ Works on a standard **9V battery**  
- ✔️ Quick response to flame/IR radiation  
- ✔️ Dual alert: **LED + Buzzer**  
- ✔️ Portable and easy to assemble on a breadboard  
- ✔️ Low power consumption  

---

## 🧰 Components Used

| Component        | Specification / Details       |
|------------------|-------------------------------|
| Transistor       | BC547 (NPN)                   |
| Resistor         | 460 Ω                         |
| Infrared LED     | Standard IR LED               |
| Indicator LED    | 5mm LED                       |
| Buzzer           | 5V passive buzzer             |
| Power Supply     | 9V battery                    |
| Breadboard       | For circuit assembly          |
| Wires            | Jumper wires                  |

---

## 🔧 How the Circuit Works

1. The **IR LED continuously emits infrared rays**.
2. In normal conditions, the transistor remains **OFF**, keeping LED and buzzer inactive.
3. When a flame is brought near the IR LED:
   - The flame emits IR radiation.
   - This changes the IR LED's behavior.
4. The **BC547 transistor gets triggered**.
5. Current flows through collector → emitter.
6. The LED lights up and the buzzer sounds, indicating the presence of fire.

---

## 📐 Circuit Diagram

> *(Include your circuit diagram image here, e.g., `circuit.png`)*

```bash
![Circuit Diagram](circuit.png)
