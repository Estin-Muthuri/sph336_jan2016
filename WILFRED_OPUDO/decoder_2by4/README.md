This is a 2-by-4 decoder example

    make decoder


A line decoder is a device that changes the input code into a set of signals.<br>
It takes an n-digit binary number and decodes it into 2<sup>n</sup> data lines.
It does the reverse of encoding. <br>
In the following truth table, only the output D0 is high when the input is zero, and the output D1 is high when the input is 1. it decodes a single digit binary number.
Only one signal is high(selected) when the right binary number is available on the input. <br>
Its truth table: 
<p align="left">
  <img src="2by4truthtable.png" width="250"/>
</p>

Circuit:
<p align="left">
  <img src="2by4circuitdiagram.png" width="200"/>
</p>

Model of computation:
<p align="left">
  <img src="2BY4MOC.png" width="400"/>
</p>
Results:
The above MOC was implemented in systemc (code in this folder) and the following output found from traced signals.<br>
Traced signals timing diagram:
<p align="left">
  <img src="2by4timer.png" width="600"/>
<p>


