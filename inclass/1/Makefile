CC=gcc
OBJ=src/sh.o
OUT=build/sh
DEBUGFLAGS=-g
SRC=src/sh.c
#IN = include
#CFLAGS=-I$(IN)
#DEPS=
#LIBS=-lm


#%.o: %.c $(DEPS)
     #%(CC) -c -o $@ $< $(CFLAGS)

build: $(OBJ)
	$(CC) -o $(OUT) $^ $(CFLAGS)

debugbuild: 
	$(CC) -o $(OUT) $(SRC) $(DEBUGFLAGS)

.PHONY: clean

clean:
	rm -f $(OUT)
	rm -f $(OBJ)

#https://www.cs.colby.edu/maxwell/courses/tutorials/maketutor/