# AIM:
To Design and simulate the logic diagram using Verilog.

# HARDWARE REQUIRED:
– PC, Cyclone II , USB flasher

# SOFTWARE REQUIRED:
Quartus prime

# LOGIC DIAGRAM:

![image](https://github.com/Preetha-Senthamilan/Simulation-project--Digital-Electronics/assets/119390282/1021288a-85e0-486b-875e-b070ccee2362)


# Procedure:

Step1:

create module encoder and decoder.

Step-2:

Get inputs and outputs for encoders and decoders.

Step-3:

perform or operation for encoder and and logic for decoders.

Step-4:

perform RTL LOGIC and get waveform.

Step-5:

End the module.

# PROGRAM:

```
Program to To Design and simulate the logic diagram using Verilog.
Developed by: PREEETHA.S
RegisterNumber: 212222230110
module e13(x,y1,y2,z1,z2):
Input x,y1,y2;
Output z1,z2;
Assign z1=(x&y) | ((~x) & y2);
Assign z2=((~x)&y2) | (x&(~y1));
endmodule
```

# RTL DIAGRAM:

![image](https://github.com/Preetha-Senthamilan/Simulation-project--Digital-Electronics/assets/119390282/bb89f780-4b8c-4dae-9496-66ed60d69e2c)


# TIMING DIAGRAM:

![image](https://github.com/Preetha-Senthamilan/Simulation-project--Digital-Electronics/assets/119390282/4ea3fa6c-58fe-4089-b955-b9e3515a0a1d)


# TRUTH TABLE:

![image](https://github.com/Preetha-Senthamilan/Simulation-project--Digital-Electronics/assets/119390282/a2f2abfe-f227-4366-bf0a-859459b3f801)


# RESULT:
Thus the program to design and simulate the logic diagram using Verilog.



