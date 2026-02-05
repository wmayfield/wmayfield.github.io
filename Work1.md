**Back to main page:** [Main](https://wmayfield.github.io/)


## Thorlabs Internship: 
So I kind of have to be somewhat vague here but I can paint the picture of what I worked on. Unfortunately I will not be providing any pictures on this. I was working on a new product for Thorlabs for instrumentation in a lab. For those not familiar with Thorlabs, it is an optics/photonics company that makes components and devices particularly for research, quantum applications, and healthcare applications.

#### Inut:
The product I was working on was a board that could take in up to a 1MHz signal and provide gains from unity to 60dB. The signal would go through a gain stage and then a filter stage before being input into an ADC for signal processing. I spent many hours perfecting a 4th order multiple feedback in LTspice for this. A main focus of mine was lowering noise and I achieved a 10nV/$\\sqrt{Hz}$ noise metric at 0 gain from the input to the ADC. 

### Output: 
The output utilized a current-based DAC into a transimpedance amplifier for noise purposes. Then, it was sent through a 2nd order sallen-key filter to the output of the device

### Power Distribution:
I utilized LDOs for analog supplies and DC-DC converters with three-pole LC filters on either side of the switcher for digital supplies. There were 7 different rail levels for this board.

### Interfacing:
The microchip selected was a BGA chip for the signal processing as there were many pin connections needed. This MCU interfaced PGAs, DACs, FRAM, SDRAM, ethernet communications, and USB communications.

### Layout and Stackup: 
I did not complete the layout by any means but I got practice routing ethernet and power on a 6-Layer SIG/GND/PWR/SIG/GND/SIG for best power/signal integrity (especially for the BGA MCU). I also started looking at how to route the BGA and got some practice on that with capacitor placements and found it to be satisfying.

### Reflection:
I am super grateful to have had this opportunity working at Thorlabs as I was able to come into work and learn everyday. I gained so much knowledge regarding the bringup of boards, standard rules, and the reasoning behind those rules. It furthered my curiosity in electrical engineering and gave me more confidence for my personal projects. I improved my skills with layout, distribution, debugging, prototyping, simulation in spice, practice simulating in SIwave. I also got to look at other product designs and debug old designs with my mentor, which I found to be very cool and interesting when viewing the work of other engineers because you can tell that someone thinks differently than you. I was also able to provide solutions to times I was called on to debug which was really cool because I was just an intern and actually being helpful. I also was super happy to make friends with the other interns and we had a good time working together. I also worked on professional skills, particularly a presentation that I did on my work at the end of the summer where everyone in Thorlabs was invited. I was nervous because the CTO was there but I practiced a bunch and did well on the presentation, partially due to the work I had put in throughout the summer. Thank you Thorlabs!




**Back to main page:** [Main](https://wmayfield.github.io/)
