CC = gcc
CFLAGS = -Wall -Wextra -O2
TARGET = matrix7

all: $(TARGET)

$(TARGET): main.o
	$(CC) $(CFLAGS) -o $(TARGET) main.o
	rm -f main.o

main.o: main.c
	$(CC) $(CFLAGS) -c main.c

clean:
	rm -f $(TARGET)
