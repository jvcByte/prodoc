## FBS4 System

What is [FBS](./fbs.md)?

**FBS4** is the **fourth-generation** Mercedes drive authorization system, introduced on newer vehicles (mid-2010s onward).

It significantly increases security.

### Core Components (FBS4)

- **EIS / EZS (Next Gen)**
- **Keyless GO SmartKey**
- **Gateway (more central role)**
- **ECU**
- **Dashboard**
- **Online Mercedes servers** (for some operations)

### Key Differences from [FBS3](./fbs3.md)

| Feature              | FBS3                  | FBS4                 |
| -------------------- | --------------------- | -------------------- |
| Security Level       | High                  | Very High            |
| Password Access      | Readable / Calculable | Highly restricted    |
| Module Renew         | Common                | Limited              |
| Online Authorization | No                    | Sometimes required   |
| FAST Calculation     | Yes                   | Yes (tool-dependent) |

---

### Why FBS4 Is More Restricted

- Security data is **distributed and encrypted differently**
- Some operations require:
  - Online authorization
  - Tokens
  - OEM-level tools

- Not all modules can be renewed like FBS3

This is why **FAST calculation** and **bench emulation** are critical when working with FBS4 vehicles.

---

## Why FAST Calculation Matters

FAST calculation is a method used by aftermarket tools to:

- Rapidly calculate security access data
- Reduce dependence on vehicle gateway
- Enable key and module operations on FBS3 and supported FBS4 vehicles

The **Full Test Platform Pro** provides:

- Gateway emulation
- ELV emulation
- Stable bench power

Which makes FAST calculation **possible and reliable**.

---

## Practical Summary

- **FBS3** = older Mercedes system, more flexible, widely programmable
- **FBS4** = newer system, more secure, limited but supported by advanced tools
- Your tools exist to **bridge the gap** between these systems safely

---
