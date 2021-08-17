This code is for the  dds 9850 module hc-sr08 .
For the serial mode you have to connect the D2 pin of the module to the ground and D1,D0 to VCC.
You have to make GPIO output pin in the STMcoding for chip select signal to FU_UD
Connect the MOSI Pin from Stm32 to DATA/D7 in the module.
The Sck pin to the W_Clk pin in the module
