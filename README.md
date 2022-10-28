# Client-Server
This Repo contains two programs, one for the Server side application, and one for the Client side application. The Server side application is a single threaded server that accepts requests from clients, and the Client side application is multithreaded capable of spawning numerous client sessions that connect to the server.

## What does this project do?
-	Establishes a connection to a server using Java’s Socket Server library when provided the appropriate server IP and Port number.
-	Takes user input and stores it in an ArrayList and returns it to the user as the response of the server.
-	Upon establishing connection, the user can enter a command that will display the Date and Time, Uptime, Memory use, Netstat, current Users, Running Processes, or Test Response of the server.

## What I learned from this project?
- 


## This project in action!
### Step 1: 
Is to run the server application first where it will start listening for client requests on the specified network address and port that is hardcoded.
(P.S. Avoid hard coding IP addresses and Port numbers in production environments because if you redeploy your app on a different host it will have issues)

<img width="485" alt="CleanShot 2022-10-28 at 13 14 52@2x" src="https://user-images.githubusercontent.com/47955658/198694824-c958435d-612f-40ee-a958-51b40e55d86a.png">
Upon running the server this is what you will see in your console
 <hr>

### Step 2:
Is to run the client side application and you will be prompted with 7 options.

<img width="485" alt="CleanShot 2022-10-28 at 13 18 38@2x" src="https://user-images.githubusercontent.com/47955658/198695664-0bc4c531-7dc1-480e-916e-dff4a380c8df.png">

 <hr>
 
 ### Step 3:
 
