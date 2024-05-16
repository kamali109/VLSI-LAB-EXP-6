
#                               INVERTER SCHEMATIC USING CADENCE
# AIM:
```
    To Schematic and Simulate Inverter using CADENCE virtuoso.
```
# APPARATUS REQUIRED:
```
CADENCE VIRTUOSO
```
# PROCEDURE:
```
Procedure for Commands to get into Cadence

    Right Click and open the terminal window
    Type the following commands as follows and press enter.
    i) tcsh
    ii) source /home/install/cshrc
    iii) virtuoso
```

Procedure for Schematic simulation using Cadence
```
    Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…"
    Close the 2nd window
    Use 1st window i.e virtuoso window(CIW) for further processing.
    i) Create a New Library
    ii) Create Schematic Cell view.
    iii) Create the Symbol for schematic Cell view.
    iv) Create the test Cell view.
    v) Analog simulation by spectre
```

Procedure for Creating New Library
```

a) File –New – Library
b) Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK
c) Attach the library to the technology library gpdk045.Click OK
Create Schematic Cell view.
```
```
a) Go to 1st window i.e virtuoso(CIW)
b) File-New-Cell view
c) Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic
d) Type: Schematic press OK
e) Add the required components from the libraries and make the connections.
f) Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos
g) Analog library Vdd, Gnd, Vcc, Vpulse, Vsin
h) Make the connections by using fixed narrow wire key
i) Click Check and Save button
```

Creating the Symbol for schematic Cell view
```
a. In the schematic window, execute Crate – Cell view – From Cell view The cell view from cell view window appears Check Lib Name, Cell Name, From View name must be schematic Press ok
b. Now Symbol generation form appears. Click Ok If No changes required
c. A new window with with default symbol is created.
d. Edit the symbol if you want to give actual symbol shape else continue.
i. Execute Create-Cell view-from cell view
ii. Library Name and Cell Name must be same which you have used for schematic. Press OK
iii. Check for the position of pin side.Prss OK
iv. Edit for the shape by Create-Shape-Choose required options to edit.
```

Creating the new test cell view
```
a) Go to CIW window, Execute File-New-Cell view
b) Setup the new file form
Library: Select the one you a created.
Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test
View: Schematic
Type: Schematic press OK
Analog simulation by SPECTRE.
a. In test cell view window
b. Launch – ADE L(Analog Design Environment)
c. Execute Setup—Simulation/directory/Host A new window opens
d. Set the simulation window to spectre and click ok
e. Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK.
f. Execute Analysis – Choose. A window opens.
g. Select the type and set the specifications and press OK
h. Execute Output s—to be plotted – Select on Schematic
i. Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse
j. Execute Simulation -- Net list and Run

```

Simulation Settings

Setup for transient analysis:
```

    Stop time = 400n
    Setup for D.C analysis
    Component to be selected in schematic is for d.c analysis
    Start = -1 Stop = 1 resp.
```
# CMOS INVERTER:

![330746618-3e336a66-13c5-4da6-956f-b8195b3a4a21](https://github.com/kamali109/VLSI-LAB-EXP-6/assets/160600794/8fa4f52f-f4c6-409f-9b9d-62b218c00845)

![330746724-406f55bd-11f9-41e5-9592-c52a4d219b9a](https://github.com/kamali109/VLSI-LAB-EXP-6/assets/160600794/4978f130-71e0-44c3-b197-47e7b731aae4)

# OUTPUT:

![330746922-c3546127-c5f4-4802-b709-898757e349c9](https://github.com/kamali109/VLSI-LAB-EXP-6/assets/160600794/5e64a067-7202-4cae-9758-9d92e3d0ee80)

# NANDGATE:

![330751905-f54e8aa1-f7c1-498b-9c36-d532819ca0e8](https://github.com/kamali109/VLSI-LAB-EXP-6/assets/160600794/11b595bf-6f49-4401-a4e9-d758c628816a)

![330752067-c909717f-baca-4f7a-9358-009b6c950e77](https://github.com/kamali109/VLSI-LAB-EXP-6/assets/160600794/f78cd8a9-bbd9-49ee-883e-ef60ff2a4837)

# OUTPUT:

![330752587-9ae8390a-57cf-454a-a78d-cbfd868c8176](https://github.com/kamali109/VLSI-LAB-EXP-6/assets/160600794/30039a2b-a62d-4a97-8bff-a5a27b06179a)

# NORGATE:

![330752790-71f05040-35df-405f-bb47-3630a781cedc](https://github.com/kamali109/VLSI-LAB-EXP-6/assets/160600794/2a077d33-ca31-48b7-8cd0-6644fb45ccbf)

![330752976-840cf0b0-3d45-465a-af8c-a56f13c09a25](https://github.com/kamali109/VLSI-LAB-EXP-6/assets/160600794/1c7bfdc0-f142-443c-a3d3-ff47931957d1)


# OUTPUT:

![330755446-94d85148-2ba5-4722-99bc-af66a2319183](https://github.com/kamali109/VLSI-LAB-EXP-6/assets/160600794/bed49d00-d38b-4645-8cd0-8ed0108c6170)

# RESULT:
```
   The schematic and simulate inverter using CADENCE is done and verified successfully.
```
























    
