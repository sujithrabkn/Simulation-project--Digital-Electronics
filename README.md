# DESIGN AND SIMULATE THE LOGIC DIAGRAM USING VERILOG

## AIM

To Design and simulate the logic diagram using Verilog.

## EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher.

Software – Quartus prime.
## PROCEDURE

Step 1:
Create module encoder and decoder.

Step 2:
Get inputs and outputs for encoders and decoders.

Step 3:
perform or operation for encoder and and logic for decoders.

Step 4:
perform RTL LOGIC and get waveform.

Step 5:
End the module.

## LOGIC DIAGRAM
![283732685-192afdd5-09ff-4d1d-bcee-5b93e348f39d](https://github.com/sujithrabkn/Simulation-project--Digital-Electronics/assets/119477857/a6fb8c2d-ce4f-4ffc-a189-609ab0a05350)

## NETLIST DIAGRAM

![283732838-f9bf5e4d-8d4f-4906-bfdd-fddc6371478a](https://github.com/sujithrabkn/Simulation-project--Digital-Electronics/assets/119477857/47202004-8d40-4967-a9b8-1bc8782f49f7)

## TIMING DIAGRAM
![283732859-5238e1f8-9dc6-4bb8-b596-e556dd9b8bbf](https://github.com/sujithrabkn/Simulation-project--Digital-Electronics/assets/119477857/31f4de35-3e4d-4701-9228-f31a92183e30)

## TRUTH TABLE

![283732986-0ca20176-dd8e-49da-99ef-d3993d06c991](https://github.com/sujithrabkn/Simulation-project--Digital-Electronics/assets/119477857/f1b5d97a-1b6a-4c5f-8a09-fa3b3fab29da)


## PROGRAM
```
Program to To Design and simulate the logic diagram using Verilog.
Developed by: SUJITHRA B K N
RegisterNumber: 212222230153
module e13(x,y1,y2,z1,z2):
Input x,y1,y2;
Output z1,z2;
Assign z1=(x&y) | ((~x) & y2);
Assign z2=((~x)&y2) | (x&(~y1));
endmodule
```
## RESULT

Thus the program to design and simulate the logic diagram using Verilog.
