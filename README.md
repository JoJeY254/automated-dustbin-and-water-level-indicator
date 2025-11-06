# automated-dustbin-and-water-level-indicator

# Group 3 
## Group Members

| Name                 | Registration Number   |
|----------------------|-----------------------|
 George Kareko         | BSCCS/2025/39770      |
| Collins Brian        | BSCCS/2025/40048      |
| Owiti Vivian Anyango | BSCCS/2024/59652      |
| Elias Muchira Karimi | BSCCS/2025/40695      | 
| Collins Brian        | BSCCS/2025/40048      | 
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
- Ultrasonic HC-SR04 connected: VCC -> 5V, GND -> GND, TRIG -> D9, ECHO -> D10
- Servo connected: Signal -> D3, VCC -> 5V, GND -> GND


# automated-dustbin-and-water-level-indicator

## Contents
- screenshots
  - 01_design_overview.png — full circuit/top view  
<img width="554" height="369" alt="image" src="https://github.com/user-attachments/assets/2a9c9194-9098-4227-9264-6555dc4dfdb2" />



- code  
  - water_level.ino — Arduino code used in Tinkercad  

## How to run  
1. Open the Tinkercad circuit: 
2. Copy the `water_level.ino` code into the Arduino IDE/code section in Tinkercad.  
3. Start the simulation and observe:  
   - LEDs light up according to water level (Low → High).  
   - Buzzer sounds when the water tank is full.  

## Notes  
- **Ultrasonic Sensor (HC-SR04) Connections:**  
  - VCC → 5V  
  - GND → GND  
  - TRIG → D7  
  - ECHO → D6  

- **LED Indicators:**  
  - Green LED → D2 (Low level)  
  - Yellow LED → D3 (Medium level)  
  - Red LED → D4 (High level)  

- **Buzzer:**  
  - Signal → D5  
  - VCC → 5V  
  - GND → GND  

- **Operation:**  
  - The sensor measures distance to the water surface.  
  - As water rises, LEDs turn on one by one.  
  - When the tank is full, the red LED lights and the buzzer activates. 
