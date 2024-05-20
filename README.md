# AIM:

To simulate and synthesis half subtractor using vivado 2023.2

# APPARATUS REQUIRED:

vivado 2023

# PROCEDURE:
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.

# HALF_SUBTRACTOR

# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/d0d5980a-6bcf-4ede-a54e-6aae3fb5f5f2)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/df70da69-5a12-4a0d-ab84-a98dad3f7e70)
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/2f2d6a4d-9eda-4165-8579-1d7490b5fe97

# Verilog code:

module halfsubtractor(a,b,diff,borrow);

input a,b;

output diff,borrow;

xor g1(diff,a,b);

and g2(borrow,~a,b);

endmodule

# output:

![image](https://github.com/SivaShankar33/HALF_SUBTRACTOR/assets/125188331/7f509741-1e87-45d7-93c6-65fdde270615

# Result :

Thus the simulatation and synthesis of half subtractor using vivado was successfully executed and verified.



