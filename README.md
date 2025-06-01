# 📦 SQL Server Backup Types – Training & Strategy Guide

This repository contains a complete guide and SQL scripts to understand and implement various **SQL Server backup types**, supported by examples and a real-world hospital system scenario.

---

## 📘 Contents

1. **Part 1 – Backup Types Research**
   - Overview and comparison of:
     - Full Backup
     - Differential Backup
     - Transaction Log Backup
     - Copy-Only Backup
     - File/Filegroup Backup
   - Use cases, pros & cons, and real-world examples (banking, ticketing, etc.)

2. **Part 2 – Practice with TrainingDB**
   - Sample SQL scripts to:
     - Create a test database (`TrainingDB`)
     - Insert mock data
     - Perform various types of backups
   - Great for students or beginners to simulate backup operations.

3. **Part 3 – Real-World Backup Strategy (HospitalDB)**
   - Full SQL Server backup schedule for a hospital system:
     - Weekly full backups
     - Nightly differential backups
     - Hourly transaction log backups
   - File naming conventions and sample scripts included

---

## 🚀 How to Use

1. Clone this repo or copy the scripts locally.
2. Run each SQL segment inside **SQL Server Management Studio (SSMS)**.
3. Review the explanations for each backup type to understand best practices.
4. Adapt the real-world backup strategy to your production or test environments.

---

## 📂 Backup Folder Structure

C:\HospitalBackups
├── Full
│ └── HospitalDB_Full_YYYYMMDD.bak
├── Differential
│ └── HospitalDB_Diff_YYYYMMDD.bak
└── Logs
└── HospitalDB_Log_YYYYMMDD_HH.trn

---
