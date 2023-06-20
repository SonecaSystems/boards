Digital to analog converter with serial data input.

The module is made up of two functional blocks:
- First block is built with 74hc595 integrated circuit. It is a shift register that is responsible for converting 8-bit serial data
chains to parallel protocol.
- Second block is an 8bit dac with parallel input. It is a set of resistors in series and parallel configuration which convert the digital signals 
coming from the shift register output to analog signals. The range is from 0 to 5 volts.

h2.The product is designed to control analog signals such as synthesizers, lights, motors or solenoid valves from the ports of the microcontroller.

The advantage offered by this assembly is that unlike the parallel r2r that uses 8 pins for its connection, it only needs 3 pins as it is controlled by the 74hc595 shift 
register.

1.  Serial In
2.  Clock
3.  Latch
4.  DAC Out
5.  5V
6.  Gn
