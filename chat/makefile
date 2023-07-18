CC=gcc
ARGS=-pthread -lncurses 
CLEAN=rm -f

all: client server

client: client.c gui.h
	$(CC) -o client client.c gui.c $(ARGS) 

server: server.c
	$(CC) -o server server.c $(ARGS) 
	
clean:
	$(CLEAN) client server
