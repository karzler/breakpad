includes=-I. -I/home/karzler/google-breakpad-read-only/src
breakpadlib=/home/karzler/google-breakpad-read-only/src/client/linux/libbreakpad_client.a
link=-lpthread


CC=g++
CFLAGS=-I.

helloWorld:
	$(CC) $(includes) helloWorld.cpp  -g $(breakpadlib) -o helloWorld $(link)
	
