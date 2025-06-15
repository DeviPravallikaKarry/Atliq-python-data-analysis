# 🏨 AtliQ Hotels Booking Analysis with Python

> 📊 A data analysis project using Python to help AtliQ Hotels uncover trends, improve occupancy, and boost revenue across multiple cities and room categories.

---

## 🚩 Project Overview

AtliQ Hotels has been experiencing a drop in bookings and inconsistent revenue. So, this project was undertaken to analyze booking patterns and generate actionable insights that support better strategic decisions.

---

## 🎯 Project Goals

- Understand booking behavior by city, room type, and day of the week  
- Compare performance across weekdays and weekends  
- Identify key metrics that influence revenue and room utilization  
- Propose data-driven strategies to improve operations

---

## 🧰 Technologies & Libraries Used

| Tool/Library        | Purpose                                |
|---------------------|----------------------------------------|
| **Python**          | Data analysis scripting                |
| **Pandas**          | Data cleaning and manipulation         |
| **NumPy**           | Numerical operations                   |
| **Matplotlib & Seaborn** | Visualizing insights and trends  |
| **Jupyter Notebook**| Interactive analysis and storytelling  |

---

## 📁 Data Sources

The analysis was conducted using multiple datasets:

- `Bookings.csv` – Reservation records  
- `Rooms.csv` – Room types and their attributes  
- `Cities.csv` – Hotel location data  
- `Dates.xlsx` – Check-in and check-out details  
- `Revenue.csv` – Financial metrics related to bookings

All files were combined and cleaned before analysis.

---

## 🧹 Data Cleaning & Preparation

- Removed missing values and corrected date formats  
- Merged datasets to create a comprehensive view of hotel performance  
- Engineered new features like **occupancy rate**, **room revenue**, and **booking trends**

---

## 📊 Exploratory Analysis

Key areas analyzed:

- Occupancy patterns across cities and room categories  
- Performance differences between weekdays and weekends  
- Seasonal booking behaviors  
- Revenue contributions by location and room type

Visuals were created using Matplotlib and Seaborn to highlight trends and support conclusions.

---

## 🔍 Key Findings

| Area         | Insights |
|--------------|----------|
| **Occupancy** | Weekend stays had significantly higher occupancy (72%) compared to weekdays (51%) |
| **Cities**    | Delhi reported the highest occupancy; Mumbai contributed the most revenue |
| **Rooms**     | Presidential Rooms were consistently booked at higher rates |

---

## 📢 Recommendations

- Increase marketing efforts for high-performing cities like **Delhi**  
- Create **weekend packages** to capitalize on peak demand  
- Offer promotional rates for low-occupancy cities like **Bangalore**  
- Strengthen presence on **online booking platforms** to improve outreach

---

## 🔁 Workflow Diagram

```mermaid
graph TD;
    A[Booking Sources] --> B[Data Collection];
    B --> C[Data Cleaning & Transformation];
    C --> D[Analysis in Jupyter Notebook];
    D --> E[Insight Generation & Reporting];
