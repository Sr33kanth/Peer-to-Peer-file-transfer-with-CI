

Changes I have made: (10/28/2015)

TCPServer.py 

This is the central server.
Accepts multiple requests in parallel threads
Maintains a list of peers(only one list as of now)
Right now, simply exchanges messages between client, no file transfer

TCPClient.py

These are the peers. We have to duplicate this file across client machines for the demo
A very minimal client application that talks to the server requesting for a particular RFC

Lists.py

This maintains all the lists. Right now only one
There are two classes - one for Node and the other for List of these nodes. 
We may need actual linked list and not the normal list. That's why these files
