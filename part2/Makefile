CC = g++
OBJS = wec_pt_2.cpp
CFLAGS = -Wall -O2 -std=c++11
BIN = wec21

all: $(BIN)

wec21: $(OBJS)
	$(CC) $(CFLAGS) $(OBJS) -o $(BIN)

wec21_timed: $(OBJS)
	$(CC) $(CFLAGS) -D TIMER $(OBJS) -o $(BIN)

timer: wec21_timed

clean:
	$(RM) -r wec21 wec21_timed *.o *.dSYM
