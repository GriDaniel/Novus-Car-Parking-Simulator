# About

Here lies the isolated Pygame code for the parking simulation of the Novus Car project which took place in November, 2023; developed by Daniel Oliveira.

# How it works?

The program initializes by calculating the viewport size of the user's screen to generate a full-screen container colored black, which serves as the animation canvas. After an on-screen message, a 2D abrirtary parking lot is generated. Upon every generation, there is a fixed number of total parking lots, however, which lots are occupied is always randomized in both location and quantity. Fixed objects which are made invisible are placed at the ends of the parking lot rows/coloumns and have an assosciated x and y coordinate. In fact, every object drawn on the screen has an assosciated x and y coordinate and this serves as the basis for directing the car's movement. As the car begins to move, its x and y position is compared with that of the invisible objects. Matching x and y coordinates between the objects and vehicle indicate its time for the vehicle to shift its direction. Ultimately, the vehicle safely traverses through the entire parking lot. 

# Next Step(s)

The current program sets the foundational algorithim and thought process needed to achieve safe parking for autonomous vehicles. By previously implementng coordinate tracking, the future step would be to set up a data structure to store all the coordinates of empty lots and develop and algorithim to determine the lot whose coordinates are closest to the vehicle's starting position and use these coordinates to safely guide the car to it. 

# How to Run

1. Download the file onto your computer
2. Install pygame through the command line/terminal: pip install pygame
3. Open the file in your code editor
4. Run


# The Whole Picture

This parking simulator is only a small part of Novus Car, to view the project in its entirety and the rest of the Novus Car team, please visit https://github.com/Swwwerve/NovusCar
