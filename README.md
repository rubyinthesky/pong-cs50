

Hi! So this is my solution to assignment 0: “Pong, The AI Update” on cs50 course Introduction to game development.

I deleted the key detection of player2 in main.lua and created a function in Paddle.lua called updateAI which receives: dt, ball.y and ball.dy. What the function does is basically the same as the update function, only that it updates self.y with the velocity and y position of the ball object so it will be updating itself frame by frame following the ball always.
