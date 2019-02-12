
all: libevent-server libevent-client

libevent-server: libevent-server.o
	cc -o libevent-server libevent_server.o

libevent-client: libevent-client.o
	cc -o libevent-client libevent_client.o

libevent-server.o: libevent_server.c
	cc -c libevent_server.c

libevent-client.o: libevent_client.c
	cc -c libevent_client.c

clean: 
	rm *.o
	rm libevent-server
	rm libevent-client
