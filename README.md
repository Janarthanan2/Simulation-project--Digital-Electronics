# TITTLE
![image](https://github.com/Janarthanan2/Simulation-project--Digital-Electronics/assets/119393515/fed10c4e-702a-4bd9-b42c-97ecbe52f98d)
Design and simulate the logic diagram using Verilog

# THEORY
A Karnaugh map (K-map) is a visual method used to simplify the algebraic expressions in Boolean functions without having to resort to complex theorems or equation manipulations.
# LOGIC DIAGRAM
![Screenshot 2023-06-14 134256](https://github.com/Janarthanan2/Simulation-project--Digital-Electronics/assets/119393515/0c90a696-7c45-4a4c-ac89-522508398fc7)
# NETLIST DIAGRAM
![Screenshot 2023-06-14 134256](https://github.com/Janarthanan2/Simulation-project--Digital-Electronics/assets/119393515/0c90a696-7c45-4a4c-ac89-522508398fc7)

# TIMING DIAGRAM
![Screenshot 2023-06-14 134612](https://github.com/Janarthanan2/Simulation-project--Digital-Electronics/assets/119393515/af734cda-3289-4911-b7cb-046fa938c9fc)

# PROGRAM
```
module assignment(x,y,z,f,fdash);
input x,y,z;
output f,fdash;
wire xdash,ydash,a,b,c;
not(xdash,x);
not(ydash,y);
nor(a,x,y,z);
nor(b,xdash,ydash,z);
nor(fdash,a,b);
not(f,fdash);
endmodule 
```
# REFERENCE
![WhatsApp Image 2023-06-14 at 13 56 36](https://github.com/Janarthanan2/Simulation-project--Digital-Electronics/assets/119393515/639cc021-7bc2-40e5-8a09-a9f11261fd26)
