# Surviving the Pandemic

A C++ simulation game developed at Concordia University, Montreal, where players must navigate the challenges of a global pandemic through resource management, strategic decision-making, and survival mechanics.

## Features

- **Advanced Object-Oriented Design**: Over 100 unique game mechanics implemented using modern C++ principles
- **Dynamic Event System**: Randomized events that challenge player decision making and adapt to player choices
- **Resource Management**: Strategic allocation of limited supplies including food, medicine, and protective equipment
- **Character Development**: Manage your character's physical health, mental health, and immunity levels
- **MySQL Integration**: Complete player data tracking and game state persistence
- **Performance Analytics**: ETL processes to analyze player statistics and game performance metrics

## Technical Highlights

- **C++17/20 Features**: Utilizing modern C++ features like smart pointers, move semantics, and STL algorithms
- **Database Integration**: MySQL connector with prepared statements for secure data management
- **Data Analysis**: Player performance tracking with over 500 metrics
- **Game State Persistence**: Save and restore functionality with serialization
- **Efficient Resource Management**: Memory-optimized game objects with 25% improved data access time

## Installation

### Prerequisites
- C++17 compatible compiler (GCC 9+, Clang 10+, or MSVC 19.14+)
- CMake 3.15+
- MySQL 8.0+
- MySQL Connector/C++ 8.0+

### Build Instructions

```bash
# Clone the repository
git clone https://github.com/yourusername/surviving-the-pandemic.git
cd surviving-the-pandemic

# Create build directory
mkdir build && cd build

# Configure and build
cmake ..
make

# Run the game
./pandemic_survival
```

### Database Setup

```bash
# Import schema
mysql -u username -p < ../db/schema.sql

# Import initial game data
mysql -u username -p < ../db/seed_data.sql
```

## Game Mechanics

The game features a day-based progression system where each day is divided into multiple time segments. Players must:

1. **Gather Resources**: Search different locations for food, medicine, and protective equipment
2. **Manage Health**: Monitor and maintain physical health, mental health, and immunity
3. **Handle Events**: Respond to random events like supply shortages, health emergencies, or social opportunities
4. **Make Strategic Decisions**: Choose between immediate survival needs and long-term planning

## Database Structure

The game utilizes a MySQL database to track:

- Player statistics and progression
- Game state persistence
- Resource distribution and economy
- Event frequency and outcomes
- Performance metrics and analytics

## Future Development

- Multiplayer cooperative mode
- Advanced AI for NPC interactions
- Extended event narratives and storylines
- Mobile companion app for notifications

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Developed as part of advanced programming coursework at Concordia University
- Special thanks to [Your Professor's Name] for guidance and support
