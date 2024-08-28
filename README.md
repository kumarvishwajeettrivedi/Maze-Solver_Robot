# Maze Solver Robot

Welcome to the Maze Solver Robot project! This endeavor involves designing a robot capable of autonomously solving mazes by leveraging line-following technology. Built using Arduino and motor drivers, this project showcases innovative robotics and autonomous navigation techniques.

## Inspiration

The Maze Solver Robot was inspired by the classic problem of a rat navigating a maze. Our goal was to develop a solution that could emulate this behavior and tackle the challenge of autonomous maze-solving. The project not only addresses the technical problem of maze navigation but also explores the practical application of robotics in problem-solving.

![Maze Solver in Action](MAZESOLVER.gif)


## Features

**- Autonomous maze-solving capability.**  
**- Efficient line-following using analog IR sensors.**  
**- Advanced maze-solving algorithms, including PID control for precise movement.**  
**- Modular design for easy assembly and modification.**  

## Components

**- Arduino board (e.g., Arduino Uno).**  
**- Motor driver module.**  
**- DC motors and wheels.**  
**- Analog IR line-following sensors.**  
**- Distance sensor for enhanced navigation.**  
**- Chassis for the robot.**  
**- Power source (e.g., batteries).**  

## PID Controller

To achieve smooth and precise movement while following lines, a PID (Proportional-Integral-Derivative) controller is implemented. The PID controller continuously adjusts the motor speeds based on feedback from the IR sensors, allowing the robot to make real-time corrections and stay on the path. This results in more accurate line-following, especially when navigating curves and intersections within the maze.


## Maze-Solving Algorithm

The robot utilizes a simple yet effective algorithm to navigate the maze by following these directional priorities:

1. **Left:** The robot checks if it can turn left. If the path is clear, it turns left.
2. **Down:** If left is not an option, it checks if it can move forward or down.
3. **Right:** If neither left nor down is available, the robot checks the right direction.
4. **Up:** As a last resort, the robot turns around or moves upwards if all other directions are blocked.

This algorithm ensures that the robot explores all possible paths and efficiently finds the solution to the maze. The combination of the PID controller and this directional strategy allows the robot to adapt to different maze configurations.

## Setup Instructions

1. **Connect the DC motors to the motor driver module.**  
2. **Attach the analog IR line-following sensors to the Arduino board.**  
3. **Integrate the distance sensor with the Arduino for improved navigation.**  
4. **Mount the Arduino and motor driver onto the robot chassis.**  
5. **Upload the maze-solving algorithm code to the Arduino board.**  
6. **Connect and secure the power source.**  

## Usage

1. **Place the robot at the starting point of the maze.**  
2. **Power on the robot.**  
3. **Observe the robot as it autonomously navigates through the maze by following the lines, making turns based on the directional algorithm.**  
4. **The robot will stop at the end point upon successfully solving the maze.**  

## Customization

**- Tailor the maze-solving algorithm in the Arduino code to accommodate different maze designs.**  
**- Adjust sensor positions or add extra sensors to enhance line detection accuracy.**  
**- Fine-tune the PID controller parameters for optimal performance.**  

## Presentation

Our team of three presented this project at the TechFest of IIT BHU, TechNex. The presentation highlighted the robot’s capabilities, design principles, and the innovative approach to solving the maze problem. We demonstrated how the robot efficiently navigates through various maze configurations using our custom-built algorithms and sensors.

## Contributing

We welcome contributions to improve and expand this project. Feel free to fork the repository, make enhancements, and submit pull requests to help advance the Maze Solver Robot.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute the code for both personal and commercial purposes.


**Happy maze solving!** 🤖🔍

---
