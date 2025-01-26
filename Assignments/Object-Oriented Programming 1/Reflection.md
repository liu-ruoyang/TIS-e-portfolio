# Reflection: OOP1 Project - E-Connect 4

## Project Overview
- **Course**: Object-Oriented Programming 1 (OOP1)
- **Project Title**: E-Connect 4 Game
- **Team Members**:  
  - Kahlan Sultan Mohammed  
  - Liu Ruoyang  
  - Bu Guoshun  
  - Abdulrahman Siad  
  - Hassan Saad  
- **Objective**:  
  To implement a digital version of the classic Connect Four board game using C++ with object-oriented programming (OOP) principles, incorporating graphical elements via the WinBGIm library.

---

## Features and Implementations

### Game Features
1. **Graphical Interface**:
   - Designed a 6x7 grid system for Connect Four gameplay.
   - Included visually interactive elements like buttons and player indicators.
   - Supported animations for moves and victory highlights&#8203;:contentReference[oaicite:0]{index=0}&#8203;:contentReference[oaicite:1]{index=1}.

2. **Game Modes**:
   - **PvP (Player vs Player)**: Allows two players to compete locally.
   - **PvC (Player vs Computer)**: Features an AI opponent that employs basic strategy&#8203;:contentReference[oaicite:2]{index=2}&#8203;:contentReference[oaicite:3]{index=3}.

3. **Rules Enforcement**:
   - Ensured adherence to Connect Four rules, including valid moves, turn-based gameplay, and victory conditions for horizontal, vertical, and diagonal lines&#8203;:contentReference[oaicite:4]{index=4}&#8203;:contentReference[oaicite:5]{index=5}.

4. **Menu and Help**:
   - Main menu with options for PvP, PvC, Help, and Exit&#8203;:contentReference[oaicite:6]{index=6}&#8203;:contentReference[oaicite:7]{index=7}.
   - Help section with instructions for new players&#8203;:contentReference[oaicite:8]{index=8}&#8203;:contentReference[oaicite:9]{index=9}.

---

## Reflections by Component

### **Main Menu**
- **Purpose**: Provides a starting point for the game with clear navigation options.
- **Reflection**:
  - Utilized object arrays for managing multiple buttons dynamically.
  - Improved event handling through mouse-click detection.

---

### **Help Screen**
- **Purpose**: Displays game rules and instructions interactively.
- **Reflection**:
  - Integrated image assets effectively to enhance user experience.
  - Learned the importance of providing clear guidance for a better user interface.

---

### **Game Screen**
- **Purpose**: Core gameplay logic, including grid rendering, input handling, and victory checks.
- **Reflection**:
  - Strengthened understanding of 2D array operations for board state management.
  - Tackled challenges in detecting complex victory conditions (diagonal, vertical, horizontal)&#8203;:contentReference[oaicite:10]{index=10}&#8203;:contentReference[oaicite:11]{index=11}.
  - Enhanced debugging skills while synchronizing player turns and AI decisions.

---

### **AI Player**
- **Purpose**: Implements basic AI for Player vs Computer mode.
- **Reflection**:
  - Gained insight into designing AI strategies such as blocking, winning moves, and prioritizing columns.
  - Developed a deeper understanding of function overriding and inheritance&#8203;:contentReference[oaicite:12]{index=12}.

---

### **Button Class**
- **Purpose**: Abstracts button creation and interaction.
- **Reflection**:
  - Understood the importance of reusable UI components.
  - Enhanced encapsulation skills through the independent handling of button properties&#8203;:contentReference[oaicite:13]{index=13}.

---

### **Project Proposal and Design Analysis**
- **Proposal**:
  - Inspired by the classic Connect Four game due to its simplicity and strategic depth&#8203;:contentReference[oaicite:14]{index=14}.
  - Emphasized scalability and maintainability in project planning&#8203;:contentReference[oaicite:15]{index=15}.
- **Reflection**:
  - Learned to document requirements systematically, ensuring alignment between objectives and implementation.
  - Strengthened team collaboration during brainstorming and proposal development.

---

## Overall Reflection
This project was a comprehensive exercise in applying OOP principles to a real-world scenario. It provided hands-on experience in:
- Modular programming with clear class hierarchies.
- Event-driven programming with graphical and mouse input handling.
- Developing and testing AI strategies.

Key takeaways include:
1. **Importance of OOP Concepts**: Encapsulation, inheritance, and polymorphism were pivotal in achieving a scalable and maintainable codebase.
2. **Graphics Programming**: WinBGIm graphics library offered a valuable introduction to interactive interface design.
3. **Collaboration**: Team coordination and role delegation were critical to meeting deadlines and addressing challenges effectively.

---

## Recommendations for Future Improvement
1. **Advanced AI**:
   - Implement minimax or heuristic-based algorithms for smarter AI.
2. **Dynamic Board Size**:
   - Allow players to customize grid dimensions for more variability.
3. **Optimized Graphics**:
   - Explore alternative libraries for smoother animations and transitions.
4. **Testing and Debugging**:
   - Integrate unit tests to validate victory conditions and edge cases more efficiently.

---

## Conclusion
The E-Connect 4 project showcased the practical application of OOP principles, culminating in an engaging, functional game. It laid a solid foundation for future projects, highlighting the importance of clean design, teamwork, and continuous improvement.
