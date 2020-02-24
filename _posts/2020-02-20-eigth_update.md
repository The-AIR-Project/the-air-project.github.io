---
layout: default
title: Feb 20 - Potentiometer Adjustment Dials
---
# Feb 20 - Potentiometer Adjustment Dials

- BVM operation often requires adjustment to the breath rate, delivered volume, and pressure of compressions. In order to allow users to adjust settings, potentiometer dials will be used.

- Each setting has a "typical" value and reasonable adjustment offset coded into the system. Spinning the potentiometer one way will increase that setting's output, and the other way will decrease, to allow fine adjustments. Existing attempts at a solution use buttons (low, medium, high) rather than potentiometers for this adjustment, restricting the possible combinations of operating settings.

- An interesting thing to note is that the Servo motor being used claims 270 degrees of rotation, but in actuality it is about 250 degrees (measured with protractor). Also, the library controlling the Servo only accepts rotation commands from 0 to 180. Therefore, the desired position in the physical range of the Servo must be mapped to a value in the programmable range of the Servo (i.e `pos_to_write = map(desired_pos, 0, 250, 0, 180)`).

- The software has been written and tested. It is currently in a state where the system acts correctly according to the potentiometer dials. However, the typical and adjustment values currently coded are for demonstration purposes only. More research will need to go into what these values should be, and then testing at Conestoga College will lead to system identification so that we can reliably achieve these values.
