# Prototype v.1

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
- Schematic


### Order PCBs from online manufacture

This verion is ordered from [**PCBWay**](https://www.pcbway.com/). The main process is:

1. Prepare *Gerber file*, *BOM*, *Centroid file*. There are some manufacturing limits, pleas check [their capabilities](https://www.pcbway.com/capabilities.html) when design the PCB. Also, check [file requirements](https://www.pcbway.com/assembly-file-requirements.html) for preparing BOM and centroid file.

2. Use **Instant Quote** to submit your order.

3. After the order is saved to your cart, the sales will send you email to check about the production files, components, and the final price.

4. After confirming all the settings, they will send you email to remind you to pay. They will start to produce after receving the payment. 

5. You can check the production progress in your account of the websit.