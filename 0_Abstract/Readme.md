* Interfacing comprises of hardware (Interface device) and Software (source code to communicate, also called as the Driver). Simply, to use an LED as the output device, LED should be connected to Microcontroller port and the MC has to be programmed inside make LED ON or OFF or blink or dim.
 
 *The major uses of LED (Light Emitting Diodes) are to illuminate objects and even places. Its application is everywhere due to its compact size, low consumption of energy, extended lifetime, and flexibility in terms of use in various applications

Light Emitting Diodes or LEDs are the mostly commonly used components in many applications. They are made of semiconducting material. In this project, I will describe about basics of Interfacing LED with  Microcontroller.

LED interfacing is the first thing, one would try to do while getting started with any microcontroller. So here in this tutorial we are going to interface a LED with  microcontroller, and will write a C Program to blink the LED. We have used a very popular microcontroller AT89S52, , by ATMEL.

Before going into detail, we should get some brief idea about microcontroller AT89S52. It is 40 pin microcontroller, and has 4 ports (P0,P1,P2,P3), each port have 8 pins. We can consider each port as 8 bit register, from the software point of view. Each pin having one Input/output line, means every pin can be used for input as well as for output, i.e. to read data form some device like sensor or to provide its output to some output device. Some pins have the Dual functionality, which has been mentioned in bracket in Pin Diagram below. Dual functionally like for interrupt, counters, timers etc.
