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
<img width="1026" height="608" alt="Screenshot 2025-11-29 000328" src="https://github.com/user-attachments/assets/63d8c616-53ea-41bd-ab21-2ece96e2e340" />


## AC INPUT WAVEFORM:

![WhatsApp Image 2025-12-04 at 11 00 52_7a104c52](https://github.com/user-attachments/assets/b2ac5e18-c632-41fd-8f2d-8a37565cd259)


## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)

![WhatsApp Image 2025-12-04 at 10 59 37_0e14bf85](https://github.com/user-attachments/assets/12ba749e-76f5-43d9-bd0a-1aaf479a781a)

## SIGNAL OUTPUT(WITH FILTER)

![WhatsApp Image 2025-12-04 at 11 01 05_528205d8](https://github.com/user-attachments/assets/bdd070f6-e87e-401b-9c29-48037a1c105b)

## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
