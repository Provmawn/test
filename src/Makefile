# -*- Makefile -*- 
all: grep

grep: grep.c ../include/*.h
	gcc -g -w -I../include/ -o grep grep.c

clean:
	rm grep
