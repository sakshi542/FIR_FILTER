# FIR_FILTER
Simulated a 9-tap low-pass FIR filter in Verilog for Basys 3 FPGA. Used CORDIC-based DDS to generate a noisy signal (150 Hz + 400 Hz) and filtered out high-frequency noise.

Optimized critical path using pipelining for improved timing.
Performed power analysis comparing pipelined and non-pipelined designs.
FIR coefficients designed in MATLAB and quantized to 16-bit fixed-point.
Successfully verified functionality in simulation (Vivado).
Tools: Verilog, Vivado, MATLAB.
