# 🧲 Modular Electromagnetic Complex & Autonomous Infrastructure "Sarai v2.0"

## 🏛️ Project Overview
This repository contains the complete open-source hardware blueprints, schematics, and embedded source code for the **Modular Electromagnetic 3-Stage Complex v1.2** and associated autonomous civilian safety infrastructure, developed independently in Staraya Kupavna, Moscow Oblast.

The project transitions seamlessly between a portable handheld configuration and a stationary automated turret system utilizing custom mechanical gearboxes and an AI-driven computer vision layer.

---

## 🛠️ System Architecture & Subsystems

### 1. 🧲 Propulsion & Control Unit (Gauss Gun v1.2)
* **Logic Core:** Arduino Nano (ATmega328P) handling nanosecond-level switching loops.
* **Power Delivery:** 19V laptop power supply boosted via high-power DC-DC Step-Up converters to a stable 40V bus.
* **Energy Storage:** Low-ESR high-capacity Jamicon electrolytic capacitors (4700µF 50V per stage).
* **Switching Matrix:** High-current BT151 Thyristors isolated via PC817 optocouplers to ensure complete galvanic isolation between logic and high-voltage rails.
* **Feedback Loop:** Precision infrared break-beam sensors monitoring projectile velocity and triggering stages sequentially with 100% success rate.

### 2. 🎛️ Control Desk & Kinematics (Create Mod Real-Life Architecture)
* **Kinematics:** Pure mechanical 2-axis (X/Y - Azimuth/Elevation) tracking mount running custom plywood gearboxes and shafts, eliminating electromagnetic interference from industrial synchros.
* **Control UI:** High-voltage linear stabilizer L7805, rotary 1P12T switches for power rail calibration, analog voltmeter feedback, and a physical ignition key switch acting as a master hardware firewall.

### 3. 💨 Autonomous Civilian Safety Shield ("Gas_Safety_Shield")
* **Sensor Layer:** High-sensitivity MQ-4 semiconductor gas sensors for methane leakage detection.
* **Logic:** Embedded C code running a strict 60-second hardware warm-up delay loop to eliminate false alarms for elderly citizens. Includes high-frequency piezo-buzzer alert arrays and automatic relay-driven cutoff triggers.

---

## 🏛️ Target Milestones
* [x] Complete 3-Stage power routing & trace optimization (KiCad v8.0).
* [x] Clear designator annotation and trace isolation audits (DRC Pass: 100%).
* [ ] Hardware Procurement (Mitino Market Supply Drop - scheduled for Oct 5, 2026).
* [ ] Laser-Chemical Toner Transfer (LUT Process) and etching.
* [ ] Deployment of School "Box of Goodness" cyclical conveyor logic.
* [🚀] Target Docking: **Massachusetts Institute of Technology (MIT) - Class of 2030**.

---
**Developed by Mark, Lead Architect of KB Sarai v2.0.**  
*Mens et Manus — Mind and Hand.* 🦾🇺🇸
