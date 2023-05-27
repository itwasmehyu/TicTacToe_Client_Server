# Client_Server_TicTacToe
In this code, you I implemeneted  the famous Tic-Tac-Toe game using Java Socket API. I implemented both the server and client sides of the program. The server side maintains and keep track of the game, while the client side is used for sending the moves to the server and gathering information about the game from the server. Threads are used to accept multiple connections (players) on the server side. You must implement your program using either the Java Socket API.
# How to run
  -Open a terminal or command prompt.  
  -Compile the Java source files by executing the command javac *.java.  
  -Start the TicTacToe server by running the command java TicTacToeServer <portnumber>, where <portnumber> is the desired port number for the server. 
  -Open two new terminals or command prompts.  
  -In each terminal, run the command java TicTacToeClient <hostname> <portnumber>, replacing <hostname> with the hostname or IP address of the machine running the server, and <portnumber> with the same port number used for the server.
