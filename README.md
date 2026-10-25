3-input NAND gate, AMS 0.35 um
Layout and simulation of a 3-input NAND gate in the AMS 0.35 um CMOS process (c35b4). The layout is drawn in Magic and the extracted netlist is simulated in HSPICE.

Files
nand3.mag - the layout of the gate
nand3_ld.* - the version used for simulation: layout, extracted netlist (.spice), HSPICE netlist (.sp) and the HSPICE output files (.tr0, .mt0, .st0)
nand3.pdf, nand3_ld.pdf - printouts of the layout
nand3_waveform.pdf, desex1_waveform.pdf - simulated waveforms
nand3.sv, nand3.tcl - supporting files
How it was done
Draw the NAND3 layout in Magic using the c35b4 technology.
Extract the layout to a SPICE netlist.
Run a transient simulation in HSPICE and look at the output waveform.




