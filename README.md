# Propeller-Line-following-bot

## Description
This project aims to design and implement an automated guided vehicle (AGV) system that navigates through a factory floor to pick up and drop off widgets while adhering to lane rules and avoiding obstacles using the parallax propeller.

## Scenario Overview
The AGV operates within a factory environment represented by a grid-like structure on the floor. It starts at a designated home location and follows predefined lanes to pick up widgets from machine locations in lane A and drop them off for further processing at machine locations in lane B. The system must detect intersections, handle obstacles dynamically, and interact with designated pickup and drop-off locations.

## Task Descriptions
- The robot must navigate along the path defined by black tape, following the correct heading.
- It should first traverse the center lane before entering pickup or drop-off lanes.
- The system must detect intersections and provide real-time indication without stopping.
- Upon encountering obstacles in the center lane, the robot must dynamically change its course to avoid them.
- The AGV should slow down upon entering pickup and drop-off lanes.
- It should detect objects (representing partially processed widgets) at pickup locations in lane A and stop for 2 seconds upon detection.
- If pickup locations are empty, the robot should continue without stopping.
- After picking up widgets, the AGV should proceed to drop-off locations in lane B and display the distance between pickup and drop-off locations in centimeters.
- The system should continuously check for dynamic obstacles in pickup and drop-off lanes and stop if any are present until the obstacle is cleared.

## Repository Contents

- **Problem statement & Task Description**: Contains the Challenge presented which repo solves.
- **Propeller_line following.c**: Contains source code.
- **Circuit Diagram.jpg**: Contains the circuit diagram of the setup used.

## Circuit Diagram
![Circuit Diagram](https://github.com/Amenephous/Propeller-Line-following-bot/raw/main/Circuit%20Diagram.jpg)


## Video Demonstration

![prop_linefollower_gif](https://github.com/Amenephous/Propeller-Line-following-bot/assets/48127920/597dd0a0-949e-49b2-b262-5ab51efc0c27)
[Click here to watch the video demonstration.](https://photos.app.goo.gl/9NtMvUAPNtjcXSNr8)

## License
This project is licensed under the MIT License. See the LICENSE file for details.
