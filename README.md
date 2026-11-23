Elevator Controller

Project Overview

The VLSI Elevator Controller is a digital design project implemented using Verilog HDL. It controls a four-floor elevator system by accepting multiple simultaneous floor requests and servicing them based on a priority-based scheduling mechanism.

Objectives

* Understand sequential logic design.

* Design a four-floor elevator controller.

* Implement multiple simultaneous floor requests.

* Develop priority-based request servicing.

* Control elevator movement and door operation.

* Verify the design using simulation.

Features

* Four-floor elevator control.

* Multiple simultaneous floor requests.

* Priority-based request servicing.

* UP and DOWN movement control.

* Automatic door opening and closing.

* Floor position tracking.

* Asynchronous reset.

* RTL simulation and verification.

Hardware and Software Requirements

* Xilinx Vivado

* Verilog HDL

* FPGA development board (optional)

Default Configuration

* Number of Floors: 4

* Initial Floor: Floor 1

* Floor Requests: 4-bit input

* Request Priority: Floor 4 > Floor 3 > Floor 2 > Floor 1

* Elevator Movement: UP and DOWN

* Door Operation: Automatic

* Reset: Asynchronous Active High

Project Structure

```text
VLSI-Elevator-Controller/
├── src/
│   └── elevator_controller.v
├── testbench/
│   └── elevator_controller_tb.v
└── README.md
```

Simulation Procedure

* Open Xilinx Vivado.

* Create a new RTL project.

* Add the main Verilog source file.

* Add the testbench as a simulation source.

* Set the testbench as the simulation top module.

* Run Behavioral Simulation.

* Observe elevator floor transitions.

* Verify multiple simultaneous requests.

* Observe priority-based request servicing.

* Verify motor and door control signals.

Power Analysis Procedure

* Open the Vivado project.

* Select the target FPGA device.

* Run Synthesis.

* Run Implementation.

* Open Report Power.

* Observe dynamic and static power consumption.

* Generate the power report.

Applications

* Digital electronics.

* VLSI design learning.

* FPGA-based elevator control.

* Finite State Machine (FSM) implementation.

* Priority-based control systems.

* Digital automation systems.

Author

Rahulji R

License

This project is available for educational purpose.


