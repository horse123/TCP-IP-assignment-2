# TCP-Project

Team Name: Horse

Name 1: Sim Wei Xiong  Student ID: 1131121826
Name 2: Wong Wei Ye    Student ID: 1131121730


************************************************************


Development of File Repository System using Client-Server TCP/IP
This system is interaction between user and server that used for user store file to the server and perform some common task to the files. 
User (Client) will connect with the file server using socket connection. 
Server able to handle multiple client connection requests.
Client can create new file and save into server.
Client can choose files to download from server.
For download is for Client could to request for files to be downloaded from the server.
Client can send file to the server, and server will automatically store the file in specific user’s directory.  
Client deleted files from server.
During data transmission, the program should be clear of any interruption. 


************************************************************


User manual:


1. Compile client.c and server.c (gcc filename.c -o filename)

2. Run both files on different terminal/pc (server.c must be run before client.c)



For example:

Terminal 1:
./server 2000


Terminal 2:
 ./client 127.0.0.1 2000
 
 *port number must be same and can't use the port below 1024*


Group Members Task:
Sim Wei Xiong: Research information about this system, write coding and README File.
Wong Wei Ye  : Research, coding and testing this system finally uploaded document to Github.
