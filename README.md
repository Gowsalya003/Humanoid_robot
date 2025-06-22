# Humanoid_robot# Humanoid Robot Servo Control (Arduino)

This project controls a humanoid robot using **Arduino** and **servo motors** to perform multiple movements like:
- Standing straight
- Saying Hi 👋
- Shaking hand 🤝
- Performing a custom **"Maan Karate"** move 🥋

It uses the **Servo** library for smooth control of multiple servo motors attached to different parts of the humanoid robot.

## 🤖 Features
- Controls **15 servo motors** for **head**, **right hand**, **left hand**, **right leg**, and **left leg**.
- Predefined sequences for:
  - **stand_straight()**
  - **say_hi()**
  - **shake_hand()**
  - **maan_karate()** → Simulates a dramatic karate-like move.
- Real-time debugging via **Serial Monitor**.

## ⚙️ Hardware Requirements
- **Arduino Mega 2560** (recommended for handling multiple servos)
- **15x Servo Motors** (SG90 / MG90S)
- **External 5V Power Supply** for servos
- Jumper wires or custom PCB
- Optional: **PCA9685** Servo Driver if expanding further

## 🗂️ Servo Mapping (Pin Connections)
| Body Part | Servo Pins  |
|-----------|-------------|
| Head      | 28          |
| Right Hand | 30, 31, 32  |
| Right Leg | 33 → 37     |
| Left Hand  | 38 → 40     |
| Left Leg   | 41 → 45     |

## 🖥️ Software Requirements
- **Arduino IDE** → https://www.arduino.cc/en/software
- **Servo** library (pre-installed in Arduino IDE)

## 🚀 How to Run
1. Connect your Arduino Mega board.
2. Open this project in the Arduino IDE.
3. Go to **Tools → Board → Arduino Mega or Mega 2560**.
4. Select the correct **Port** for your Arduino.
5. Click **Upload**.
6. Open the **Serial Monitor (9600 baud)** to see status logs.

## 🎬 Available Actions
| Function Name  | Action                       |
|----------------|------------------------------|
| `stand_straight()` | Neutral balanced standing position  |
| `say_hi()`        | Waves the right hand             |
| `shake_hand()`    | Performs handshake gesture       |
| `maan_karate()`   | Dramatic karate-style movement   |

## 📦 Project Structure
