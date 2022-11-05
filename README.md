# PS2-KeyBoard-Interface
Purpose: 1- Understand how computers communicate with peripherals.
2- Design the PS2 Interface using VHDL.
Theory: 
The PS2 interface was introduced by IBM in 1987 for connecting computers to keyboard and mouse devices. Even though it is now giving place to the USB (universal serial bus) interface, its study helps understand how computers communicate with peripherals, also allowing interesting designs to be developed in the lab section
We conclude this section with the design (using VHDL) of a simplified
keyboard interface.
The system is depicted in figure, which shows a PS2 keyboard connected
to an FPGA, which in turn feeds an SSD. We want to design a circuit
capable of reading the numeric (0, 1, ... , 9) keyboard keys and display
them on the SSD when such keys are pressed. If any other keyboard key
is pressed, then "e" (error) must be displayed. On the other hand, if the
error occurs in the read key (that is, if the start bit is not '0', the stop bit is not ‘1’ , or if the parity is not odd), then “E” must be displayed.

![interface](https://user-images.githubusercontent.com/110431487/200134120-bf9189be-e934-4612-9d72-324737c52146.jpg)

