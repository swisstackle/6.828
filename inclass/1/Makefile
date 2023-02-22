CC=gcc
OBJ=src/sh.o
OUT=build/sh
#IN = include
#CFLAGS=-I$(IN)
#DEPS=
#LIBS=-lm


#%.o: %.c $(DEPS)
     #%(CC) -c -o $@ $< $(CFLAGS)

build: $(OBJ)
	$(CC) -o $(OUT) $^ $(CFLAGS)

.PHONY: clean

clean:
	rm -f $(OUT)

#https://www.cs.colby.edu/maxwell/courses/tutorials/maketutor/