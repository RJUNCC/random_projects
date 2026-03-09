# Change these lines
TARGET = tree
SRC = tree.c

# Keep the rest the same
CC = cc
CFLAGS = -Wall -std=c99
LIBS = -lraylib -lGL -lm -lpthread -ldl -lrt -lX11

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(SRC) $(CFLAGS) $(LIBS) -o $(TARGET)

clean:
	rm -f $(TARGET)
