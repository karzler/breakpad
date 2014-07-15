includes = -I. -I/home/karzler/google-breakpad/src
breakpadlib = /home/karzler/google-breakpad/src/client/linux/libbreakpad_client.a
link = -lpthread

CC = g++
CFLAGS = -I

hello:
	$(CC) $(includes) hello.cpp  -g $(breakpadlib) -o hello $(link)
