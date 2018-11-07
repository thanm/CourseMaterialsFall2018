# Challenge problem: Pong Time Warp

In the Pong game, each time the ball bounces off a player's paddle it is supposed to speed up a little bit, which means that after a couple of bounces it can be moving at a very fast clip.

Add a new feature to the game called "Time Warp": if a player hits the space bar at some point during the point, time will "slow down" (the ball's speed will drop to a crawl) to make it easier for the player to insure it hits the paddle. Once the ball hits the paddle, time speeds up again and the ball resumes its previous pace.

Each player can only use the space-bar "time warp" feature once during a point (pressing the space bar after that will have no effect).

Hints:

- use a variable to keep track of whether a given player has used the time warp feature during a point.

