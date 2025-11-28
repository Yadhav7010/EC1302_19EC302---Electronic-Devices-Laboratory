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
<img width="1295" height="656" alt="image" src="https://github.com/user-attachments/assets/53f0191c-6c37-4fe8-9bf9-071824d9e338" />


## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)
<img width="1199" height="761" alt="image" src="https://github.com/user-attachments/assets/6e87e126-a6c2-409f-b577-a7d1ab6fddf6" />

## SIGNAL OUTPUT(WITH FILTER)

<img width="1192" height="750" alt="image" src="https://github.com/user-attachments/assets/a5485485-06fa-4d6a-b209-47f4e6e600d2" />


## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
