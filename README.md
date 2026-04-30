# 🏎️ F1™ Pit Wall — Real-Time Race Intelligence Dashboard

A **production-grade Formula 1 race intelligence dashboard** inspired by real-world **pit wall systems**, designed to simulate how teams monitor races using live data, telemetry, and strategic insights.

---

##  Overview

F1 Pit Wall is a **data-driven, high-performance dashboard** that visualizes race events, driver standings, constructor rankings, and telemetry in a structured, scalable interface.

This project goes beyond a typical frontend build — it demonstrates **systems thinking**, **data modeling**, and **real-time dashboard design**.

---

##  Core Features

###  Live Race Dashboard
- Dynamic race header (track, laps, distance, session details)
- Real-time countdown timer (“Lights Out”)
- Highlighted upcoming race with contextual metadata

###  Season Calendar Engine
- Horizontally scrollable multi-round calendar (23 races)
- Active race highlighting and navigation system
- Structured race scheduling model

###  Driver Standings System
- Points-based ranking engine
- Driver metadata (team, nationality, performance)
- Dynamic leaderboard rendering

###  Constructor Standings
- Team ranking aggregation
- Visual comparison using progress indicators
- Modular team data structure

###  Telemetry Panel
- Driver selection interface
- Simulated telemetry feed
- Extensible architecture for real-time data integration

###  Track Map Visualization
- Custom SVG-based circuit rendering
- Driver position markers
- Foundation for real-time animation and tracking

---

##  Architecture & Design

- Component-oriented UI structure  
- Separation of concerns (data vs presentation)  
- Reusable UI modules (cards, panels, tables)  
- Scalable system design for all F1 circuits  

The project is designed with **extensibility in mind**, enabling seamless integration of live APIs and real-time updates.

---

##  Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript  
- **Design System:** Custom-built (F1 broadcast-inspired UI)  
- **Data Layer:** Structured static data (API-ready architecture)  

---

## 📈 Roadmap / Future Enhancements

-  Live data integration (Ergast API / FastF1)  
-  Real-time updates via WebSockets  
-  SVG path-based car animation on track maps  
-  Migration to React (component scaling + state management)  
-  Dark/Light mode toggle  
-  Full responsive optimization  
-  Advanced telemetry charts (speed, tire data, sector times)  

---

##  Engineering Highlights

- Designed a **scalable dashboard system** from scratch  
- Implemented **data-driven UI rendering**  
- Built a **modular architecture** for future extensibility  
- Focused on **performance, clarity, and real-world usability**  

---

## 🖥️ Getting Started

```bash
git clone https://github.com/AbhinavPabbaraju/f1-pit-wall.git
cd f1-pit-wall
open index.html
