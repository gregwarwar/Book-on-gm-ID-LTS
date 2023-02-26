# Book-on-gm-ID-LTS
LTSpice symbols and models based on book : P. G. A. Jespers and B. Murmann, "Systematic Design of Analog CMOS Circuits"

1. Unzip the LTS_GMID

2. Open the file "first.asc" in LTSpice and hit simulate
   This should plot gm/Id of a W=10.0 L=0.18 device

3. Open the file example_3p1.asc
   This should run the Example 3.1 from the book, although we modify the target frequency from

   fu = 1.0GHz   --->    fu = 250MHz

   We do this since the book is based on 65nm technolgy, and the models we have are 0.18u


