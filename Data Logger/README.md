# Data Logger in TwinCAT 3
This program was made to go through the core concepts of PLC programming. It have tried to write the program in a way that it utilizes all of the main programming pratices
i.e. Enumeration, Structures, function blocks, Arrays, pointers etc. 

# How to use it
After running the program on the soft PLC, go to the MAIN program. Write a "true" value to the variable "bRunOnlyOnce". This logs this particular event in an array. 

To see the logged data, click the + sign besides EventLogger. Then open up aEventBuffer, and further open aEventBuffer[1]. From dtTimeStamp you would be able to see that it has
logged the current date and time. 

You can repeat the process and the next log would be at aEventBuffer[2]
