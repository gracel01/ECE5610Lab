# Laura Parke ECE 5610-002
---------------------------------------------------------
Lab-6: Feedback Control in Boost Converter

Lab 6 Items:
- PSpice Captures
Boost Converter Analysis

Measurements and Waveforms

1. (6 Points) Run the simulation. Attach a zoomed-in waveform of the PWM driving signal of the MOSFET and estimate the switching frequency;  f_s ~ 50505.05 Hz
Compare the switching frequency of this converter with the one in Lab 4.  The switching frequency in Lab4 is 1E5 Hz.  The switching frequency in this lab is 50.5% of the switching frequency in Lab4.

 PWM driving signal of MOSFET |
:-------------------------:|
![](Lab5Dara/boost_closeloop_Vg.bmp) |

2. (6 Points) Compare the inductance value with the one in Lab 4. Make comments on the differences based on your observation of assignment 1.

3. (6 Points) What type of diode is used in this circuit? What’s major difference between this diode and the one we used in Lab 4?

4. (6 Points) Now replace the diode MBRS340 by 1N914, which is a normal silicon diode. Re-run the simulation and attach a zoomed-in waveform of steady-state voltage. Comment on the steady state voltage ripple. Change the diode back once you are done with this question.

 Zoomed in Waveform of steady-state voltage |
:-------------------------:|
![](Lab5Dara/boost_closeloop_ss.bmp) |

5. (3x2=6 Points) List the advantages and disadvantages of operating at higher frequency.

6. (5 Points) Summarize what you have learned from assignment 1 to 5.
 
 PWM driving signal of MOSFET |
:-------------------------:|
![](Lab5Dara/boost_closeloop_Vg.bmp) |

scope_66:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 10% @ 100kHz
- Ch2: Ouput Voltage measure across V2+ and COM
  
 PWM Reference Signal of Power Pole Board -> Duty 10% @ 100kHz Resistance = 20 Ω |
:-------------------------:|
![](5Data/scope_66.bmp) |

scope_67:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 20% @ 100kHz
- Ch2: Ouput Voltage measure across V2+ and COM

 PWM Reference Signal of Power Pole Board -> Duty 20% @ 100kHz Resistance = 20 Ω |
:-------------------------:|
![](5Data/scope_67.bmp) |

scope_68:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 30% @ 100kHz
- Ch2: Ouput Voltage measure across V2+ and COM

 PWM Reference Signal of Power Pole Board -> Duty 30% @ 100kHz Resistance = 20 Ω |
:-------------------------:|
![](5Data/scope_68.bmp) |

scope_69:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 40% @ 100kHz
- Ch2: Ouput Voltage measure across V2+ and COM

 PWM Reference Signal of Power Pole Board -> Duty 40% @ 100kHz Resistance = 20 Ω |
:-------------------------:|
![](5Data/scope_69.bmp) |

scope_70:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 50% @ 100kHz
- Ch2: Ouput Voltage measure across V2+ and COM

 PWM Reference Signal of Power Pole Board -> Duty 50% @ 100kHz Resistance = 20 Ω |
:-------------------------:|
![](5Data/scope_70.bmp) |

scope_71:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 60% @ 100kHz
- Ch2: Ouput Voltage measure across V2+ and COM

 PWM Reference Signal of Power Pole Board -> Duty 60% @ 100kHz Resistance = 20 Ω |
:-------------------------:|
![](5Data/scope_71.bmp) |

section 5.4.2: Varying Switching Frequency
----------------------------------------------------------
- duty ratio @ 60%
- Load Resistance = 15 Ω
- Switching Frequency = 100 kHz
- External Input Voltage Vd = 10V (DC Power Supply)

scope_72:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 60% @ 100kHz
- Ch2: Inductor Voltage measure across CS5 and COM

 PWM Reference Signal of Power Pole Board -> Duty 60% @ 100kHz Resistance = 15 Ω |
:-------------------------:|
![](5Data/scope_72.bmp) |

scope_73:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 60% @ 100kHz
- Ch2: Inductor Voltage measure across CS5 and COM

scope_73:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 60% @ 100kHz
- Ch2: Inductor Voltage measure across CS5 and COM

scope_74:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 60% @ 100kHz
- Ch2: Inductor Voltage measure across CS5 and COM

scope_75:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 60% @ 80kHz
- Ch2: Inductor Voltage measure across CS5 and COM

scope_76:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 60% @ 60kHz
- Ch2: Inductor Voltage measure across CS5 and COM

scope_77:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 60% @ 40kHz
- Ch2: Inductor Voltage measure across CS5 and COM



section 5.4.3: Determining Efficiency
----------------------------------------------------------
- duty ratio @ 60%
- Load Resistance = 15 Ω
- Switching Frequency = 100 kHz
- External Input Voltage Vd = 10V (DC Power Supply)

scope_78:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 60% @ 60kHz
- Ch2: Output Voltage measure across V2+ and COM

scope_79:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 60% @ 60kHz
- Ch2: Output Voltage measure across V2+ and COM

scope_80:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 60% @ 100kHz
- Ch2: Output Voltage measure across V2+ and COM

section 5.4.4: Varying Load
----------------------------------------------------------
- duty ratio @ 40%
- Load Resistance = 20 Ω
- Switching Frequency = 40 kHz
- External Input Voltage Vd = 10V (DC Power Supply)

scope_81:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 40% @ 40kHz
- Ch2: Output Voltage measure across V2+ and COM

scope_82:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 40% @ 40kHz
- Ch2: Output Voltage measure across V2+ and COM

scope_83:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 40% @ 40kHz
- Ch2: Output Voltage measure across V2+ and COM

scope_84:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 40% @ 40kHz
- Ch2: Output Voltage measure across V2+ and COM

scope_85:
- Ch1: PWM reference measurement of Power Pole Board -> Duty 40% @ 40kHz
- Ch2: Output Voltage measure across V2+ and COM
***Discontinuous Conduction Mode due to "flat" valley peaks:
  Load Resistance = 28.7 Ω for DCM
