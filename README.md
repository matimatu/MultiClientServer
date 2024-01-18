This simple project is for educational purposes.

PROGRAM BEHAVIOR:
The server implements threads and for each client that connects it opens a stream channel in which the client sends a string and the server simply responds with the same string.
This channel closes when the client sends an "END" string.

TO EXECUTE:
-Run MultiServer first on your machine
-Run MultiClient on your machine on other cmd
-Run as much MultiClient as you want in others cmd
That's it!


If you want to make communicate the client and the server in different machines,
just change the field "nomeServer" to the local IP address of the server.