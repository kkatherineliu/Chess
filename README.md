# Chess
A chess program with options to play against others online in real-time or against an AI chess bot.
There are multiple chess game-play options, each equipped with a display of all moves and a chat window.
To start the program, run the [Server](Chess/Server.java) file and then run [HomeFrame](Chess/HomeFrame.java) for each person who wants to play.

Previously, this program worked across different laptops. However, the free trial for our server has finished. 
If you want to re-enable this function, head to [Constants](Chess/Constants.java) and change the HOST and PORT variables accordingly.

## Public Rooms
You may choose to play a random opponent in a public room (where you will have to wait for another opponent to connect to matchmaking mode). 
You can also choose to simply spectate a public room so you can see the gameplay and chat but you will be unable to influence the moves.

## Private Rooms
When you create a private room, you will be given a code. This is the code that your friends can use to join the same room.

## Human vs Computer
Lastly, you can play against the computer which generates moves based on a basic chess algorithm. 
That being said, if its too easy, you can always choose the medium difficulty instead.

# Have fun!
