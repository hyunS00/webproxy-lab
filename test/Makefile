# Makefile for test

# Compiler and flags
CC = gcc
CFLAGS = -O2 -Wall -I .
LIB = -lpthread

# Targets
all: badcnt

badcnt: badcnt.o csapp.o
	$(CC) $(CFLAGS) -o badcnt badcnt.c csapp.o $(LIB)

csapp.o: csapp.c
	$(CC) $(CFLAGS) -c csapp.c

clean:
	rm -f *.o badcnt
