# IITG-Summer-Analytics
Dynamic Pricing for Urban Parking Lots — Capstone project submitted for Summer Analytics 2025, organized by the Consulting and Analytics Club in collaboration with Pathway. This project explores optimization techniques and machine learning models to improve pricing efficiency in urban parking systems.


# 🅿️ Dynamic Pricing for Urban Parking Lots

**Capstone Project – Summer Analytics 2025**  
Hosted by **Consulting & Analytics Club × Pathway**

## 📌 Project Overview

Urban parking is a limited and high-demand resource. Static pricing often leads to inefficiencies—either overcrowding or underutilization.  
This project introduces a **dynamic pricing engine** for 14 parking spaces using real-time data, economic theory, and ML models to adjust prices intelligently based on:

- Occupancy rate
- Queue length
- Nearby traffic conditions
- Special day indicators (e.g., holidays, events)
- Type of incoming vehicle
- Competition from nearby lots

The objective is to maximize utilization and revenue while maintaining fair and explainable pricing.

---

## 🛠️ Tech Stack Used

| Category        | Tools / Libraries               |
|----------------|----------------------------------|
| Programming     | Python                          |
| Data Handling   | Pandas, NumPy                   |
| Visualization   | Bokeh                           |
| Modeling        | Custom Pricing Functions (Built from Scratch) |
| Streaming Simulation | [Pathway](https://pathway.com)  |
| Development     | Google Colab, GitHub            |


⚙️ Project Architecture & Workflow
📥 1. Data Ingestion
73-day data for 14 parking spaces at 18 time points/day
Features: Occupancy, Capacity, Latitude/Longitude, VehicleType, QueueLength, TrafficConditionNearby, IsSpecialDay

🔧 2. Real-Time Simulation (Pathway)
Data streamed with time delay
Processed in real time for dynamic decision-making

🧠 3. Pricing Logic
✅ Model 1: BaselineLinearPricingModel

🔁 Model 2: DemandPricingModel
Uses a multi-featured demand function:

🤖 Model 3: CompetitivePricingModel
Adds competitor prices based on proximity

📊 4. Real-Time Visualization
Built using Bokeh


