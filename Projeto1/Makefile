SOURCES = proj1.c
CC   = gcc
CFLAGS =-Wall -ansi -g -O3
TARGET = proj1

all: $(TARGET)

$(TARGET): $(SOURCES)
	$(CC) $(CFLAGS) $^ -o $(TARGET)

clean:
	@echo Cleaning...
	rm -f $(TARGET)
