# CS350

#Summarize the project and what problem it was solving.
The final project was to develop a smart thermostat protype using the TI board for SysTec. The prototype used the TMP006 temperature sensor to read the room temperature (via I2C), the LEDs had to indicate the output to the thermostat where LED on = heat on (via GPIO), two buttons had to increase and decrease the set temperature (via GPIO interrupt), and the UART had to simulate the data being sent to the server.

#What did you do particularly well?
I felt like I figured out the Task Schedular pretty quickly. After looking at ZyBooks, it made alot more sense. Then, after piecing the past milestones together, everything fit into place and made even more sense to me.

#Where could you improve?
My biggest issue through out this course was understanding how everything functioned, such as the timers, GPIO, and UARTs. I just knew what functions to call for and from what previous milestones, but I had trouble understanding exactly how they worked and how they would all work together. It wasn't until after I finished the final project where it all began to click for me that I got a better understanding of the material.

#What tools and/or resources are you adding to your support network?
This was my first time ever working with an embedded system. I really enjoyed working with the Code Composer IDE, as someone who has experience with Eclipse, it was super easy to learn. Then, the biggest resource that helped me was our ZyBooks book and TI pdfs.

#What skills from this project will be particularly transferable to other projects and/or course work?
I believe just doing proper research on how to correctly build certain models, such as the state machines and task schedulars can help me go a long way especially for other courses. Also, looking at example codes and figuring out how I can implement them into my program is also very beneficial.

#How did you make this project maintainable, readable, and adaptable?
For the Thermostat program, I had already used and repurposed a lot of recycled code from previous milestones. So, this program is very adaptable. Also, I made sure to comment a lot of key lines to tell readers what they are used for. Lastly, I tried to keep the code as simple as possible, so it could be easily read and maintained.
