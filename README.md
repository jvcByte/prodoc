# Mercedes-Benz Diagnostic & Programming Tools Guide

This project is an **mdBook-based technical guide** focused on professional **Mercedes-Benz diagnostic, testing, and programming tools**.

It is written to help technicians, locksmiths, and automotive electronics specialists understand **what Mercedes modules do**, how they communicate, and how to safely **test, read, renew, and program them** using aftermarket tools.

---

## 📘 What This Book Covers

This documentation explains how to work with major Mercedes-Benz electronic modules, including but not limited to:

- ECU (Engine Control Unit)
- TCU / VGS (Transmission Control Unit)
- EIS / EZS (Electronic Ignition Switch)
- ELV / ESL (Electronic Steering Lock)
- ISM (Intelligent Servo Module – gear selector)
- Dashboard / Instrument Cluster
- Gateway (CAN/LIN communication hub)

The focus is **not limited to key programming**. These tools allow full interaction with many control units, including bench testing, diagnostics, renewals, and programming.

---

## 🛠 Tools Documented

### Mercedes-Benz Full Test Platform Pro (MK24712)

A professional **Mercedes module testing and programming platform** that supports:

- Bench testing of EIS/EZS, ELV/ESL, ECU, TCU/VGS, ISM, Dashboard, Gateway
- Built-in ELV/ESL emulator
- FAST calculation for FBS3 and FBS4 systems
- Compatibility with VVDI MB Tool, AUTEL, ABRITES, CGDI MB, and others

Official product page:  
https://www.mk3.com/en/mercedes-benz-full-test-platform-pro

---

### CGDI Prog MB Benz Key Programmer

A multi-function Mercedes-Benz programming tool supporting:

- Key programming (including all-keys-lost scenarios)
- EIS/EZS reading and password calculation
- ECU and Gearbox (EGS 7G) renew
- Gateway read/write authorization
- Mileage and dashboard-related operations (where supported)

Official product page:  
https://www.cgdiprog.com/products/cgdi-prog-mb-benz-key-programmer.html

---

## 🎯 Goals of This Documentation

- Explain **what each Mercedes module does**
- Show **how tools interact with each module**
- Provide **safe workflows** for testing and programming
- Include **visual references and diagrams**
- Link to **official manuals and PDFs** for deeper technical detail

This guide is structured for **learning and reference**, not shortcuts.

---

## 🧱 Project Structure

```text
.
├── src/
│   ├── SUMMARY.md
│   ├── intro.md
│   ├── full-test-platform.md
│   ├── cgdi-mb.md
│   └── advanced-functions.md
├── images/
│   ├── mk3_test_platform.png
│   ├── cgdi_mb_prog.png
│   ├── ecu.png
│   ├── eis.png
│   ├── elv.png
│   ├── ism.png
│   └── dashboard.png
└── README.md
```
