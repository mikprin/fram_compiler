# FRAM gds and netlist compiler

This is a README file for MIPT lab fram memory compiler.

## Author: Solovyanov Mikhail

### About:
Compiler is aimed to create gds and simulation representation of embedded FRAM memory array with given paramethers. You are free to change them in annotated array_config file.

Compiler includes pre-made views of all cells such as:

- memory_cell = One 1T-1C cell
- sense_amp = non destructive comparator for in and ref signals
- driver (aka bl_driver) - high off state  impedance  driver connected directly to BL
- pmos and nmos for decoder creation
- PL driver = driver for plate line


### Usage:

For quick run just run: python3 fram_array.py

Also you are welcome to make changes in config.py file which is a main config.

Debug level show how much of an iformation you wanna get about the prosessing to the terminal.

### Dependencies
Require:
Python 3 ! (python 2 is not supported)
klayout for python ( "pip3 install klayout" )

tested on python3.6


Optional:
gdsMill for pdf print (in future)

### List of all files:


---------output---------------
fram_sample.sp - OUTPUT netlist example
./gds_files/fram_sample.gds = GDS file
./netlists/fram_sample.gds = netlist output

any questions you can ask here:

e-mail: solovyanov.mm@phystech.edu
