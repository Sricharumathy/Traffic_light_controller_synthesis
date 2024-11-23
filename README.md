### Traffic_Light_Controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

### Synthesis RTL Schematic:

![Screenshot 2024-11-23 115006](https://github.com/user-attachments/assets/c33e7a40-7a76-4b61-9d5f-1e7ef94987d0)


### Area report:

![Screenshot 2024-11-23 115034](https://github.com/user-attachments/assets/b1ee8262-b156-4933-a645-9d6827a0236c)


### Power Report:
![Screenshot 2024-11-23 115157](https://github.com/user-attachments/assets/8dfc3fc1-673a-4637-ab94-5725f3e4f681)



### Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
