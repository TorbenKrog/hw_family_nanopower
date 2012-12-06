Design notes for P31U-7.0
=========================


Reference diode in battery protection circuit
---------------------------------------------

The LM4040-2.5 reference diode has been chosen because it is used in other GomSpace systems. According to the datasheet, it operates from 60uA to 15mA. We choose to run it at a low current of 100uA. The series resistor is calculated for Vboost = 3.3V:

Rseries = (Vboost - 2.500) / 100uA = 8kOhm

