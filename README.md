# 🚗 Dynamic Pricing for Urban Parking Lots

### Capstone Project – Summer Analytics 2025  
By: Niladri Banerjee

---

## 📌 Overview

This project builds a real-time **dynamic pricing system** for 14 urban parking lots using ML models and economic logic. The system adapts parking rates based on live demand factors like occupancy, queue length, traffic congestion, and competition.

The objective is to maximize space utilization, avoid overcrowding, and ensure fair pricing.

---

## 🧰 Tech Stack

- **Languages & Libraries**: Python, NumPy, Pandas, Pathway, Bokeh
- **Execution**: Google Colab
- **Visualization**: Real-time plots with Bokeh
- **Version Control**: GitHub

---

## 📐 Architecture Diagram

```mermaid
graph TD
    A[Data Simulation (Pathway)] --> B[Real-time Data Ingestion]
    B --> C[Feature Extraction (Occupancy, Queue, Traffic...)]
    C --> D[Pricing Logic (3 Models)]
    D --> E[Price Output]
    E --> F[Bokeh Visualization]
