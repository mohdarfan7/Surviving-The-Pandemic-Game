# Surviving the Pandemic Game  
*A C++ survival simulation with MySQL integration*  
*(Developed at Concordia University, Montreal, QC)*  

![Gameplay Screenshot](docs/screenshots/gameplay.png)  

---
# 📂 Project Structure

- 📦 **Surviving-The-Pandemic-Game/**
  - 📂 **src/** - C++ source code
    - 🎮 *core/* - Game engine
    - 👥 *entities/* - Player/NPC classes
    - 🗃️ *database/* - MySQL integration
    - 🏁 *main.cpp* - Entry point
  - 📂 **docs/** - Documentation
    - 📝 *design.md* - Design specs
    - 🖼️ *screenshots/* - Game visuals
    - 📊 *db_schema.md* - DB diagrams
  - 📂 **sql/** - MySQL scripts
    - 🛢️ *schema.sql* - Table definitions
    - 🧪 *sample_data.sql* - Test data
  - 🧪 **tests/** - Unit tests
  - ⚙️ *CMakeLists.txt* - Build config
  - 📄 *README.md* - Project docs


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
