# HealthCheck Monitoring Windows Service

**VB.NET • Windows Service • System Monitoring • Automated Reporting**

A robust, production-grade Windows Service designed to monitor the health and performance of a critical data processing pipeline in a healthcare technology environment.

### Key Features

- Runs as a **Windows NT Service** with proper `OnStart`/`OnStop` lifecycle
- Hourly scheduled checks using `System.Timers.Timer`
- Monitors file-based data exchange activity in real-time
- Queries SQL Server database for operational metrics
- Generates and emails exception reports for:
  - Clients with stale activity (>48 hours)
  - Low performance (eligibility/plan match rates <50%)
  - Hourly processing volume summaries
- Fully **configuration-driven** via `app.config`
- Comprehensive logging for diagnostics

### Technical Highlights

- Clean separation of monitoring concerns
- Defensive programming with error handling
- Efficient database access using `SqlDataAdapter`
- Time-windowed execution to avoid peak-hour load
- Tabular report generation for clear alerting

### Why This Project Stands Out

This service was responsible for **proactive detection** of issues in a system processing thousands of daily transactions across hundreds of clients. It enabled rapid response to outages, data delays, and performance degradation — directly impacting customer satisfaction and operational reliability.

## 🔒 Read‑Only Usage Notice

This repository is provided **solely for evaluation by potential employers**.  
You may **view** and **review** the code to assess engineering ability.

All other actions are **not permitted**, including:

- Reuse or modification  
- Redistribution or publication  
- Integration into any software  
- Commercial or operational use  
- Automation of any real‑world systems  

A full license file in this repository reinforces these restrictions.

---

## 📌 Notes

This code is intentionally incomplete and non‑functional.  
Its purpose is to demonstrate **architecture**, **coding style**, and **automation expertise**, not to operate against any real software.