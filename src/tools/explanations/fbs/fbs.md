## FBS Systems (Mercedes-Benz)

**FBS** stands for **Drive Authorization System** (_Fahrberechtigungssystem_ in German).
It is Mercedes-Benz’s **immobilizer and vehicle authorization architecture**.

The FBS system determines:

- Whether a key is valid
- Whether the engine is allowed to start
- Whether modules trust each other

## How This Applies to This Book

Whenever this book mentions:

- Password reading
- FAST calculation
- EIS renew
- ECU / TCU renew
- ELV personalization

You are working **inside the [FBS3](./fbs3.md) or [FBS4](./fbs4.md) authorization framework**.

Understanding this prevents mistakes and explains _why_ some operations are allowed and others are restricted.
