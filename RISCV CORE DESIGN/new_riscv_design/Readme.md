# RISCV CORE DESIGN 

Before generating the RISCV CORE DESIGN as this needs fakeram So, first we need to generate the FAKERAM 

for that follow the below links

For generating the FAKERAM refer this document: https://github.com/vijayank88/OpenROAD-flow-scripts/blob/fakeram_gen/flow/platforms/asap7/fakeram.cfg#L4
Follow below steps:

*git clone https://github.com/maliberty/FakeRAM2.0.git fix-obs branch
git checkout fix-obs*
Follow the instruction on how to generate required fakeram: https://github.com/maliberty/FakeRAM2.0/tree/fix-obs#fakeram20


For , installing the FAKERAM folder go to this directory :
Desktop/OpenROAD-flow-scripts/flow/designs/asap7 
and run the above command as specified above 

 <p align="center">
<img src="https://user-images.githubusercontent.com/90523478/227723597-ea4c0cca-6ed7-4650-945a-2e6bdf930f37.png">
 </p> 
 
 <p align="center">
<img src="https://user-images.githubusercontent.com/90523478/227723469-acba6991-0a40-4659-a3cc-7660c245fac4.png">
 </p> 
 


## Now , I am facing this error in running this FAKERAM ,
as otherthan FAKERAM new RISCV design will not be able to generate properly .

For solving the above error use this command 

* python3 run.py example_input_file.cfg *

 <p align="center">
<img src="https://user-images.githubusercontent.com/90523478/227725287-7d3a56df-11a3-449e-9aa2-4a5ac802131a.png">
 </p> 


