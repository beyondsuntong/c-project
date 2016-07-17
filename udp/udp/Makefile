#!/usr/bin/env 

#udp_server: udp_server.o
#	g++ -Wall -g -o udp_server udp_server.o
#
#udp_client: udp_client.o
#	g++ -Wall -g -o udp_client udp_client.o
#
#udp_server.o: udp_server.cpp
#	g++ -c udp_server.cpp
#
#udp_client.o: udp_client.cpp
#	g++ -c udp_client.cpp
PROGS =	udp_client	udp_server

all: $(PROGS) udp_client.o udp_server.o

udp_client: udp_client.o
	g++ -Wall -g -o udp_client udp_client.o

udp_server:	udp_server.o
	g++ -Wall -g -o udp_server udp_server.o

	
clean:
	rm -rf *.o *.exe


