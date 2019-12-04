CC=gcc
CFLAGS=-Wall -Wextra -Werror

iutsh: main.o file.o ligne_commande.o
	$(CC) $^ -o $@

main.o: main.c file.h

file.o: file.c

