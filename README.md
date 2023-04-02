# CurrentSensingPCB

This is a PCB that can help provide the amount of power drawn in a system. This is done by placing a shunt sensor in series within the circuit, which produces a voltage drop across itself that will be read using an Arduino. A shunt sensor is a relatively low resistance resistor. Using Ohm's Law, this can be converted to current, which can be used to derived for power. Noise filtering capacitors were also used with their appropiate resistance to reduce inaccurate peak readings.

The PCB is made for a 24V, 10A system on a robot, power calculations derived the maximum power through the shunt to be 0.2W, well below the 8W tolerated by the shunt.
Part Specifications:
Shunt Sensor: 2 mili-Ohms resistance, +/- 1% tol, 8W max power
Capacitors: 100nF, 6.3V, +/- 10% tol
Resistors: 100 Ohms, +/-1 %, 63 mW
Input/Output: XT30PW-M

PCB 3D Model
![image](https://user-images.githubusercontent.com/128961461/229329062-a9539a9f-7cd9-45ec-a791-db6fcdb54ac6.png)

Corresponding Schmatic:
![image](https://user-images.githubusercontent.com/128961461/229329242-d5400c10-ddb2-4783-84a0-000c4dafac45.png)
