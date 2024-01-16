# Note: Main Power Board

<img src="/Prototype v1/Main_power_board/pics/Main_power_board.jpg" alt="main power board 3D" width="400"/>


### Features

- Input voltage: 6.2v - 20v (1.2v Maximum Dropout Voltage at 800 mA)
- Regulating the input voltage to 5v. 
- A main switch to turn on/off the entire system manually. 
- I2C connection to the master board. 
- An eneble pin to turn on/off the 

### Difference with the previous version

The trace width and via size are reduced because the manufacturer can produce PCBs with the machine and get more detailed and accurate results.

- Ordinary trace width: 0.4mm
- Via diameter: 0.5mm
- Via hole: 0.3mm
- To decrease the signal interference, I tried to separate the traces based on different signal transmissions (e.g. PWM, I2C, analog reading). 


### Pinout

<img src="/Prototype v1/Peltier_slave/pics/Peltier_slave_pinout.jpg" alt="peltier slave 3D" width="400"/>