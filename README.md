# automated-dustbin-and-water-level-indicator

# Group 9 
## Group Members

| Name                 | Registration Number   |
|----------------------|-----------------------|
 George Kareko         | BSCCS/2025/39770      |
| Collins Brian        | BSCCS/2025/40048      |
| Owiti Vivian Anyango | BSCCS/2024/59652      |
| Elias Muchira Karimi | BSCCS/2025/40695      | 
| Brian Chege          | BSCCS/2025/45559      | 
| Ian Wanyama          | BSCCS/2025/39198      | 
| Alier Bior           | BSCCS/2025/41621      |

# automated-dustbin
autotomatic bin
## Contents

- screenshots
  - 01_design_overview.png — full circuit/top view
  - <img width="554" height="369" alt="image" src="https://github.com/user-attachments/assets/9ed9dc23-2cdd-4f4f-ac80-e5c86d807f2c" />

- code
  - project.ino — Arduino code used in Tinkercad

## How to run
1. Open Tinkercad circuit: https://www.tinkercad.com/things/frYLDsSe1j3-amazing-migelo?sharecode=lAZb2EPC8GM-5ZXilvA8RBgvJwTHV1_gWuEFVvDGNoc
2. Copy project.ino into the Arduino code box in Tinkercad.
3. Start the simulator.

## Notes
The ultrasonic sensor (HC-SR04) detects when a person’s hand or object comes near the dustbin lid.

The Arduino reads the sensor data and activates the servo motor.

The servo motor automatically opens the lid when an object is detected within a set distance.

After a short delay, the servo motor closes the lid again once the object is removed.


# water-level-indicator

## Contents
- screenshots
  - 01_design_overview.png — full circuit/top view  
<img width="541" height="369" alt="image" src="https://github.com/user-attachments/assets/864afed2-3a69-4659-aa6a-d1f8ba747a2b" />



- code  
  - water_level.ino — Arduino code used in Tinkercad  

## How to run  
1. Open the Tinkercad circuit: 
2. Copy the `water_level.ino` code into the Arduino IDE/code section in Tinkercad.  
3. Start the simulation and observe:  
   - LEDs light up according to water level (Low → High).  
   - Buzzer sounds when the water tank is full.  

## Notes  


- **Operation:**  
The ultrasonic sensor (HC-SR04) measures the distance between the water surface and the sensor at the top of the tank.

The Arduino processes the distance data and determines the current water level.

LEDs (green, yellow, red) light up one by one to indicate low, medium, and high water levels.

When the tank is full, the buzzer automatically sounds an alert to prevent overflow.
