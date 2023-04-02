# CurrentSensingPCB

This is a PCB that can help provide the amount of power drawn in a system. This is done by placing a shunt sensor in series within the circuit, which produces a voltage drop across itself that will be read using an Arduino. A shunt sensor is a relatively low resistance resistor. Using Ohm's Law, this can be converted to current, which can be used to derived for power. Noise filtering capacitors were also used with their appropiate resistance to reduce inaccurate peak readings.<br>
**The PCB is made for a 24V, 10A system**, power calculations derived the maximum power through the shunt to be 0.2W, well below the 8W rating of the shunt.<br>
Note: Arduino can read a minimum voltage of 0.0049V, **an op-amp is not necessary in this circuit**<br>
Part Specifications:<br>
Shunt Sensor: 2 mili-Ohms resistance, +/- 1% tol, 8W max power<br>
Capacitors: 100nF, 6.3V, +/- 10% tol<br>
Resistors: 100 Ohms, +/-1 %, 63 mW<br>
Input/Output: XT30PW-M<br>

_PCB 3D Model_
![image](https://user-images.githubusercontent.com/128961461/229329821-7d23fa43-fc2b-45ac-9776-c19e468725f8.png)

_PCB Layout_
![image](https://user-images.githubusercontent.com/128961461/229329842-6afc7c78-8525-42e2-9769-8c50666a0aaa.png)

_PCB Schematic_
![image](https://user-images.githubusercontent.com/128961461/229329938-6d1978a1-4e53-48d7-bb81-7ddb1cc4ee85.png)



