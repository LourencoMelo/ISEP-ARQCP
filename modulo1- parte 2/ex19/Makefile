# A simple Makefile

ex19: find_word.o main.o

	gcc -g -Wall -lm find_word.o main.o -o ex19
find_word.o: find_word.c

	gcc -g -Wall -lm -c find_word.c -o find_word.o
main.o: main.c

	gcc -g -Wall -lm -c main.c -o main.o
clean:

	rm -f *.o ex19
run: ex19

	./ex19
