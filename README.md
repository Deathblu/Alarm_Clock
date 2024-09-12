# Alarm_Clock
This project implements a digital alarm clock using Verilog. It features real-time clock functionality, alarm setting, and management.

## Features

- **Real-Time Clock**: Keeps track of hours, minutes, and seconds.
- **Alarm Setting**: Set and manage alarm time.
- **Alarm Activation**: Triggers an alarm when the current time matches the alarm time.
- **Reset and Control**: Includes reset and control inputs to manage clock and alarm settings.

## Module Description

- **Inputs**:
  - `reset`: Resets the clock and alarm to default values.
  - `clk`: 10Hz clock signal for real-time second generation.
  - `H_in1`, `H_in0`: Hour digits input.
  - `M_in1`, `M_in0`: Minute digits input.
  - `LD_time`: Load time input.
  - `LD_alarm`: Load alarm input.
  - `STOP_al`: Stops the alarm.
  - `AL_ON`: Turns the alarm on.

- **Outputs**:
  - `Alarm`: Indicates when the alarm time matches the current time.
  - `H_out1`, `H_out0`: Hour outputs.
  - `M_out1`, `M_out0`: Minute outputs.
  - `S_out1`, `S_out0`: Second outputs.

## How to Use

1. **Compile the Verilog code** using a suitable FPGA or Verilog simulation tool.
2. **Run the simulation** to test the functionality of the alarm clock.
3. **Adjust inputs** as needed to set the time and alarm.

## Testbench

The project includes a testbench to verify the functionality of the alarm clock module. It tests various scenarios including setting and stopping the alarm, and adjusting the time.
