# Nerve of Steel Game Code
### MGTC28 Weekly Exercise 6
This is a game program written in Python  

Please see below for a breakdown of the different files in this repository:

**timer.py** is a simple Python script allowing users to set timer duration. Upon timer expiry, the user will see the time-up meme.

**Pseudocode** is a document that allows us to see the logic and flow of our code before we begin programming. (Both Zaaraaa and Anaya have made commits to this file)
  
**GameCode** is the python code for the game Nerve of Steel. (Both Zaaraaa and Anaya have made commits to this file)
It is a party game where players sit in a circle and when the game begins:

1. The program displays "Players stand"
2. The program sleeps for a random time between 10 to 25 seconds. 
3. While the program is sleeping, players can sit down. 
4. Keep track of the people who sat down. Create a list, prompting the user to enter the names of those who sat.
5. When sleep is over, the program displays "Time's Up."
6. The last person to sit down wins. Players still standing are eliminated, and the winner is "the last name entered on the list."

![times-up!](https://media.makeameme.org/created/times-up-5923e0.jpg)\  
Please see the documentation for the library used:
- [time](https://docs.python.org/3/library/time.html)
- [pillow](https://pypi.org/project/Pillow/)
