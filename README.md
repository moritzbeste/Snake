This is an implementation of the iconic snake game using java.
You can change the size of the board in the main file by changing the values of x and y.
You can play the game yourself instead of having the ai play by changing the boolean value in the game.play() parameters to false.

The AI works by finding a unique hamilton cycle in the game grid and loosely following it to ensure that there is always enough space for the snake to escape its own body. 
The AI is heavily inspired by John Tapsel's blog where he also created a snake AI. His series of blog posts about the topic is linked here: https://johnflux.com/category/nokia-6110-snake-project/
