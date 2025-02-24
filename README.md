Download Link : https://programming.engineering/product/the-objective-of-this-assignment-is-to-get-you-to-be-comfortable-coding/

# CS250-The-objective-of-this-assignment-is-to-get-you-to-be-comfortable-coding
The objective of this assignment is to get you to be comfortable coding
VERSION 1.0

The objective of this assignment is to get you to be comfortable coding in a networked setting where you need to manage the underlying communications between nodes. All communications will be based on TCP and you will be using the sockets to implement this assignment. The programming assignment should be implemented in Java. You are required to work alone on this assignment. The assignment accounts for 7.5% towards your cumulative course grade.

This assignment may be modified to clarify any questions (and the version number incremented), but the crux of the assignment and the distribution of points will not change. If there are any changes to the assignment, all changes will be documented in the “Change History” section of this assignment.

1 Description of Task

As part of this assignment, you will be responsible for designing programs that facilitate communications in a networked setting. Three machines will be involved during program execution. The programming assignment should be developed in Java version 8, and your classes must reside in the package “cs250.hw3”.

You will be designing two separate programs that implement functionality relating to key roles in the system: a server and a client.

Your server program will be provided with 3 arguments at the command line. The first argument specifies the port number that your server “listens” to. The second argument specifies the seed (an integer number) that is used to initialize the Server’s random number generator. The final argument, number-Of-Messages, specifies the number of messages that will be sent by each client that is connected to the server.

Server Command line compilation:

javac cs250/hw3/TCPServer.java

Server Command line execution format:

java cs250.hw3.TCPServer <port-number> <seed> <number-Of-Messages>

Server Command line execution example:

java cs250.hw3.TCPServer 1345 42 4

Your client program will be provided with 2 arguments at the command line. The two arguments specify the hostname and port-number where the Server is listening to for communications.
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	

	

CS250: FOUNDATIONS OF COMPUTER SYSTEMS
	

PROFESSOR: Shrideep Pallickara
	

Department of Computer Science
	
	

Colorado State University
	
		
	

Finished sending messages to server.
	
	

Total messages sent: 30
	
	

Sum of messages sent: -6382135587
	
	

Starting to listen for messages from server…
	
	

Finished listening for messages from server.
	
	

Total messages received: 30
	
	

Sum of messages received: -2496366311
	

Deductions:

1 points each for not following the prescribed argument specification.

3 points for hardcoding any values in the system; everything should be argument driven including the random number generator.

You are required to work alone on this assignment.

4 Late Policy

Please check the class policy on submitting late assignments. You are allowed to submit assignments up to 24 hours late with a 7.5% deduction, or up to 48 hours late with a 15% deduction.

5 Version Change History

This section will reflect the change history for the assignment (if needed) after the first public release of the assignment. It will list the version number, the date it was released, and the changes that were made to the preceding version. Any changes to the first public release are made to clarify the assignment; the spirit or the crux of the assignment will not change.

Page 8 of 8
