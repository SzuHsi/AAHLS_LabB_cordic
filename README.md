# AAHLS_LabB_cordic

## Description of the function
*  Coordinate Rotation Digital Computer (CORDIC) is a simple and efficient algorithm for trigonometric functions based on vector rotations

*  Can be used for polar-to-rectangular and rectangular-to-polar conversions

*  Using only shifts and adds to performing vector rotations
## Build flow
1. Creat a vitis project and add the source code in src/

2. Run CSIM and COSIM to verify the function

3. Export the RTL code

4. Creat a vivado project and connect the IP to the PYNQ processor
![This is a alt text.](/imag/sample01.PNG "This is a sample image.")
 
5. Find the overlay file(.bit & .hwh) in the vivado folder

6. Upload the overlay to the FPGA and use the host code to control the kernel
## Result / Analysis
* aa
|               | original      |       unroll  |
|:-------------:|:-------------:|:-------------:|
|Latency (cycle)| 62            | 8             |
## Platform 
Xilinx PYNQ-z2

