# 🔌 Wireless EV Charging System

> A contactless electric vehicle charging system based on electromagnetic induction, eliminating the need for physical charging cables.

---

## 📖 Project Overview

The **Wireless EV Charging System** is a power electronics project that demonstrates contactless energy transfer for electric vehicle battery charging using the principle of electromagnetic induction. A transmitter coil generates a magnetic field, which induces a voltage in a nearby receiver coil. The induced AC power is converted into usable DC power through a rectifier circuit, which can then be used to charge a vehicle battery — all without any physical electrical connection between the charging station and the vehicle.

This project explores the core working principle, system architecture, and practical considerations behind wireless power transfer (WPT) as applied to electric vehicle charging.

---

## 📝 Abstract

Electric vehicles are becoming central to sustainable transportation, but conventional plug-in charging has limitations such as cable wear, exposure to weather, and manual user effort. This project presents a **Wireless EV Charging System** that uses inductive coupling between a transmitter coil and a receiver coil to transfer electrical energy without physical contact. The transmitter coil, driven by an AC source, generates a time-varying magnetic field. This field induces an alternating voltage in the receiver coil placed in proximity, based on Faraday's Law of Electromagnetic Induction. The induced AC voltage is then rectified into DC using a rectifier circuit, making it suitable for battery charging. The system demonstrates a working proof-of-concept of inductive wireless charging and highlights its potential as a convenient, cable-free alternative to conventional EV charging methods.

---

## ❗ Problem Statement

Conventional electric vehicle charging relies on physical cables and connectors, which presents several practical challenges:

- Charging cables are subject to **physical wear, weather exposure, and damage** over time
- Manual plugging and unplugging adds **user inconvenience**, especially in public or automated charging scenarios
- Exposed connectors and cables raise **safety concerns**, particularly in outdoor or wet conditions
- Cable-based systems are **less suited to automation** (e.g., autonomous vehicles, robotic charging bays)

There is a need for a charging method that removes the dependency on physical connectors while still reliably transferring power to the vehicle battery.

---

## 🎯 Objectives

- To design a transmitter coil circuit capable of generating an alternating magnetic field
- To design a receiver coil circuit capable of capturing the induced magnetic field and converting it into an AC voltage
- To implement a rectifier circuit that converts the induced AC voltage into a usable DC output
- To demonstrate functional wireless power transfer between transmitter and receiver coils
- To evaluate the system's behavior under varying coil separation distances

---

## 🏗️ System Architecture

The system is composed of two main sides — the **Transmitter (Charging Station) Side** and the **Receiver (Vehicle) Side** — linked only through magnetic coupling, with no physical electrical connection between them.

**Transmitter Side:**
AC/DC Power Source → Driver Circuit → Transmitter Coil

**Receiver Side:**
Receiver Coil → Rectifier Circuit → DC Output → Battery

A detailed block-level breakdown of this architecture is provided in `BLOCK_DIAGRAM.md`.

---

## ⚙️ Working Principle

The system operates on the principle of **electromagnetic induction**, as described by Faraday's Law:

1. **Magnetic Field Generation:** A driver circuit excites the transmitter coil with an alternating current, generating a time-varying magnetic field around it.
2. **Inductive Coupling:** When the receiver coil is placed within range of this magnetic field, the changing flux induces an alternating voltage in the receiver coil.
3. **AC to DC Conversion:** The induced AC voltage is fed into a rectifier circuit, which converts it into a DC voltage suitable for charging applications.
4. **Power Delivery:** The resulting DC output is directed toward the vehicle's battery for charging.

Since energy transfer occurs purely through the magnetic field between the two coils, no physical electrical contact is required between the charging station and the vehicle.

---

## 🧩 Components Used

| Component | Function |
|---|---|
| Transmitter Coil | Generates the alternating magnetic field for power transmission |
| Receiver Coil | Captures the magnetic field and induces an AC voltage |
| Driver Circuit | Excites the transmitter coil with the required alternating current |
| Rectifier Circuit | Converts the induced AC voltage into a usable DC output |
| Power Supply | Provides the input electrical energy to the transmitter side |

---

## ✅ Advantages

- Eliminates the need for physical charging cables and connectors
- Reduces wear and damage associated with repeated plugging/unplugging
- Improves user convenience through contactless charging
- Reduces exposure-related safety risks from outdoor cabling
- Better suited to automated or robotic charging environments

---

## 🌍 Applications

- Electric vehicle charging stations (private and public)
- Automated/robotic EV charging bays
- Charging infrastructure for electric two-wheelers and small EVs
- Research and academic demonstration of wireless power transfer principles

---

## 🔭 Future Scope

- Extending the system to support higher power levels for faster charging
- Improving coil alignment tolerance for more flexible vehicle positioning
- Incorporating closed-loop control for adaptive power regulation
- Evaluating performance and efficiency trade-offs across varying coil air-gap distances
- Exploring resonant coupling techniques to extend effective charging range

---

## 🏁 Conclusion

The Wireless EV Charging System demonstrates a practical, working application of electromagnetic induction principles for contactless electric vehicle charging. By transferring power through magnetic coupling between a transmitter and receiver coil — followed by AC-to-DC rectification — the system removes the dependency on physical charging cables, improving convenience and reducing wear associated with conventional plug-in charging. This project highlights the feasibility and future potential of wireless charging technology as a meaningful step toward more convenient and automated EV charging infrastructure.

---

## 👤 Author

**Navya Shree Sairigapu**
B.Tech, Electronics & Communication Engineering
[LinkedIn](https://www.linkedin.com/in/navya-sairigapu-97723935a) · navyasairigapu@gmail.com
