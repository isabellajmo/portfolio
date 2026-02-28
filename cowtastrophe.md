# IoT "Cowtastrophe" Multi-User Game
> **Tools:** MATLAB App Designer, OOP, ThingSpeak API

## 🎯 Project Objective
Develop a cloud-connected multiplayer game featuring real-time data persistence and event-driven logic.



## 🛠 Technical Implementation
* **OOP Architecture:** Encapsulated player turns and cow-building logic into modular MATLAB classes.
* **Cloud Sync:** Utilized **ThingSpeak API** for field-based data logging and cross-client synchronization.
* **Input Validation:** Implemented switch-case error handling to ensure deterministic state management.

## 🔍 R&D Insight
**Rate Limiting:** Solved API request frequency errors by implementing local state caching, reducing unnecessary cloud writes.
