CC = gcc

all: kaprekarDemo kaprekarTest

kaprekarDemo: kaprekarUtils.o kaprekarDemo.c
	$(CC) -lm kaprekarDemo.c kaprekarUtils.o -o kaprekarDemo

kaprekarTest: kaprekarUtils.o kaprekarTest.c
	$(CC) -lm kaprekarTest.c kaprekarUtils.o -o kaprekarTest

kaprekarUtils.o: kaprekarUtils.c kaprekarUtils.h
	$(CC) -c -lm -o kaprekarUtils.o kaprekarUtils.c

clean:
	rm -f *.o *~ kaprekarDemo kaprekarTest
