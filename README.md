# gcode-mill-pocket
Python library to generate GCODE tool path (CNC) for N-sided pockets 
-- define the pocket by its edges/corners/verticies and then enter some machining parameters like cutter diameter, speeds and feeds etc.
NOTE: This program does not generate a complete CNC GCODE program-- you will need to enter initialization parameters at the start of the program and possibly after tool changes that are specific to your machine tool, tools etc. This script simply generates tool paths you can cut and paste into your full program once all that boiler plate has already been taken care of. 

Make sure you verify the correctness and safety of the program yourself before running. This is no substitute for a competent machinist, its simply a time saver/quick iterator. 
