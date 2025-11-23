# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:
![WhatsApp Image 2025-11-23 at 21 35 03_5ff77fcc](https://github.com/user-attachments/assets/52df44f3-b150-473e-a095-c340b934b34d)


## AC INPUT WAVEFORM:
<img width="780" height="397" alt="image" src="https://github.com/user-attachments/assets/11f9d990-907f-4295-b822-485b70f35385" />


## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER):
<img width="776" height="396" alt="image" src="https://github.com/user-attachments/assets/789aaf31-8c77-4cb0-9f52-a03b13b9433a" />


## SIGNAL OUTPUT(WITH FILTER)
<img width="775" height="396" alt="image" src="https://github.com/user-attachments/assets/64f39a93-cd1e-4860-a1fa-771032989ad8" />

## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
