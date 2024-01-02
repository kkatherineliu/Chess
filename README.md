# Chess
A chess program with options to play against others online in real-time or against an AI chess bot.
There are multiple chess game-play options, each equipped with a display of all moves and a chat window.
To start the program, run the [Server](Server.java) file and then run [HomeFrame](HomeFrame.java) for each person who wants to play.

Previously, this program worked across different devices (you could play with friends by running [HomeFrame](HomeFrame.java) on each individual's laptop). However, the free trial for our server has finished. 
For future reference, to run this code on an actual server, head to [Constants](Constants.java) and change the HOST and PORT variables accordingly.

## Public Rooms
You may choose to play a random opponent in a public room (where you will have to wait for another opponent to connect to matchmaking mode). 
You can also choose to simply spectate a public room so you can see the gameplay and chat but you will be unable to influence the moves.

## Private Rooms
When you create a private room, you will be given a code. This is the code that your friends can use to join the same room.

## Human vs Computer
Lastly, you can play against the computer which generates moves based on a basic chess algorithm. 
That being said, if it's too easy, you can always choose the medium difficulty instead.

# Have fun!

Here's a quick demo of the program and what it might be like to play against your friend in a private room or against the computer

https://github.com/kkatherineliu/Chess/assets/80860203/00acb4df-c4e3-4aca-89b1-e41f09844b10

