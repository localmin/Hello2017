TARGET = test

all: ${TARGET}

test: test.o print.o
	gcc -Wall -O2 -o test test.o print.o

.PHONY: clean
clean:
	rm -f test test.o print.o

.SUFFIXES: .c .o

.c.o: 
	gcc -c $< -Wall
