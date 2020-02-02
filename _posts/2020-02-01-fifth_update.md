---
layout: default
title: Feb 1 - Motor Characterization
---
# Feb 1 - Motor Characterization

- Today, the DC motor was characterized using the simple DC motor model, which includes a pole at the origin, a pole at -1/tau, and motor constant Km.

- The step response of the motor was analyzed (encoder counts vs time), and the parameters were determined to be tau = 0.3519, and Km = 12.0969. These values were used in Simulink to simulate the action of the motor.

<figure align="center">
  <img src="/assets/img/motor_sim.JPG" width="500" />
</figure>
&nbsp;

- Now that the motor has been modeled, simulations can be run to determine the optimal controller to use in the code.
