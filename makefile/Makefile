test: test.o print.o
	gcc -Wall -O2 -o test test.o print.o

test.o: test.c
	gcc -c test.c

print.o: print.c
	gcc -c print.c

.PHONY: clean
clean:
	rm -f test test.o print.o
