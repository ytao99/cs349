To run:
java -jar Breakout.jar [frame-rate] [speed]
Or without arguments, use default fps 30, speed 2.

Command-line Parameters:
1. "frame-rate" : support 25-50, outside this range, take default 30
2. "speed" of the ball: 1=slow, 2=med, 3=high, not 1/2/3, take default 2


Additional Features:
1. Bricks in different colors have different value / score.
Red - 5, Orange - 4, Yellow - 3, Green - 2, Blue - 1, Gray - 0.

2. Special block that makes the paddle wider for a short period of time. 
There will be 5 gray bricks (one in each row). They are generated randomly. Their values are 0, but breaking them will make the paddle 3 times wider for 5 seconds.


Key Command:
'p' - pause the game, ball stops moving
'r' - resume the game, ball continues to move
'q' - quit the game

Paddle Movement:
press '->' (left arrow) - paddle move left by 10
press '<-' (right arrow) - paddle move right by 10
mouse drag - move change in mouse x position
Note: if paddle reaches the edge, it can not move further.


Window Size for the game:
Preferred: 700 X 700
Min: 400 X 400
Max: 900 X 900

Resize Behaviour:
The ball, paddle and bricks will be repositioned using scale (newWidth/oldWidth, newHeight/oldHeight). Their sizes will change as well.


End of game:
1. Ball touches the bottom of the screen: will show "Game Over! Your score is X."
2. Broke all bricks: will show "Congratulations! You broke all bricks!"


Citation:
- The splash screen game introduction cited some words from https://en.wikipedia.org/wiki/Breakout_(video_game).
