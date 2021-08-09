Welcome to Merlin the Wizard and the Missing Stone!


The story should drive you along fairly well on it's own.


I will make a note:
sometimes when the Computer Serpent is creating his battle ships, he gets stuck in an infinite loop.
I am still debugging, if this happens chances are very low it will happen again if you restart and try again.
It has to do with the srand() seed I am using I suppose becuase sometimes it happens while others it does not happen.

I hope you enjoy playing this game as much as I enjoyed writing it! Be sure to try all the different paths!

-Jordan Babb


@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
Resubmission notes
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

I just realized there was a BIG bug in my code. Whenever the Serpent(bot) would guess a coordinate of where your battleship could be, it would count it's previous guesses(misses) as hits!!!!!! AH! I fixed the code easily and have it attached to this email along with another executable application. Thanks!