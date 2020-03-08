---
layout: default
title: Mar 4 - Conestoga Visit - 3
---
# Mar 4 - Conestoga Visit - 3

- This was, by far, our best visit to Conestoga. We were able to get very good volume measurements and insightful pressure measurements. The most important detail is that our device is able to hit the 500 mL target. In fact, in its current configuration, it outputs a maximum of about 560 mL of air.

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/RYOD9RQdotk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

- Shown below is the test lung volume indicator, displaying a reading of 500 mL during a compression cycle. This indicator gives a good representation of the approximate volume the design is achieving, but a more precise measurement was needed to fully characterize and validate the compression function.

<figure align="center">
  <img src="/assets/img/test_lung_500.jpg" width="250" />
</figure>

- Luckily, we were offered to use a much more accurate volume indicator, called a Wright Respirometer. Shown below is the Respirometer indicating an output of about 560 mL.

<figure align="center">
  <img src="/assets/img/respirometer.JPG" width="250" />
</figure>

- Some interesting observations came out of these tests. From the data we collected, the volume output seems to be <i>very</i> consistent. For a given servo command, the maximum deviation of the output is about 10 mL, which is only 2% of the nominal adult volume requirement. Also, after recording volume outputs for different servo positions, a quadratic relationship was identified for this region of operation, as shown below.

<figure align="center">
  <img src="/assets/img/volume_vs_servo.JPG" width="450" />
</figure>

- Also worth noting is that the servo angle of 210 degrees has been identified as a reasonable maximum angle for the servo. Commands for the servo to compress the bag past this angle result in a stall of the servo due to torque limitations, and are therefore not useful. Commands beyond this region would be unnecessary regardless, as the achievable volume is already surpassing the nominal target value, and the bag is compressed almost completely at this angle.

- Next, the electronics within the control box will be connected and tested. The entire design will also be painted.
