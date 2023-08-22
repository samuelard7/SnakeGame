# SnakeGame

INSIDE main.py
1. Setting up the screen title and importing all the other modules scoreboard, food, snake.
2. Creating the objects for the import class.
3. As the turtle size is 20px by default so considering that:
   (i) Moving the snake inside while loop
   (ii) We will direct the snake head and check for possible collision
   (iii) Three types of collision
   - Collision with food.
   - Collision with tail/ body.
   - Collision with the wall.
  
-------------------------------------------------------------------------------------------
Inheriting the turtle library in food and scoreboard.

INSIDE food.py
1. Shaping the food.
2. Using the random module.
3. Creating a method which refreshes the food and put it randomly on the screen.


INSIDE snake.py
1. It is responsible for Event Listener.
2. Creating the method to create the snake adding and extending it.
3. Keyboard's Method for up, down, left, right.


INSIDE scoreboard.py
1. Creating the Score text on the screen.
2. By using the method update_scoreboard.
3. Creating the method to check whether the user collided.
4. Creating the method to increase the score when the snake eats the food.

------------------------------------------------------------------------------------------
