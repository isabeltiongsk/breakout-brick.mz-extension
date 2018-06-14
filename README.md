# About this extension

This is an assignment project for Coventry University Open Source Development Course<br>
by Isabel Tiong. <br>
Mini breakout brick game on firefox pop up window<br>

### Screenshot
![alt text](https://github.com/isabeltiongsk/breakout-brick.mz-extension/blob/master/img/demo.JPG) <br>
You can try the [Demo](http://htmlpreview.github.io/?https://github.com/isabeltiongsk/breakout-brick.mz-extension/blob/master/index.html) here

## About the game
Breakout is an arcade game developed and published by Atari, Inc., released on May 13, 1976. <br>
It was conceptualized by Nolan Bushnell and Steve Bristow, influenced by the 1972 Atari arcade game Pong, and built by Steve Wozniak aided by Steve Jobs. 
<br>
### How to play
In the game, a layer of bricks lines the top third of the screen. <br>
A ball travels across the screen, bouncing off the top and side walls of the screen.<br>
When a brick is hit, the ball bounces away and the brick is destroyed. <br>
The player loses a turn when the ball touches the bottom of the screen. <br>
To prevent this from happening, the player has a movable paddle to bounce the ball upward, keeping it in play.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           <br>
### How to install extension to play
* Download all codes from master branch
* Extract files to local if you downloaded the zip file
* Open firefox browser
* Go to **'about:debugging'**
* Press the **'Load Temporary Add-on'** button
* Select the **'manifest.json'** file
* Game icon will appeared on the right side bar.
* Press and enjoy your game!

## Code References

The source code for this game was referred from the Mozilla Game Tutorial [here](https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript)<br>
<br>
But still, minor changes are made to the code
* **Brick and ball colour** are changed.
* **Ball speed** has decreased a little.
* **Frame size** has decreased for the firefox popup window.
* Visible `Tab` key
* **Drag and Drop** file read.
