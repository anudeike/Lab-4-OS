# lab-4/Makefile
# Ikechukwu Anude

func-ptr: func-ptr.o process.o util.o
	gcc func-ptr.o process.o util.o -o func-ptr

func-ptr.o: func-ptr.c
	gcc -c func-ptr.c

process.o: process.c process.h
	gcc -c process.c

util.o: util.c util.h
	gcc -c util.c

clean:
	*.o