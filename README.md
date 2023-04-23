# CS-350
# Summarize the project and what problem it was solving.
  My project was to create a prototype for a smart thermostat that the company Systec can use to build upon where they hope to break into the thermostat market. The goals for this company was for the prototype to support the peripherals used in the project, connect to the cloud via Wi-Fi, and for the chosen architecture to have enough Flash and RAM to support the code. I used a temperature sensor to read the room temperature, an LED to indicate the output to the thermostat where LED on = heat on, two buttons to increase and decrease the set temperature, and the UART to simulate the data being sent to the server.

# What did you do particularly well?
  After trial and error I feel like I did a good job with creating the task scheduler. Everything is laid out logically and each task has its on specific period which is incremented during each tick of the program by a universal period (100ms). once the tasks period is met then the program calls on the tasks function and resets the tasks period to zero. by doing this we can check for button presses every 200ms; check the temperature every 500ms; and update the LED and report to the server every second or 1000ms.

# Where could you improve?
  I feel like I could improve on using state machines in embedded systems. I feel like the logic I create for state machines arent the best or the most simple way of implementing the functionality. I do believe with more practice and better planning I can improve on this aspect and keep my code simple or easier to read for future maintenance.

# What tools and/or resources are you adding to your support network?
  I am adding code composer studio and the TIcc3220SF board as tools and resources to my support network so that I can grow on my foundation in embedded systems. I also would like to branch out and work with other boards so that I can get used to working with differnt features for different situations/tasks that I may be faced with. I have also added peers from this course and our discussions to my social network where we can support one another in situations that may challenge us.

# What skills from this project will be particularly transferable to other projects and/or course work?
  I think everything Ive learned in this project has helped me be a better programmer in different ways. One example is learning how to use state machines and task schedulers has helped me to think about ways to design and architect my code before I jump into writing it. The designing and pre-planning phase is very important and in many ways is essential. I dont think I would have been able to get through this project if I had not thought about it critically and used drawIo to work through the problem.

# How did you make this project maintainable, readable, and adaptable?
  I made this project maintainable, readable, and adaptable by keeping it simple and using clear/concise comments to describe the code. For the code to be maintainable it must also be readable where all the functionality of the code can be easily understood. To be adaptable the code must be able to change according to its needs and environment. The best way to make adaptable code is for it to be modularized which also helps with reuse.
