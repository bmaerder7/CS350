Summarize the project and what problem it was solving.

This project was setting up an embedded system through the Raspberry PI to control a thermostat. This system was controlled with three buttons. One button was used to cycles machine states: between off, heat, and cool. The other two buttons were used to set desired tempurature. The goal was to get the system to recognize the current state, compare the current ambient room temperature to the user set tempurature, and decide wether to heat or cool, or remain off. This was then displayed through the LEDs, flashing red for heat on, solid red for heat mode on(but not heating), flashing blue for cooling, solid blue for cool mode on(but not cooling), or all LEDS off if current state is off. 

What did you do particularly well?

I feel that I was able to use prior projects to aid me in the final very well in this final project. Before attempting any code aditing, I reviewed prior projects and analyzed their behavior in order to base my first steps off of proipr knowledge. I was able to look at the use of buttons, LEDs, and other functions to aid me in starting development of this system. This saved me a lot of time later on as I ran into less issues with logic flow and syntax as I recycled prior knowledge into this context of a thermostat application. 

Where could you improve?

I could have improved greatly on my state-machine diagram. I am not the best with draw.io and find it to be a little buggy and hard to get everything to look clean, however I could have cleaned this up much more and will invest in a software I am confortable with to do more professional diagrams. If I were to go back and redo this project, I would defenitely put more detail into the timing of these states and can learn from this project mocving foward. 

What tools and/or resources are you adding to your support network?

I added several tools and resources to my support network. I became more familiar with using Raspberry Pi hardware, GPIO connections, Python, breadboard schematics, serial communication concepts, and external hardware documentation. I also learned how useful it is to rely on lab guides, hardware pinout diagrams, library documentation, and troubleshooting resources when working with embedded systems.

What skills from this project will be particularly transferable to other projects and/or course work?

The skills from this project that will be most transferable to other projects are working with hardware peripherals, using state machines, and breaking a larger system into smaller functional parts. This project required me to use GPIO for buttons and LEDs, I2C for the temperature sensor, UART for serial communication, and an LCD display for user feedback. Those same ideas can apply to many other embedded systems projects because most hardware based programs need to read input, process conditions, and produce some kind of output.

How did you make this project maintainable, readable, and adaptable?

I made this project more maintainable, readable, and adaptable by keeping the code organized around specific functions and clear responsibilities. For example, the thermostat state logic, button actions, LED updates, LCD display updates, and UART output were handled in separate sections of the program. This made it easier to troubleshoot because I could focus on one part of the system at a time instead of searching through the whole program. I also used comments and descriptive function names so that the purpose of each section was easier to understand. The state machine made the code more adaptable because new states or actions could be added later without completely rewriting the program.
