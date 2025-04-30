# Surviving the Pandemic Game  
*A C++ survival simulation with MySQL integration*  
*(Developed at Concordia University, Montreal, QC)*  

![Gameplay Screenshot](docs/screenshots/gameplay.png)  

---
# 📂 Project Structure
Surviving-The-Pandemic-Game/
├── src/ # C++ source code
│ ├── core/ # Game engine (GameManager, Renderer)
│ ├── entities/ # Player, NPCs, Items
│ ├── database/ # MySQL connection and queries
│ └── main.cpp # Entry point
├── docs/ # Documentation
│ ├── design.md # Game design specs
│ ├── screenshots/ # Game visuals
│ └── db_schema.md # Database diagram
├── sql/ # MySQL scripts
│ ├── schema.sql # Database tables
│ └── sample_data.sql # Mock data
├── tests/ # Unit tests (Google Test)
├── CMakeLists.txt # Build configuration
└── README.md # Project documentation


---

## **🎯 Features**  
- **100+ game mechanics** (health, crafting, infections)  
- **MySQL integration** (500+ player metrics tracked)  
- **SDL2 graphics** (optional)  

---

## **🚀 Quick Start**  
```bash
# Clone & build  
git clone https://github.com/yourusername/Surviving-The-Pandemic-Game.git  
cd Surviving-The-Pandemic-Game  
mkdir build && cd build  
cmake .. && make  
./SurvivalGame  
