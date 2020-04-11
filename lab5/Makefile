all: build run clean

build:
	gcc -std=c89 -pedantic-errors main.c list.c -o programm

run: programm
	./programm
	
clean:
	rm -rf *.o programm
	
