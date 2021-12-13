SOURCES = proj2.c
CC   = gcc
CFLAGS =  -Wall -ansi -O3 -lm
TARGET = proj2

all: $(TARGET)

$(TARGET): $(SOURCES)
	$(CC) $(CFLAGS) $^ -o $(TARGET)

clean:
	@echo Cleaning...
	rm -f $(TARGET)
