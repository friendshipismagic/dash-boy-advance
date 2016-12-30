Dash Boy Advance
================

An fpga-based processor capable of running Game Boy Advance ASM code.

# Description

An implementation of a Game Boy Advance CPU writton in System Verilog. The goal
is to build a fully-working GameBoy Advance 'emulator' on an fpga-based
hardware.

# Inspirations

The design is based on the book "Computer Organization and Design" by David A.
Patterson and John L. Hennessy (4th ed. 2008). This is a CPU Design superbible.

If you want a course, just take the [Embedded Systems](https://sen.enst.fr)
course at Télécom Paristech :)

# Requirements

You need Quartus and ModelSim to build the code and simulate it. It can be
easily changed to whatever System Verilog simulator. To run a program during
simulation, you also need a cross compiler or a ready-to-execute ROM (you can
get one from the internet).

# License

Project done by [didjcodt](https://github.com/didjcodt), please check LICENSE
file for more information.
