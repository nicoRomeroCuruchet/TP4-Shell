CC = gcc
CFLAGS = -Wall -Wextra -std=c11

TARGET = signals-game
SRC = signals-game.c

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm -f $(TARGET)
