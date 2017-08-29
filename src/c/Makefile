# Makefile

CC = gcc -m64
BIN = Tetris_Game
LDLIBS = -l pthread
SOURCE = Tetris_Game.c
CFLAGS = -std=gnu11 -s -Wall -Os

${BIN}: ${SOURCE}
	${CC} ${CFLAGS} ${LDLIBS} -o $@ $^

clean:
	rm -f ${BIN}
