# Smart National Park Trash Management System

This repository contains the simulation project for **CNG 476 System Simulation** course at METU for the Spring 2024/2025 semester.

##  Project Title
**Smart National Park Trash Management System**

## 👥 Team Members
- **Berkan Balcı** – 2526150  
- **Arda Yücel** – 2457968

##  Project Description

This project simulates an IoT-based smart trash collection system deployed in a national park. Trash bins are equipped with sensors that measure their fill levels. When a bin’s fill level reaches a threshold, it communicates with a control center using the **FLoRa** protocol. The control center dispatches cleaning robots to empty the bins, following an optimized route to minimize distance and response time.

The system is implemented using the **OMNeT++** discrete event simulation framework and evaluated for network reliability and routing efficiency.

##  Technologies Used
- **OMNeT++** for simulation  
- **FLoRa** (LoRa simulation framework on OMNeT++)  
- **C++** for sensor and robot behavior  
- **NED** for network architecture modeling  
- **Git** & **GitHub** for version control

##  Repository Structure

smart-trash-management/
│
├── /docs # Reports (proposal, progress, final)
│ ├── Proposal.pdf
│ ├── Progress.pdf
│ └── FinalReport.pdf
│
├── /src # Simulation source files
│ ├── TrashSensor.cc
│ ├── Robot.cc
│ ├── Network.ned
│ └── omnetpp.ini
│
├── README.md # Project description
└── LICENSE # (Optional) Open-source license


## How to Run

1. Install OMNeT++ (v6 or later)
2. Clone this repository:
3. 3. Open the project in OMNeT++ IDE
4. Build the project and run the simulation via `omnetpp.ini`

##  Simulation Focus

- Random trash level generation (Monte Carlo Simulation)  
- LoRaWAN communication delays and reliability  
- Dynamic routing for cleaning robots  
- Evaluation metrics:
- Average travel distance
- Network delay
- Number of full bins over time

##  Deliverables

- ✅ Proposal Report  
- ✅ Progress Report  
- ⏳ Final Report (in progress)  
- ⏳ Simulation code and demo  

##  License

This project is for academic use under CNG 476. You may modify and reuse the content with proper citation.

##  GitHub Repository

https://github.com/your-username/smart-trash-management






