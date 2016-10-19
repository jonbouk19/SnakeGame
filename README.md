# SnakeGame
The traditional snake game is implemented instead with a herd of sheep who eat the hay. For every piece of hay the flock gathers, one more sheep is added to the herd. 

The Processing plugin in the Eclipse IDE was used to make the applet, and the language used was Java. Processing is useful in the area of graphics. The basic concept is that the setup method is called once and then the draw method is called at the frequency of the frame rate.

The user can control the speed difficulty by pressing 1, 2, or 3 for a frame rate of 5, 30, or 50 respectively.

Also, the user may pause the game using the spacebar. The arrow keys are used to move up, down, left, or right.

At the start of the game, the setup method is called. It creates a new sheep (by default with coordinates at the center of the gameboard). It also creates a hay object and scoreboard object. The image files for a sheep and hay are loaded, and the difficulty level is set to moderate; a frame rate of 30 times per second.

The draw method is called the number of times as the frame rate per second. So, for the beginner leve, the draw method would be called 5 times per second. The first step is to draw the white gameboard, then the scoreboard, hay object placed in a random location. Finally, the move method of the herd sheep is called before the draw method of the herd is called. This is necessary to determine whether the herd has either collided with the wall or with itself.

In the case that the herd of sheep dies, a new herd of sheep is created at the center of the gameboard.
