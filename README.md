# Multi-Client-Server-Chat
Group chat program where there is a single server and multiple clients. The server forwards a client's message to all the other clients.

<b>Platform:</b> Linux with GCC compiler

<b>Compiling:</b> gcc filename.c -pthread

<b>Running the server:</b> ./a.out portnumber

<b>Running the clients:</b> ./a.out username portnumber

<b>Stopping the clients and server:</b> CTRL-D

<b>Note:</b> The portnumber provided to clients should be same as the one given to server. Username is just an identity of yourself.
