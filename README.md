# 🅿️ Dynamic Parking Pricing System

A dual-model dynamic pricing system to optimize urban parking using both **baseline linear** and **real-time streaming** methods. Built with real-world parking data, the project aims to reduce traffic congestion, improve space utilization, and enhance revenue generation.

---

## 🚀 Overview

Urban parking inefficiencies lead to congestion, time loss, and underutilization. This project presents:

- A **baseline linear model** that adjusts prices based on occupancy rates.
- A **real-time streaming model** using Pathway that adapts prices using multiple contextual features like vehicle type, queue length, and traffic conditions.
- An interactive dashboard comparing both models to drive insights and decision-making.

---

## 🛠️ Tech Stack

| Component            | Technology           | Purpose                                |
|----------------------|----------------------|----------------------------------------|
| Core Language         | Python 3.8+          | Data processing and model logic        |
| Data Manipulation     | Pandas               | Data wrangling and transformation      |
| Visualization         | Bokeh                | Interactive dashboards                 |
| Real-time Processing  | Pathway              | Stream-based dynamic pricing           |
| Development Platform  | Google Colab         | Collaborative notebook environment     |
| Data Storage          | CSV/JSON             | Historical and real-time data formats  |

---

## 📊 Architecture Diagram

```mermaid
flowchart TD
    A[📁 Raw Data (CSV)] --> B[🧹 Preprocessing & Feature Engineering]
    B --> C1[📈 Linear Pricing Model]
    B --> C2[🌐 Real-time Streaming Model (Pathway)]
    C1 --> D[🖼️ Visualization & Analysis (Bokeh)]
    C2 --> D
    D --> E[📤 Output: Plots, JSON, CSV]
