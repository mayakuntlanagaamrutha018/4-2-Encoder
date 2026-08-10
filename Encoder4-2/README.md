# 4-to-2 Encoder using Verilog

## Description

A 4-to-2 Encoder is a combinational digital circuit that converts
one of four active input lines into a 2-bit binary output.

## Inputs and Outputs

- Inputs: D[3:0]
- Outputs: Y[1:0]

Only one input should be HIGH at a time.

## Truth Table

| D3 | D2 | D1 | D0 | Y1 | Y0 |
|----|----|----|----|----|----|
| 0  | 0  | 0  | 1  | 0  | 0  |
| 0  | 0  | 1  | 0  | 0  | 1  |
| 0  | 1  | 0  | 0  | 1  | 0  |
| 1  | 0  | 0  | 0  | 1  | 1  |

## Files

- `encoder_4to2.v` - Verilog design code
- `encoder_4to2_tb.v` - Testbench
- `encoder_4to2.vcd` - Simulation waveform

## Simulation

The testbench checks all four valid input combinations.

The waveform can be viewed using a simulator such as GTKWave.

## Tools Used

- Verilog HDL
- Icarus Verilog
- GTKWave

## Applications

- Data encoding
- Digital communication
- Priority encoding systems
- Digital logic circuits
