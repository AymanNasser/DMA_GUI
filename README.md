# DMA_GUI

GUI 
•	Could browse any assembly file located in the system
•	Supports User Interface to generate assembly instructions that can access the Verilog code to initiate DMA operations
•	Checks registers ranges to match the allowed range & detect if negative number is specified showing error message
•	Three edit boxes to specify source, destination & count of bytes to transfer in memory to memory mode 
•	Six edit boxes to specify DMA registers in (Program DMA) mode (not completed).


Simulation GUI
•	Animation Coloring for BUSs as indication for using the bus.
•	In Write Bus Transfer the Address Bus, Data Bus and Control Bus get colored with the Master’s Color, and in Read Transfer the Data Bus get colored with the Active Slave Color, and Control and Address Bus get colored with Master’s color.
•	Visualizes the current program counter and current executed instruction.
•	Supports visualization of requesting the bus from DMA or CPU.
•	Shows the waiting states of both CPU and DMA if one of them waits bus. 
•	User can control the clock cycles forward and backward.
•	Supports User Interface Buttons and Progress Bar to control the cycles, show the progress of the clock cycles and a play-stop button for auto-play animation.
•	Supports Data acquisition for values of data bus, address bus, control bus.
