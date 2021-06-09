
# Project Title

SAPiD project 6 - measurement of the family of transistor characteristics Ic=f(Uce) at specific base currents.

Assumptions:

- Application testing based on the test of the BC211 transistor.
- Declaration of the maximum number of characteristics and base currents (e.g. 100, 200, 300 uA).
- Declaration of the maximum number of measuring points for one characteristic.
- Declaration of the permissible load of the transistor (Pmax).
- Carry out measurements until the permissible power of the transistor is obtained.
- Acquisition of measurement data in the table.
- Current presentation of the obtained data.
- Graphical presentation of the family of characteristics.
- The ability to save the results in a file (format adopted by the spreadsheet).
- Ability to interrupt measurements or the program at any time.





2. Measurement system and implementation of measurements:

![App Screenshot](http://www.kmeif.pwr.wroc.pl/elektron/interfejsy/projekt2/zad4.gif)


- The optocoupler diode circuit is connected to source A and the transistor circuit is connected to source B of the BM572 power supply.
- The diode current should be checked by measuring the voltage across a 1.23 kohm resistor. When measuring the characteristics, the voltage of the A source should be selected in order to obtain the required current If
- The collector current should be determined by measuring the voltage across the 889ohm resistor.
- Calculate the collector-emitter voltage on the basis of the set value of the B source voltage and the measured voltage drop across the collector resistor.
- The V553 multimeter measures the voltage across both resistors of the system depending on the setting of the commutator. Channel 6 is energized from the diode resistor and channel 7 is supplied from the collector circuit resistor.
- The sub-range of the multimeter should be optimally selected for the currently measured voltage.


## Related

Here are some related projects:

[Our exercise](http://www.kmeif.pwr.wroc.pl/elektron/interfejsy/projekt2/zad_proj2.htm#z6)

  
## Software

**NI LabVIEW 2020 SP1 (32-bit) 20.0.1** 

  


  
## Authors:

 - **Damian Kociołek** [@Dako99](https://github.com/Dako99)

 - **Julia Moroz**  [@yuuqx](https://github.com/yuuqx)


  