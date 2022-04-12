# Tilt-Switch

ECE 387 Project

This device is a TM1000 E series tilt switch.

Check the Wiki page for the tutorial example video, datasheet, and report.

---Code Description---

The code is very simple and has the inhouse LED on when the tiltswitch is open and turns off when the tilt switch closes. It also has a 50 ms debouncer to make sure the switch is in a stable state before changing the LED to a different state. 

--Note--

I was unable to get the arduino code running in C and compile using avr-gcc. I figured that an arduino file was better than nothing on the code side of things.
