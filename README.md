# eceCapstone24
This is the software for our ECE Capstone project, a Battery Management System

The .ino file contains all the code needed to run the general loop and test the BMS. One thing to note is to successfully communicate to the LTC6820, the chip select pin CS_PIN needs to be defined properly. It is defined in the .ino file, but it is also defined in the LTC681x.h file, which is why that is included. The .ino file will not compile without all the other files from the LTSketchbook, so make sure to download those first. 

Link here to download the LTSketchbook: https://github.com/analogdevicesinc/Linduino/tree/master
Be sure to set the LTSketchbook folder as your path, or move the required files to the path you are working in. 

I have included the files from Altium as well for public viewing. 
- Ryan
