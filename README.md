# Scratch3_BalloonPop
Another Scratch 3 game
In this small game balloons move around at random. When clicked the ballooh hides, and 'pop' sound plays.

Start with a background:

![Background](https://github.com/zleap/Scratch3_BalloonPop/blob/master/backgroundBP.png) 


Now add a Balloon Sprite:


![enter image description here](https://github.com/zleap/Scratch3_BalloonPop/blob/master/baloonBP.png)


Now add the code to the Balloon Sprite:

![BalloonSprite](https://github.com/zleap/Scratch3_BalloonPop/blob/master/baloon1.png)

When the green flag is clicked, the balloon glides to a random position.  If it touches the edge of the stage then it will bounce off and head in another direction.

If the balloon is clicked then 'pop' is played and the sprite is hidden.

Now we have this working,  go ahead and add more balloons, copy the code over to each of the new balloons.

**EXTENSION KEEPING SCORE**

Can you add more blocks to keep score?  You will need a variable called **score**. 
If you need help with variables please take a look at my 
[timer project](https://github.com/zleap/scratch3_timer)

**ADD SCORE**

After creating a new variable, add the following code blocks to the project. 

![add score](https://github.com/zleap/Scratch3_BalloonPop/blob/master/add-score.png)

**What is next ?**
So far we show 3 balloons,  click on them,  after which they vanish.  Not much of a game here eh.  We should re-show the Balloons to keep the game going.  

Add the following to the **end** of the ***when this sprite is clicked*** block.  

![wait5andshow](https://github.com/zleap/Scratch3_BalloonPop/blob/master/wait5andshow.png)

Once tested to make sure it re-appears after 5 seconds (you can set this to what you want) use the backpack to copy the code to teh rest of the balloons.

**SPEED**
So far the game is preductable.  Firstly the balloons reappear after 5 seconds.  Lets try and fix this. 

Create a new variable called time and the following blocks.
![add-delay1](https://github.com/zleap/Scratch3_BalloonPop/blob/master/add-delays1.png)

now connect the second two blocks together 

![delay2](https://github.com/zleap/Scratch3_BalloonPop/blob/master/add-delay2.png)

You should end up with:-

![delayb4show](https://github.com/zleap/Scratch3_BalloonPop/blob/master/code-delays-b4-show.png)

For some reason, at the time of wrting when creating another variable it does not seem to show up in the variable list. 
I have added the code to:- 

 - Set My Variable to between 0 & 5 at random
 - Wait that amount  of time
 -    Show sprite

You need to select the variable you want to use from the drop down menu.  

**MAKING THE GAME A LITTLE MORE CHALLENGING**

So far you score points if you click on Balloon.  So lets add some code, so that if the Stage is clicked we lose points.
In the bottom right click on the current stage (backdrop) 

Add the following

![stageclick](https://github.com/zleap/Scratch3_BalloonPop/blob/master/baloonpop-stageclick.png)


**LICENSE AND COPYRIGHT**


By Paul Sutton 3/1/2019

e: zleap@zleap.net

web: http://www.zleap.net

![cc-logo](https://github.com/zleap/Scratch3_BalloonPop/blob/master/88x31.png)

<!--stackedit_data:
eyJoaXN0b3J5IjpbNDU5MTg4MDgzXX0=
-->