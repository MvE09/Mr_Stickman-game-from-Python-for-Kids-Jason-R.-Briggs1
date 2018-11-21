# Mr_Stickman-game-from-Python-for-Kids-Jason-R.-Briggs1
I recently started learning Python, I encountered a problem in my code that I wrote following a book. 
The book is called Python for Kids and is written by Jason R. Briggs. 
There is a full written example online but I can't manage to find the problem that im having. 
I will add an README file for more details. Hopefully someone is able to explain the problem to me.

--------------------------------THE_ERROR_MESSAGE----------------------------
Traceback (most recent call last):
  File "/Users/michelvaneijk/Documents/Python_Boek_Programmeren_met_Python/Mr_Stickman_game/Mr_Stickman.py", line 313, in <module>
    g.hoofdlus()
  File "/Users/michelvaneijk/Documents/Python_Boek_Programmeren_met_Python/Mr_Stickman_game/Mr_Stickman.py", line 52, in hoofdlus
    sprite.move()
  File "/Users/michelvaneijk/Documents/Python_Boek_Programmeren_met_Python/Mr_Stickman_game/Mr_Stickman.py", line 256, in move
    if left and self.x < 0 and collided_left(co, sprite_co):
NameError: name 'collided_left' is not defined
-------------------------------------------------------------------------------
As you can see it is telling me there are problems with the loop of the game, the move function of the sprite \
and the collided left function of the sprite. 

-------------------------------THE_CODE_ONLINE----------------------------------
This is the webpage where to find the code online. Its kind of confusing because the code that is online \
is slightly different then what was noted in the book. That is problaby because I read the dutch translation of the book.

https://doc.lagout.org/programmation/python/Python%20for%20Kids_%20A%20Playful%20Introduction%20to%20Programming%20[Briggs%202012-12-22].pdf

---------------------------------------------------------------------------------


-------------------------------THE_CODE_I_FOUND_ONLINE_THAT_DOES_WORK------------
I found some code online that does work. It's from the same book and looks exactly the same. I also compared \
this code to mine but still I havent found the mistake i made. The indentations are diffrent but that should be the problem \
here right? 

This code will be in the repository under the namen Found_Online.py
