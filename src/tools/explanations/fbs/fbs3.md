## FBS3 System

What is [FBS](./fbs.md)?

**FBS3** is the **third-generation** Mercedes drive authorization system and is found on many vehicles from the early 2000s up to mid-2010s.

### Core Components (FBS3)

- **EIS / EZS** – Electronic Ignition Switch (central authority)
- **Key** – Infrared or SmartKey
- **ELV / ESL** – Electronic Steering Lock
- **ECU** – Engine Control Unit
- **TCU / VGS** – Transmission Control Unit
- **Gateway**

### How FBS3 Works (Simplified)

1. Key is inserted or detected
2. EIS authenticates the key
3. EIS verifies ELV status
4. EIS sends start authorization to ECU and TCU
5. Engine start is allowed

All major modules **store synchronized security data**.

---

### Why FBS3 Matters for Programming

- Passwords can be **read or calculated**
- Modules can often be **renewed or virginized**
- Keys can be added or replaced
- FAST calculation works on **all FBS3 modules**

This is why tools like the Full Test Platform Pro are powerful for:

- EIS repair
- ECU renew
- ELV replacement
- All-keys-lost situations
