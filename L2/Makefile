swap.o: swap.c
	gcc -c swap.c -o swap.o
main.o: main.c
	gcc -c main.c -o main.o 
p: main.o swap.o 
	gcc -o p main.o swap.o
clean: rm main.o swap.o p

