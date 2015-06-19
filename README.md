# MIPS-Logisim
Author Jagdeep Singh & Muhammed Shafiq

Emulating MIPs instructions in multicycle, single cycle and 5 staged pipeline  
Instructions must be given in HEX and converted to little endian 
Aside can be used to convert MIPS into Hex and then transfered over into little endian 
Aside can be found at
http://csiflabs.cs.ucdavis.edu/~ssdavis/50/

A mips instruction like 
add  $1, $1, $1
would come out in hex from aside as 
20082100
and must be put into a text file and loaded into the intruction memory as 
00210820

Using aside 
1)simply type the wanted instruction and make sure CPU is set to MIPS
2)hit assemble found in the toolbar right side next to CPU (black button)
2)Open the .obj file with a text editor to read HEX instruction

Loading Instruciton
1) Simply right click the instruction ROM (usually the left most ROM)
2) hit load and select intruction file
