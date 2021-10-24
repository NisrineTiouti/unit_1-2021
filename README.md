# Unit 1: A classic game 
![](game.gif)

# Criteria A: Planning

## Problem definition

The owner of the local game shop is an enthusiast of classic computer games. He has been looking for a talented programmer that can help him revive his passion for text-based games. He has few requirements for this task:

1. The game has to be entirely text-based.
2. The game must record the time played.
3. The game must record the player name and score.

Apart for this requirements, the owner is open to any type of game, topic or genre.

## Proposed Solution
**Design Statement:**
I will design and make a a classic text-based computer game for a client who is an owner of the local game shop. The game will be a dragon collecting game and is constructed using the software Python. It will take 3 weeks to make and will be evaluated according to the criteria shown below .

**Justification of tools used:**
1. Python is a very popular language nowadays. Google search trends for 2019 place Python as the second most sought for language on the net.
2. The Python code is really easy to write because it is very similar to the English language. In fact, that was the whole idea behind the project. The developers wanted to make a program that would be easy to understand. The code uses English keywords instead of punctuations, making it immensely easy to use even for beginners.
3.  by March 2019 there have been 23,122,064 hits for Python download for Windows users. This translates into 59.37% of hits established for the period. And since i have a HP laptop, Python is the right choice for me to develop this game.

## Success Criteria
1. The game has to be entirely text-based.
2. The game must record the time played.
3. The game must record the player name and score.
4. The game must output a table with the score, time played and username.
5. The game must give the user time to rest if needed.
6. The game will be developed in english.
# Criteria B: Design

## System Diagram
![system diagram(game)](https://user-images.githubusercontent.com/89052189/134761943-484a6299-9d41-4222-848a-778045663779.png)

**fig.1**: System Diagram for the proposed solution. In this this diagram you''ll see a representation of where the game is running, the user name and score is the data stored in the game. Pycharm is the sfotware where the game is being developed. Windows is the operating system for that software and the computer is the electronic device and home of them all. You can also see the inputs that are being inputed by the keyboard and outputed on the screen in Pycharm's terminal.
## personal reasons:
I chose the game theme to be a dragon collecting game, because i think that dragons are amazing creatures. They are indeed scary, but they are very powerful and strong. We always see them as frightening beasts but i think it is better to fratenize with them. I also chose this game to be a bit of a tricky one as you won't always gain a dragon in each door you choose, which can be projected in our daily life, that you should dream on but don't expect it will all come through, that each path in life doesn't necessarily end well so we have to choose carefully, choose a path where the price is something we are willing to pay.
## Flow Diagrams
<img src="https://user-images.githubusercontent.com/89052189/138575880-ff6c8dbc-f61f-4bc8-a4ae-a1cee05354c5.png"
     width = 50% height = 50%>\
 
  **fig2** : Main function of the game
    
<img src="https://user-images.githubusercontent.com/89052189/138575881-17b1bcd0-236a-4bee-97fe-fe9ff4f9979c.png"
     width = 50% height = 50%>\
    **fig3** : For loop within the main function that outputs the door choices.
     
<img src="https://user-images.githubusercontent.com/89052189/138575884-ebb007cc-32be-4374-a0e2-b22fb8fead8d.png"
     width = 80% height = 80%>\
     **fig4**: While loop within the main function that checks the player's door choice, in which the player can collect a dragon and points if its the right choice or get damaged if it's the wrong choice. 
     - *grotto(), hollow()* are room functions that tell the player which dragon they gained in that room and how many points were added to his score 
     - *damage()* is a function with a level of damage argument, if the damage is at level 1 or 2 the player rests for 10 seconds and then continues the game, if its high then its Game over.

## Caesar Cypher
**fig5**

<img src="https://user-images.githubusercontent.com/89052189/136376240-a140e283-74ae-4d46-ab17-ea6cb0dc7256.png"
     width= 40% height=40%>

The databse in the game has to be protected so that personal data is not exposed. To solve this requirement I am using the Caesar Cypher. **Fig 5**

## Source Code:

   **HydraCollect**
![dragon logo](https://user-images.githubusercontent.com/89052189/138598932-02e6caa5-183f-4117-8f49-6f5c41ce9fbd.jpg)

   [Classic game.zip](https://github.com/NisrineTiouti/unit_1-2021/files/7404012/Classic.game.zip)

## Record of Tasks
| Task No | Planned Action                                                                               | Planned Outcome                                   | Time estimate | Target completion date | Criterion |
|---------|----------------------------------------------------------------------------------------------|---------------------------------------------------|---------------|------------------------|-----------|
| 1       | write design statement                                                                       | have design statement                             | 7min          | 22nd sep               | A         |
| 2       | write success criteria                                                                       | have success criteria(6)                          | 10 min        | 22nd sep               | A         |
| 3       | write justification tools                                                                    | have the tools justified                          | 30 min        | 22rd sep               | A         |
| 4       | create system diagram                                                                        | have a system diagram                             | 30 min        | 23rd sep               | B         |
| 5       | create a encryption function for the user data                                               | A function tested that uses caesar cypher         | 15 min        | 6th oct                | C         |
| 6       | Integrate the encryption with the database save/load function                                | The database is encrypted and can be read/written | 5 min         | 6th oct                | C         |
| 7       | write personal reasons for choosing the game's theme                                         | have the personal reasons statement               | 5 min         | 11th oct               | B         |
| 8       | Prepare an MVP for game                                                                      | Have an MVP that can be tested                    | 1h            | 14th oct               | B         |
| 9       | Record yourself demonstrating the MVP                                                        | Have the video and upload it on Managebac         | 5 min         | 14th oct               | B         |
| 10      | Create 3 flowcharts from the game                                                            | Have the 3 flowcharts                             | 45 min        | 24th oct               | B         |
| 11      | Create a table that contains username, score and timeplayed by importing the tabulate module | Have that table outputed at the end of the game   | 10 min        | 24th oct               | C         |
