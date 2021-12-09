# CS 3530 : Computer Networks - I

## Socket Programming Assignment
## Multi-Media Group Chat
======================================

Commands to run the program :

* ```$ python3 server.py``` 
* ```$ python3 client.py```

On running "client.py" file the user is prompted to : 

- *Enter the IP address :*
- *Enter the port Number :*
- *Please enter your name :* 

On choosing the suitable HOST and PORT, the client is connected to the server and displays :
- *connected to server!*
- *"client_name" has joined the chat!*

### BASE LINE IMPLEMENTATION
#### Normal Text Chat

- To text in the group chat with other clients type the message and then click enter. 


### ENHANCED VERSION

#### OS Commands
- ``` !cmd "Linux Commands"``` command is used to execute the OS commands. 
- It supports all the basic linux commands like *ls, date, time.*
- The commands ```sudo, rm, rf``` are not supported and are considered as error commands.
- For example, ```!cmd ls``` command outputs the list of all the files in the present directory.


### Flie Transfer
- ```!send "filename"``` command is used to send a file from the client to the server.
- ```!req "filename"``` command is used to request a file from the server to the client.
- It supports all file extensions like ```.txt, .pdf, .mp3, .mp4, .jpeg, .png, .py....```

### Bank Authentication
- ```!get "QR Code"``` pops out the unique generated QR Code for a given URL.

### Pre-installations to run the files
- Missing packages are installed using subprocessed module in python automatically.
