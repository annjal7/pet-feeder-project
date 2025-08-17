
# Smart Pet Feeder – Assignment Part 1

## 📌 Overview:
This project designs a **Smart Pet Feeder System** that dispenses food automatically for pets at fixed times, with safety and monitoring features.  
The design follows a structured problem-solving method (Steps 1–5) and integrates **sensors, algorithms, and alerts** to ensure reliable and ethical pet care.

---

## 🗂 Deliverables:
- **Part1/**
  - Step 1 – Problem statement, assumptions, and **Block Diagram** (`.jpg`).
  - Step 2 – Input/Output data table with sample values, ranges, and constraints.
  - Step 3 – **Flowchart** (`.jpg`).
  - Step 4 – **Word Code (pseudocode)** in plain English (`Step4_Word_Code.txt`).
  - Step 5 – **Test Scenarios** with expected outcomes (`Step 5 - Testing and Refinement.doc`).

---

## ⚙️ System Features
- **Scheduled feeding** at fixed times (default: 08:00 & 18:00).
- **Hopper & bowl monitoring** using sensors.
- **Safety checks**:
  - Low hopper alert.
  - Bowl overflow prevention.
  - Dispense jam detection & retry.
  - Pet not eating alert.
  - Sensor fault handling.
- **Logging** of all events (feedings, errors, alerts).
- **Alerts** via buzzer/LED/app for owner awareness.

---

## 🚀 How It Works
1. **Configuration** – Pet profiles, feeding times, bowl capacity, and safety margins are set.
2. **Loop** – At feeding times, the system checks hopper/bowl levels, then runs the feed routine.
3. **Dispense routine**:
   - Dispenses portion (with jam retry).
   - Waits 10 minutes and checks consumption.
   - Logs result (eaten / not eating).
4. **Alerts & Logs** – Triggered whenever abnormal conditions occur.

---

## ✅ Testing Scenarios
- **Normal eat** – Pet consumes ≥50% portion.
- **Not eating** – Pet ignores food (alert raised).
- **Low hopper** – Feeding skipped, warning issued.
- **Jam detected** – Retry once, else alert.
- **Bowl near full** – Feeding skipped to prevent overflow.
- **Sensor fault** – Feeding paused until sensors recover.

---

## 📖 How to Use
- Open the `Step3_Flowchart` file (u3279536_Assignment1) for flowchart of the system.
- Review pseudocode in `Step4_Word_Code.txt` for logic reference.
- Check `Step 5 - Testing and Refinement.doc` for structured test cases.
- Use diagrams and code together to document or implement the system (e.g., with Arduino or Raspberry Pi).

---

## 👤 Author
Prepared by: Anjel Dhungel  
Course: Introduction to Information to IT  
Assignment: **Smart Pet Feeder System**

---
