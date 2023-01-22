#Virtual_Robot

##Project Description

  Given the basic structure and code for a 3D virtual robot, we built a learning strategy that would enable the robot to compete in a tournament against opponents with a goal to collect the most balls from the play area and return to home base. Our strategy focused on our robot, named "MTHC", to collect three balls from the arena or the opponent's home base and return to its home base. This way the robot would not slow down too much due to the weight of the balls. We trained MTHC on this strategy using reinforcement learning. MTHC was given more positive rewards whenever the agent has number of targets closer to 3. This makes it so during our training, the agent collects the balls as fast as it could considering that the agent will keep getting higher rewards the faster it collects. MTHC was given negative rewards whenever the agent whever it hits the walls or has more than 3 balls and has not returned to base. The training was done on multiple environments for 12+ hours. The appearance of the robot was insipred by the Pixar character, Wall-E, and was desgined and implemented using Unity prefab.

##Installation

- Navigate to the directory where you want this project to be cloned.
- Clone this project by running git clone *link* in your terminal.
- Navigate to this project in the terminal by running *command*.
- Open this project in Unity Hub.

##Demonstration
- Open the project in Unity through Unity Hub
- Click the play button on top to see the robot in action against "TA_Example_1" (a robot built by the Teaching Assistants of the course, with minimal training")
- To watch the robot compete against itself, navigate to...
- To inspect the implementation of the strategy, navigate to...

##Credits

  This was a team project built with 3 other students as part of the final lab project for a course. We received help and feedback from the Teaching Assistants of the course as well during this project. 
