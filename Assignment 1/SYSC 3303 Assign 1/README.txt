SYSC 3303 A - Assignment 1

Files:

1) Client.java: 
	-This contains the algorithm implementation for the client
	-It has a main() method that executes 11 request (5 read request, 5 write request and an invalid request)
	-Both the intermediate host and the server have to be running before this class can work

2) Server.java
	-This contains the implementation for the server algorithm
	-It has a main() method that runs on an infite loop as long as the request it is receiveing are valid.
	-It will wait to receive a packet before doing anything else
	-It must be running before the intermediate host sends it a request

3) Host.java
	-This class contains the implementation for the intermediate host algorithm
	-There is a main() method that contains an infinite loop to start the prgoram
	-It accepts packets from the client without changing the content of the packet before sending it to the server
	-It accepts a response from the server and sends it to the client without changing it.
	-This must be running before the client sends any packets
	-The Server must be running before this class works


Run Instruction:
1. Run Server.java
2. Run Host.java
3. Run Client.java
4. Check and compare logs