Lesson 4 Exercise: Make Blinky
==
On your final project board, make blinky for yourself. Then add a button to turn the LED on and off. Bonus points for making the button cause an interrupt. Triple bonus points for debouncing the button signal.

I used two LEDs (a red LED for simply blinking and a green LED for turning on/off based on the blue button status).  The red LED is on Pin6/PortH and the green LED is on Pin7/PortH.  There was added code to debounce the button signal so that it triggers on the rising edge only after waiting for 5ms.  The button is on Pin13/PortC.
