# 🧹 Smart User Data Cleaner

A Python script to clean and format raw user data using **only string methods**.

### 🎯 The Challenge (Week 1)
* **Goal:** Parse and clean a messy string (`" Name ; Age ; Height ; Email "`).
* **Constraints:** No loops (`for`/`while`), no lists, no `if` statements.
* **Techniques:** `split()`, `strip()`, `slicing`, type conversion (`int`, `float`).

### 📊 Example
**Input:**
`"  AhMeT  yILMAZ ;  23 ;  1.78 ;  ahmetYILMAZ@GMAIL.Com   "`

**Output:**
```text
User: Ahmet Yilmaz
Age (in 10 years): 33.0
Height: 178.0 cm
Email Code: ahm

_Created for Data Science Bootcamp._
