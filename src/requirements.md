# Requirements

Before using the tools and procedures described in this guide, make sure you meet the following requirements. These tools interact directly with **Mercedes-Benz security and control modules**, so preparation is critical.

---

## Intended Audience

This guide is intended for:

- Automotive technicians
- Auto locksmiths
- Diagnostic specialists
- Automotive electronics repair professionals

It is **not** intended for beginners with no automotive or electronics experience.

---

## Knowledge Prerequisites

You should already understand:

- Basic vehicle electrical systems
- CAN and LIN bus fundamentals
- Difference between ECU, TCU, EIS/EZS, ELV/ESL, ISM, and Gateway
- Safe handling of electronic control units
- Windows PC operation and driver installation

> If terms like _EIS_, _FBS3/FBS4_, or _ELV emulator_ are unfamiliar, review the Introduction and Glossary first.

---

## Hardware Requirements

### Required Tools

- **Mercedes-Benz Full Test Platform Pro (MK24712)**
- **CGDI Prog MB Benz Key Programmer**
- Windows laptop or PC
- Stable USB cables
- Original test platform wiring harnesses and adapters

### Recommended Equipment

- Regulated **12–14V bench power supply** (minimum 5A)
- Vehicle battery charger / stabilizer (for in-car work)
- ESD protection (anti-static wrist strap)
- Clean workbench with proper lighting

---

## Software Requirements

- Windows 10 / 11 (64-bit recommended)
- Latest official software for:
  - CGDI Prog MB
  - VVDI MB Tool / AUTEL / ABRITES (if used with MK3)
- USB drivers installed correctly
- Administrator access on the PC

> Always download software from **official vendor websites only**.

---

## Vehicle & Module Conditions

- Vehicle battery voltage must be stable (≥12.4V)
- For programming operations, use a battery stabilizer
- Bench testing requires correct wiring and polarity
- Modules must match supported model lists
- Backup original data before writing or renewing modules

---

## Safety & Legal Notice

- These tools can **permanently alter vehicle modules**
- Incorrect wiring or voltage may damage ECUs
- Some operations may be restricted by local law
- Always confirm vehicle ownership and authorization
- This guide does **not** encourage illegal activity

You are responsible for complying with all applicable laws and regulations.

---

## Important Notes

- Never hot-plug modules during active programming
- Do not interrupt power during write operations
- Label and organize cables to avoid cross-connection
- When in doubt, stop and verify before proceeding
