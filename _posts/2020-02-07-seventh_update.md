---
layout: default
title: Feb 7 - Conestoga Visit - 1
---
# Feb 7 - Conestoga Visit - 1

- Today we visited Conestoga College at their Respiratory Therapy lab. They had some very useful equipment to test BVM techniques, including a test lung that is capable of measuring pressure in the lungs (intrapulmonary pressure), pressure at the mouth or airway (proximal pressure), and volume delivered to the lungs (tidal volume).

- The test lungs allow you to change different simulated biological parameters includes lung stiffness and airway resistance. These changes can be used to mimic different conditions for various patients, such as someone with asthma or a heavy smoker. For now, we are focusing on an average healthy adult. A video of the test operation is shown.

<p align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/Ua4sCcsDB1g" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
&nbsp;

- A series of trials were conducted with this setup. The data we gathered showed us what we need to do to improve our design. As previously suspected, even though the bag is being squeezed quite a lot, the total volume of air our setup can deliver is just over 300 mL on average. The target volume for the selected parameters is 500 mL. The motor torque stalls out before the bag is fully compressed, however another observation was also made. the pressure point contacts between the strap and bag are focused on one location instead of being spread out more like a hand. this results in less overall compression for a given strap tightness. We will need to adjust this aspect moving forward.

- Also, the pressure delivered at both the airway and the lungs was quite low. Currently, the motor is being driven at 10.8 V but it's full power is 12 V. We would need to acquire a full 12 V motor driver to fix this, or hopefully, the new servo should be sufficiently strong and fast.

<figure align="center">
  <img src="/assets/img/Volume_Test_1.JPG" width="300" />
  <img src="/assets/img/Pressure_Test_1.JPG" width="300" />
</figure>


- These observations will be used to modify the design moving forward. Our goal is to finalize the design next week and produce a full prototype for more extensive testing. We have already confirmed with the Respiratory Therapy Lab that we could return to perform more testing as required.
