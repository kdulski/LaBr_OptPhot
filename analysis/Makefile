CC = g++

CFLAGS = -Wall `root-config --cflags`

CLIBS = `root-config --glibs` `root-config --cflags`

all: LaBrAna

LaBrAna: LaBrAna.C Histo_Collection.h
	$(CC) LaBrAna.C -o LaBrAna.exe $(CLIBS) -std=c++17

clean:
	rm -rf *o

