# AIM:
To simulate and synthesis d flipflop using vivado
# APPARATUS REQUIRED:
vivado
# PROCEDURE:
```
STEP:1 Start the vivado software, Select and Name the New project.
STEP:2 Select the device family, device, package and speed.
STEP:3 Select new source in the New Project and select Verilog Module as the Source type.
STEP:4 Type the Fille Name and module name and Click Next and then finish button. Type the code and save it.
STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.
STEP:7 compare the output with truth table.
```
# D_FLIPFLOP
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/4f3e1d9d-e0c3-464e-b0e4-e47946c813bd)
# Truth Table
![image](https://github.com/RESMIRNAIR/D_FLIPFLOP/assets/154305926/42d38f79-9cc3-4b09-a46f-e0c1241dee57)
# VERILOG CODE:
```
module dff(clk,rst,d,q);
input clk,rst,d;
output reg q;
always@(posedge clk)
begin
if(rst==1)
q=1'b0;
else
q=d;
end
endmodule
```
# OUTPUT:
![WhatsApp Image 2024-04-19 at 19 29 38_c393e8d9](https://github.com/Afsar1276/D_FLIPFLOP/assets/161407741/2b98c153-6b6f-4a30-ac52-aee8f9a37ae9)

# RESULT:
Thus, the verilog program for d flipflop has been simulated and verified successfully.
