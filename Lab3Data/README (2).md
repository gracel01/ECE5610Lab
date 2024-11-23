# Laura Parke 
# ECE 5610-001
---------------------------------------------------------
Lab 3 Items:
- Waveform Captures
Buck Converter: MOSFET Analysis

ABSTRACT:  In this experiment we study the switching characteristics of power MOSFETs and power 
diodes using a buck converter. The circuit is operated in open loop conditions with no feedback.
The purpose of this lab is to understand the switching behavior of these two power devices. We perform
Psice simulations to take measurements and compare with values obtained in the datasheet IRF640.  We
estimate switching power losses during the turn-ON and turn-OFF of both the MOSFET and diode.


section 3.4: Measurements and Waveforms
----------------------------------------------------------
- duty ratio @ 50%
- Load Resistance = 10 Ω
- Switching Frequency = 100 kHz
- External Input Voltage Vd = 15V (DC Power Supply)
1. V_ak -> C53 Diode
   Input:
   Ch-1: PWM Output
   Ch-2: V_diode (C53 / GND) -> C53
     15.63 V - top flat line
     -0.700 V - bottom flat line
   V_diode (V_AK) = 15.63 V - (-0.700V) =16.33 V
     14.7 V - top flat line
     -0.700 V - bottom flat line
   V_diode (V_AK) = 14.7 V - (-0.700 V) = 15.4 V
   
   C53:
   460 mV Peak-to-Peak
   R_L = 10 Ω
   I_diode (C53) = 460 mV/10 Ω = 46 mAmps

   760 mV Peak-to-Peak
   R_L = 10 Ω
   I_diode (C53) = 760 mV/10 Ω = 76 mAmps

   PSU:  15 V @ 0.28 Amps (source Vin)
        15(0.3) = 6V(0.700)

2.  Top MOSFET: Ch2: drain and source
    -average: 140 mV/10 Ω = 14 mAmps
    -Pk-pk: 9.6 V
3.  Ch 2:  drain and source of top Mosfet   50+V triangle wave
    -average: 14.256 V
    -average: 13.82 V
    I_ds (mosfet) (CS1) = 140 mV/0.05 Ω = 28 mAmps
4.  V_FM = 0.7 V
5.  I_o = 623 mAmps
    V_o = 6.22 V @ 10 Amps
    
scope_34:
- Using cursor to measure peak flat voltage
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Anode-Cathode Voltage of lower diode
  
 PWM Reference Signal of Power Pole Board -> Peak Flat Voltage |
:-------------------------:|
![](3Data/scope_34.bmp) |



scope_35:
- Using cursor to measure minimum flat voltage
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Anode-Cathode Voltage of lower diode

 PWM Reference Signal of Power Pole Board -> Minimum Flat Voltage |
:-------------------------:|
![](3Data/scope_thirty_five.bmp) |

scope_36:
- Change time to enhance ON behavior
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Anode-Cathode Voltage of lower diode

 PWM Reference Signal of Power Pole Board -> Change Time |
:-------------------------:|
![](3Data/scope_36.bmp) |


scope_37:
- Change time view multiple cycles
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Anode-Cathode Voltage of lower diode

 PWM Reference Signal of Power Pole Board -> Change Time View Multiple Cycles |
:-------------------------:|
![](3Data/scope_37.bmp) |

scope_38:
- Change time to enhance OFF behavior
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Anode-Cathode Voltage of lower diode

 PWM Reference Signal of Power Pole Board -> Change Time to Enhance Off Behavior|
:-------------------------:|
![](3Data/scope_38.bmp) |

***Changed external power supply to different unit for stability concerns of previous scope_34-35***

scope_39:
- Using cursor to measure peak flat voltage
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Anode-Cathode Voltage of lower diode

 PWM Reference Signal of Power Pole Board -> Peak Flat Voltage |
:-------------------------:|
![](3Data/scope_39.bmp) |


scope_40:
- Using cursor to measure minimum flat voltage
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Anode-Cathode Voltage of lower diode

 PWM Reference Signal of Power Pole Board -> Minimum Flat Voltage |
:-------------------------:|
![](3Data/scope_40.bmp) |


scope_41:
- Change time to enhance ON/OFF behavior
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Anode-Cathode Voltage of lower diode

 PWM Reference Signal of Power Pole Board -> Change Time to Enhance ON/OFF behavior |
:-------------------------:|
![](3Data/scope_41.bmp) |


scope_42:
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Drain-Source MOSFET V_DS

 PWM Reference Signal of Power Pole Board -> PWM Reference Measurement |
:-------------------------:|
![](3Data/scope_42.bmp) |

scope_43:
- Change time view
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Drain-Source MOSFET V_DS
 
 PWM Reference Signal of Power Pole Board -> Change Time View |
:-------------------------:|
![](3Data/scope_43.bmp) |


scope_44:
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Output load voltage
*Calculate load current I_o

 PWM Reference Signal of Power Pole Board -> PWM Reference Measurement |
:-------------------------:|
![](3Data/scope_44.bmp) |


scope_45:
- Ch1: PWM reference measurement of Power Pole Board
- Ch2: Output load voltage
*Calculate load current I_o

 PWM Reference Signal of Power Pole Board -> PWM Reference Measurement |
:-------------------------:|
![](3Data/scope_forty_five.bmp) |







