# Temperature Sensors - Devices


# Analogue Temperature sensors

### LM35

±0.5°C 4V-30V, Temperature sensor with analog output

### LM75

±2°C, 2.7V to 5.5V industry standard temperature sensor with I2C/SMBus interface

[preview:3](LMT70/LMT70.md)


### SHT20
The SHT20 is **humidity** and **temperature** sensor of Sensirion has become an industry standard in terms of form factor and intelligence: Embedded in a reflow solderable Dual Flat No leads (DFN) package of 3 x 3mm foot print and 1.1mm height it provides calibrated, linearized sensor signals in digital, I2C format.


### KY-001

### KY-013
This module provides a NTC thermistor

# Analogue Temperature sensors Conditioning IC

### Maxim MAX31820

### Maxim MAX31855

The  MAX31855  performs  cold-junction  compensation  and  digitizes  the  signal  from  a  K-,  J-,  N-,  T-,  S-,  R-,  or  E-type  thermocouple.  
The  data  is  output  in  a  signed  14-bit,  SPI-compatible,  read-only  format.  
This  converter  resolves  temperatures  to  0.25°C,  allows  readings  as  high  as  +1800°C  and  as  low  as  -270°C,  and  exhibits  thermocouple accuracy of ±2°C for temperatures ranging from -200°C to +700°C for K-type thermocouples. 

## Maxim Integrates: **MAX31865** - PT-RTD amplifier


# Digital temperature sensors
--------

[preview:3](LM70/LM70.md) 

[preview:3](DS18B20/DS18B20.md) 

[preview:3](TMP116/TMP116.md) 

[preview:3](TMP117/TMP117.md) 




# Device Comparison
-------

| Device  	| Prec. °C	| Accuracy 	| Resol.	| Range 			| Price	| Supply (V)| I (uA)| Interface |
| :-		| :-  		| :-  		| :-    	| :- 				| :-	| :-		| :-	| :-		|
| TMP117	| :-  		| ±0.1°C	| 16 bit	|-55 to 150, 0 to 85| 		| 1.8 - 5.5	| 5		| I2C		|
| DS18B20	| ±0,5 (±2) | 			| 9-12 bit	|-55 a 125, -10 85	| 4-8 €	| 3.0 - 5.5	| -		| 1-wire	|
| MAX31820	| ±0,5 (±2) | 			| 11 bit	|-55 a 125, -10 85	| 2 €	| 3.0 - 3.7	| -		| 1-wire	|
| MAX31820	| ±0,5 (±2) | ±2°C		| 14 bit	|-40 a 125			| - €	| 3.0 - 3.6	| 1000	| 1-wire	|



