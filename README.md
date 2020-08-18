# Seven-Segment-Display-Counter
This project implements a 7-segment display counter. It counts in seconds and goes upto 999 seconds

This project has been verified in the Spartan-6 FPGA board. 
Since my FPGA board has three 7-segment displays, I could only configure it to count till 999 seconds.

My clock speed is 100MHz, you need to change the counter value in the loop according to your speed.

For example, my clock speed in 100MHz, so my counter limit value(for a second) will be 10000000000.
Calculate yours accordingly.
