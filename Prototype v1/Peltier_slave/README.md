# Note

<img src="/Prototype v1/Peltier_slave/pics/Peltier_slave.jpg" alt="peltier slave 3D" width="400"/>


### Features

- Input voltage: 4.5v - 44v (with Main Power board: 6v - 20v)
- Control up to two Peltiers to heat up and cool down with pulse width modulation (PWM) signal. 
- Connect with up to four 10K thermistors. 
- Unified Program and Debug Interface (UPDI) pins for programming the board. 
- I2C connection with the master board. 

### Difference with the previous version

The trace width and via size are reduced because the manufacturer can produce PCBs with the machine and get more detailed and accurate results.

- Ordinary trace width: 0.4mm
- Via diameter: 0.5mm
- Via hole: 0.3mm
- To decrease the signal interference, I tried to separate the traces based on different signal transmissions (e.g. PWM, I2C, analog reading). 


### Pinout

<img src="/Prototype v1/Peltier_slave/pics/Peltier_slave_pinout.jpg" alt="peltier slave 3D" width="400"/>