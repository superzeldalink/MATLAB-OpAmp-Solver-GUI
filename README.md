# MATLAB-OpAmp-Solver-GUI
## DISCLAIMER!!!
Please don't copy this source code for your own purpose (e.g. exercises, projects,...). If you get caught by your instructor/lecturer for using this source code, that's your fault.

Please consider carefully by using this.

## Features
- [x] Includes four different circuits:
  - Inverting Amplifier
  - Non-inverting Amplifier
  - Summing Inverting Amplifier
  - Summing Non-inverting Amplifier
- [x] Three different types of source signals:
  - DC source
  - AC source
  - Custom function Vin(t)
- [x] For Summing circuits, input can be maximum of 100 sources.
- [x] Time domain can be adjusted for the graphs.
- [x] Input and output can be plotted on a single axes. 
- [x] Resistor (potentiometer) can be a function that changes over time (must not be negative).
- [x] All inputs accept basic operations, e.g., +, -, *, /,^, abs, mod, log,...
- [x] Plot all Vin in a same axes (for summing circuit).
- [ ] Plot resistor function.
- [ ] ??? (new feature(s))

## Instructions
- **Step 1:** Choose the circuit.
- **Step 2:** 
  - If non-summing circuit is chosen:
  Choose the source in “Vin source” panel then fill the value.
  - If summing circuit is chosen:
  Fill in the value of the source and resistors in “Vin sources (for summing circuits)” panel in the exact order.
  _Note:_ The number of the Vin and the number of resistors must be equal.
- **Step 3:** Fill in the value Rf and R (if needed) in “Resistors” panel.
- **Step 4:** (optional)
  Custom the time range (tmin, tmax) to plot Vin and Vout in that range only.
  Tick “Plot on the same axes” to plot Vin and Vout on the same axes.
- **Step 5:** Press the “Solve” button and the results will shown up. 

## Screenshots
- Inverting Amplifier with AC source

![image](https://user-images.githubusercontent.com/4103880/140642555-5507f013-2155-409d-a945-4488f70061a9.png)

- Non-inverting Amplifier with custom function

![image](https://user-images.githubusercontent.com/4103880/140642577-273e7043-aae6-46cc-a8b0-18cd445fecb3.png)

- Summing Inverting Amplifier with a list of 3 Vins, 3 resistors

![image](https://user-images.githubusercontent.com/4103880/140642588-2ef8a56a-8b1d-4651-8b29-888649ada3c3.png)

## Using the source code
- Make sure `GUI.m`, `GUI.fig` and all of the images are in the same folder.
- Run the `GUI` command in MATLAB.
- That's it.

## Notes
- If there are bugs or you want to add new features, feel free to open an issue and we will try to fix/add them if we can.

## DISCLAIMER (again)!!!
Please don't copy this source code for your own purpose (e.g. exercises, projects,...). If you get caught by your instructor/lecturer for using this source code, that's your fault.

Please consider carefully by using this.

## Credits
- Assoc. Prof. H. H. Kha, Ho Chi Minh City University of Technology, "Operational Amplifier".
- Assoc. Prof. H. H. Kha, Ho Chi Minh City University of Technology, "Project OpAmp Sample".
- R. Teja, "Summing Amplifier," Electronics Hub, 22 April 2021,  https://www.electronicshub.org/summing-amplifier/.
- M. Safwat, "How to draw any function using GUI MATLAB.," YouTube, 12 April 2017, https://www.youtube.com/watch?v=ZjH1i9SfNa0.
- user3797886, rayryeng, "How do I make a png with transparency appear transparent in MatLab?," Stack Overflow, 07 August 2014, https://stackoverflow.com/questions/25172389/how-do-i-make-a-png-with-transparency-appear-transparent-in-matlab.
- MATLAB, "MATLAB Documentation," MathWorks, https://www.mathworks.com/help/matlab/.
- Maxim Integrated, "GLOSSARY DEFINITION FOR OP AMP," Maxim Integrated, 2020, https://www.maximintegrated.com/en/glossary/definitions.mvp/term/Op%20amp/gpk/883.
- All About Circuits, "Introduction to Operational Amplifiers (Op-amps)," EETech Media, LLC., https://www.allaboutcircuits.com/textbook/semiconductors/chpt-8/introduction-operational-amplifiers/.
