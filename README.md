# Brick-Breaker-Game-JAVA

This is a simple implementation of the classic Brick Breaker game using Java and the Swing library. The game features a paddle, a ball, and bricks that the player must destroy by bouncing the ball off the paddle.

# How to Play
-Objective: Break all the bricks using the ball without letting the ball fall below the paddle.
-Controls:
Use the Left Arrow key to move the paddle left.
Use the Right Arrow key to move the paddle right.
Press Enter to restart the game if you win or lose.

# Game Features
-Bricks: The game starts with 21 bricks arranged in a 3x7 grid. Each brick is removed when hit by the ball.
-Score: The player earns 5 points for every brick destroyed.
-Winning Condition: The game is won when all bricks are destroyed.
-Losing Condition: The game is lost when the ball falls below the paddle.
-Restart: The game can be restarted by pressing Enter after a win or loss.

# Implementation Details
# MapGenerator Class
Responsible for generating and managing the bricks.
Bricks are arranged in a grid, with their sizes automatically calculated based on the grid dimensions.
The draw() method is used to render the bricks on the screen.
Bricks turn invisible once they are hit by the ball, which is managed by the setBrickValue() method.
# GamePlay Class
Manages the game loop, including the movement of the ball and paddle, collision detection, and score tracking.
Handles user input through the KeyListener interface.
Implements the main game mechanics, including ball and paddle movement, and ball-brick collisions.
The paint() method is responsible for rendering the game elements on the screen, including the background, paddle, ball, bricks, and score.
# Main Class
The entry point of the game.
Initializes the game window and adds the GamePlay component to the frame.

# Setup and Running the Game
-Prerequisites: Ensure that you have Java Development Kit (JDK) installed.
-Clone the Repository:
bash_code: git clone https://github.com/Warrior-Aviator/Brick-Breaker-Game-JAVA.git
-Compile and Run:
Navigate to the project directory.
-Compile the Java files:
bash_code: javac Main.java
-Run the game:
bash_code: java Main

# Customization
You can customize the brick layout by changing the rows and columns in the MapGenerator constructor.
Modify the colors, paddle speed, and ball speed by adjusting the values in the GamePlay class.
