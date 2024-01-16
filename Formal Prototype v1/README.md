# Formal Prototype v.1

This version is the first version that was sent to the PCB manufacturer. There are 5 types of PCBs are made:

- Main Power Board
- [Peltier Slave](./Peltier_slave/)
- Motor Slave
- Thermistor Slave
- Heater Slave

### Folder Structure

The manufacturing files for each type of PCB are organized in a folder. A folder includes:

- KiCad project file
- Gerber files
- BOM: Components list of this board
- Centroid file: aka Pick-and-place file. Record the position and orientation of each components. It's usually for assembling PCB.
- Quotation from manufacturer
- Pictures
- Design note
- Schematics