# Written prompt for Project 2

## Summarize the project and what problem it was solving.
For this project, I was to create software for a theoretical thermometer. The software is designed to run on a CC3220S launchpad. The requirements for this thermometer are to allow the user to set a desired temperature, and to have the user turn the heat "on" or "off". If the user pushes a GPIO button, the heat is set to on, incrementing the heat by 1 degree every second. When the heat is "ON", a red LED glows on the thermometer (Or in our case, the launchpad). Once the temperature reaches the user's desired temperature, the heat stops incrementing, and the LED is turned off. 

## What did you do particularly well?
I believe I did well in developing callback functions depending on which button was pressed, and utilizing a task scheduler to execute commands at various intervals of time. 

## Where could you improve?
I know I can improve in buiding more efficient task schedulers, and gain more confidnece in building state machines in tandem with task schedulers to produce code that seamlessly transitions from function to function depending on user input. 

## What tools and/or resources are you adding to your support network?
While I have had experience with programming in C++, this was my first ttime developing in C. I found the website https://www.codeinsideout.com/ to be an excellent resource in helping me learn how to implement various algorithms in C. 

## What skills from this project will be particularly transferable to other projects and/or course work?
Prior to this class, I was not familiar with the utilization of task schedulers and state machines. Even working outside of embedded systems, I know that I can use such agorithms to produce more efficient and creative code in all kinds of applications. 

## How did you make this project maintainable, readable, and adaptable?
I made sure to have an easy-to-follow variable naming scheme, and followed proper indenting and line spacing best practices to ensure my code was clean and readable. Additionally, I provided detailed comments on blocks and lines of code that were the most critical to the code's functionality. 
