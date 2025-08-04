1️⃣ ARITHMETIC LOGIC UNIT

An arithmatic logic unit is an important part of central processing unit and performs arithmatic and logic operations. It can take inputs as multiple bits through an input register. It is the fundamental building block of the central processing unit of a computer.The ALU is the mathematical brain of a computer. The first ALU was INTEL 74181 implemented as a 7400 series is a TTL integrated circuit that was released in 1970.
This project simulates an Arithmetic Logic Unit (ALU) using Icarus Verilog and visualizes waveforms via GTKWave.

2️⃣ Tools Used

Icarus Verilog for compilation & simulation
GTKWave for waveform visualization

3️⃣ Command Used

iverilog -o alu_test alu.v alu_tb.v
vvp alu_test
gtkwave alu_waveform.vcd

