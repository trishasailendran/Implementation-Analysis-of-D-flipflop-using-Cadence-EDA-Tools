# Implementation-Analysis-of-D-flipflop-using-Cadence-EDA-Tools
Ex No: 01     Implementation & Analysis of D-flipflop using Cadence EDA Tools   

Aim:
To design and implement a D-flip-flop using Cadence EDA tools, simulate its behavior, and analyze key performance parameters such as timing, power consumption, and resource utilization for a comprehensive understanding of sequential logic circuits.

Tools Required:
•	Personal Computer
•	Cadence Virtuoso Software

S C H E M A T I C S I M U L A T I O N - PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION -Commands to get into Cadence

1.	Right Click and open the terminal window
2.	Type the following commands as follows and press enter.
•	csh
•	source /cadence/install/cshrc
•	virtuoso 
Procedure for Schematic simulation using Cadence

1.	Now two windows must open i) virtuoso/command interpreter window ii)”Whats New…”
2.	Close the 2nd window
3.	Use 1st window i.e virtuoso window (CIW) for further processing.
i.	Create a New Library
ii.	Create Schematic Cell view.
iii.	Create the Symbol for schematic Cell view.
iv.	Create the test Cell view.
v.	Analog simulation by spectre


i)	Procedure for Creating New Library.
•	File –New – Library
•	Name: Give name for ur library Ex: VLSILAB_EXP_1
•	Enable Attach to an existing technology library, Click OK
•	Attach the library to the technology library gpdk045.Click OK
ii)	Create Schematic Cell view.
•	Go to 1st window i.e virtuoso (CIW)
•	File-New-Cell view
•	Setup the new file form
	Library: Select the one you created.
	Cell: Give the experiment name Ex: Inverter ViewSchematic
	Type: Schematic press OK
•	Add the required components from the libraries and make the connections.
	Go to instance fixed menu or use shortcut key “I” from keypad to go instances
	Click on browse. This opens the library browser
	Now select the appropriate library for components like 
	Gpdk45 ------------------------nmos1v, pmos1v
	Create Input and Output pins
	Make the connections by using fixed narrow wire key
	Click Check and Save button
![WhatsApp Image 2024-10-23 at 14 18 44_15076b58](https://github.com/user-attachments/assets/4bdaa7e8-1d49-4c57-ae50-5db1172f55ee)




 
iii)	Creating the Symbol for schematic Cell view

•	In the schematic window, execute 
	Create – Cell view – From Cell view
	The cell view from cell view window appears
	Check Lib Name, Cell Name, From View name must be schematic Press ok
•	Now Symbol generation form appears. Click Ok If No changes required
•	A new window with with default symbol is created.
•	Edit the symbol if you want to give actual symbol shape else continue.
•	Execute Create-Cell view-from cell view
•	Library Name and Cell Name must be same which you have used for schematic. Press OK
•	Check for the position of pin side.Prss OK
•	Edit for the shape by Create-Shape-Choose required options to edit.

![WhatsApp Image 2024-10-23 at 15 01 26_5466778a](https://github.com/user-attachments/assets/3a469534-8854-4908-bbdd-66f9b4762638)

![WhatsApp Image 2024-10-23 at 15 00 25_886e71cb](https://github.com/user-attachments/assets/5e4649cc-db61-44fe-b468-4b676e83d9b4)

![WhatsApp Image 2024-10-23 at 14 59 54_cb5d6594](https://github.com/user-attachments/assets/fbca6752-0a79-40c2-bb8d-3c7f6abe9a3a)

iv)	Creating the new test cell view

•	Go to CIW window, Execute File-New-Cell view
	Setup the new file form
	Library: Select the one you created.
	Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test
	View: Schematic
	Type: Schematic press OK
•	Follow the step 3(ii) d to make the required connections

![WhatsApp Image 2024-10-23 at 14 37 34_e2eb5a68](https://github.com/user-attachments/assets/9751cb41-f76d-4427-a7ca-c1699643af35)



 
Analog simulation by SPECTRE.
•	In test cell view window
•	Launch – ADE L(Analog Design Environment)
	Execute Setup—Simulation/directory/Host A new window opens
	Set the simulation window to spectre and click ok
	Execute Analysis – Choose. A window opens.
	Select the type and set the specifications and press OK
	Execute Output s—to be plotted – Select on Schematic
	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse
•	Execute Simulation -- Net list and Run
 
![IMG-20241019-WA0010](https://github.com/user-attachments/assets/e532f49e-b60f-4629-bb39-9f9b4085b36f)


For Transient Analysis Settings and Output
 
 ![IMG-20241019-WA0013](https://github.com/user-attachments/assets/92433262-d11d-460f-899b-5c3d1e661266)

 ![IMG-20241019-WA0014](https://github.com/user-attachments/assets/eef27219-4166-4c49-8662-ee7e0ddb6894)


Results:
The design and implementation of the D-flip-flop using Cadence EDA tools were successfully completed. The simulated results confirmed the correct operation of the flip-flop, with proper synchronization of the input data with the clock signal. Key performance parameters such as propagation delay, power consumption, and area utilization were evaluated, aligning with expected theoretical values.











