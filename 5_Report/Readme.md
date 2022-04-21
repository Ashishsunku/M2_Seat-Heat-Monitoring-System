   ### PROJECT REPORT ###

## Introduction
Now-days everyone is looking for automation and advancements in all the sectors. The Vehicle Seat Heat Monitoring System is capable of maintaining of heat in the vehicles seats. In European countries, the temperature is very low and any electronic designer should make sure that his equipment should work efficiently in that weather. 
In our project, the sensor will sense the driver has been seated or not and if the driver seated then he need to set the temperature accordingly. Based on that our controller will set the heater to required temperature. 
The Heater will generate the heat and a LCD display will show requested the temperature. 
In our project we have used ATmega328 microcontroller along with temperature sensor, Push button, Heat generator, LED and LCD diplay,etc.


## Features
- The System will sense is driver or passenger is seated or not.
- Driver or Passenger has the access to change the temperature in the vehicle.
- As per Driver's request, Heater will generate the heat accordingly.
- It is mainly useful for the European Countries.
- cost of the project is low and it's a robust system.
- Modular Approach is required.

## SWOT- Strengths, and Weakness, Opportunities Threats
### Strengths
- User Friendly
- Easy to alter the temperature inside the vehicle.
- Low cost and Robust system.

### Weakness
- Its only applicable for the countries having low temperature.
### Opportunities
- It can be implemented by having both Heater and AC.
### Threats
- Not suitable for average or high temperature places.

## 4W's and 1'H
### **WHAT** : Seat-Heat_Monitoring-System
### **WHERE** : Used in Automotive Industries
### **WHEN** : At low Temperature places



## Detail requirements
### High Level Requirements
| High Level Requirements      | Description |
| ----------- | ----------- |
| HLR1      | Microcontroller   |
| HLR2   | Temperature Sensor|
| HLR3   | Heat Generation|
| HLR4   | Display|
| HLR5   | Software used|

### Low Level Requirements
| Low Level Requirements      | Description |
| ----------- | ----------- |
| HLR1_LLR1      | ATmega328     |
| HLR2_LLR1   | LM35 and ADC|
| HLR2_LLR2   | ADC with PWM-fast|
| HLR3_LLR1   | Thermoelectric module|
| HLR4_LLR1   |LCD and LED|
| HLR5_LLR1   | Code Blocks with AVR GCC compiler |
| HLR5_LLR2   | SimulIDE |


###  BLOCK DIAGRAM  ###

![usercase](https://github.com/Ashishsunku/practise/blob/0226eabb24b45b6f235904957015d87c7ab74e9f/block%20diagram.png)

###  FLOW CHART ###

![usercase](https://github.com/Ashishsunku/practise/blob/0226eabb24b45b6f235904957015d87c7ab74e9f/flow%20chart.png)

# Test Plans

|  Test ID | Description  | Input  | Output  | Status |
|---|---|---|---|---|
| TID_01  | Is person seated  | push button=1| push button=1| PASS  |
| TID_02  | Is person not seated  | push button=0| push button=0 | PASS  |
| TID_03  | Temperature Request | Temp=0| heater=Off | PASS  |
| TID_04  | Temperature Request | Temp=20| heater=20 degree generation | PASS  |
| TID_05  | Temperature Request | Temp=25| heater=25 degree generation | PASS  |
| TID_06  | Temperature Request | Temp=29| heater=29 degree generation | PASS  |
| TID_07  | Temperature Request | Temp=33| heater=33 degree generation | PASS  |
| TID_08  | LED ON | Button=1 && Heater=1| LED=1 | PASS  |
| TID_09  | LED OFF | Button=0 && Heater=0| LED=0 | PASS  |
| TID_10  | LCD Display | Temperature :)<br />20 deg Cel| Temperature :)<br />20 deg Cel| PASS  |



## SCHEMATIC  ##

![usercase](https://github.com/Ashishsunku/practise/blob/be61e1951eb6bd8c0845ba35a8d7093f3e705658/total%20schematic.png)



## OUTPUT  ##

![usercase](
