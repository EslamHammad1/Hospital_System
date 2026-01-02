# 🏥 Hospital Queue System

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Language](https://img.shields.io/badge/C++-17-blue)
![Status](https://img.shields.io/badge/status-active-success)

**Hospital Queue System** is a **C++ console application** that manages patients in a hospital based on their specialization and urgency.

It supports **adding patients, managing queues, prioritizing urgent cases, and assigning patients to doctors**.

---

## 🚀 What This Project Does

- Handles multiple specializations
- Maintains patient queues per specialization
- Prioritizes urgent patients
- Adds new patients and removes them once attended
- Prints all patients in each specialization
- Provides a simple and interactive menu for hospital staff

---

## 📌 Features

- Add new patients (regular or urgent)
- Print all patients per specialization
- Get next patient for a doctor
- Shift queue automatically for urgent cases
- Limit queue size per specialization
- Interactive console menu

---

## 🛠️ Tech Stack

- C++
- Standard Library (`iostream`, `string`, `bits/stdc++.h`)
- Console-based application
- Array-based queue management

---

## ▶️ How to Run

1. Clone the repository  
2. Compile using any C++ compiler:
```bash
g++ hospital.cpp -o hospital
