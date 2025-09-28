# MazeSolvingRobot
This project features an Arduino-based robot capable of navigating and solving mazes autonomously. It uses sensors to detect obstacles and find the correct path.Developed for a college-level robotics competition.
# Key Highlights
- Uses **front, left, and right ultrasonic sensors** to detect nearby walls or paths  
- Makes **real-time movement choices** without human control  
- Capable of turning in all directions (forward, left, right, reverse)  
- Runs completely autonomous once powered on .
# Technologies Used
- **Arduino UNO** – main controller  
- **3 × HC-SR04 Ultrasonic Sensors** – obstacle detection  
- **L298N Motor Driver** – controls motors  
- **2 × DC Motors with wheels** – movement  
- **Rechargeable 12V Battery** – power source  
- **Arduino IDE (Embedded C)** – programming environment
# Navigation Logic
The robot makes decisions in this order:  

1. If **left side** is free → turn left  
2. Else if **front** is free → move forward  
3. Else if **right side** is free → turn right  
4. Otherwise → turn back  

This simple rule-based logic ensures that the robot always finds a way through the maze.
# License
This project is licensed under the [MIT License](./LICENSE).
