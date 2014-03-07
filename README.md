ECE_281_CE3
===========

#Moore

![alt tag](http://s21.postimg.org/y7vkwh8o7/moore_screenshot.jpg)

I checked the output manually. It was working well. 


#Mealy 

![alt tag](http://s1.postimg.org/kg3q25jhr/Mealy_screenshot.jpg)



Questions:

1-"Is reset synchronous or asynchronous?"

Reset is synchronous because "if" statement that implements is proceded by another "if" that detects a rising edge of the clock.

2-"Will you mealy machine be different from your moore machine?"

No. Just added few lines at the end.

3-"What is the clock frequency? What value would we set to simulate a 50MHz clock?"

Frequency=1/T 

T-period

So our clock frequency is 100MHz. 

To get 50Mhz, one need to set clock value to "20ns"
