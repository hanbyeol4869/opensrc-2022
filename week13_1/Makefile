CC = gcc
CFLAGS = -c -o3 -Wall
LDFLAGS = 
all: hello myprog
hello: hello.o
	$(CC) $< -o $@
hello.o: hello.c
	$(CC) $(CFLAGS) $< -o $@
myprog: myprog.o
	$(CC) $(LDFLAGS) $< -o $@
myprog.o: myprog.c
	$(CC) $(CFLAGS) $< -o $@
clean:
	rm -rf *.o hello myprog
