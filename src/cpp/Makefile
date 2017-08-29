# Makefile

CXX = g++ -m64
BIN = Tetris_Game
LDLIBS = -l pthread
SOURCE = Tetris_Game.cpp
CXXFLAGS = -std=gnu++1z -s -Wall -Os

${BIN}: ${SOURCE}
	${CXX} ${CXXFLAGS} ${LDLIBS} -o $@ $^

clean:
	rm -f ${BIN}
