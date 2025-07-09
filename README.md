#  IR Sensor Module – LM358 Based

This project implements a simple **Infrared (IR) proximity sensor** using an IR LED, photodiode, and an LM358 operational amplifier configured as a voltage comparator. Designed for object detection tasks, the circuit generates a digital output when IR light is reflected from a nearby surface.

---

##  Circuit Description

- **IR LED** emits infrared light continuously.
- **Photodiode** receives reflected IR light and generates a corresponding voltage signal.
- **LM358 Op-Amp** compares the photodiode signal with an adjustable reference voltage (set by RV1).
- **Output Pin (0/P)** goes HIGH when an object is detected (voltage crosses the threshold).

---

##  Components

| Component   | Description                            |
|------------|----------------------------------------|
| IR LED      | Infrared emitter for sensing          |
| Photodiode  | Reflective light detector              |
| LM358       | Dual Op-Amp IC used in comparator mode|
| Resistors   | R1, R2, R3 to set gain and bias        |
| Potentiometer (RV1) | Sensitivity threshold adjust |
| Output Pin  | Digital signal when object is detected|

---
##  Applications

- Obstacle detection for robotics
- Line-following robot modules
- Hand gesture triggers
- Proximity detection for automation

---

##  Notes

- Adjust RV1 for optimal sensitivity under ambient lighting
- Ensure IR LED and photodiode are mounted parallel to detect reflected light
- Output can be interfaced directly with microcontrollers (e.g., ESP32, Arduino)

---

##  Designed By

**Himanshu Kumar**  
Embedded Systems & Circuit Design Enthusiast
