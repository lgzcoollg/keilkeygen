#gcc rand.c rdx36.c crypt.c mcid.c slicx.c main.c -static -o keilkeygen

# Compiler
CC = gcc

# Output executable name
TARGET = keilkeygen

# Default rule to build the target
all: 
	$(CC) *.c -static -o $(TARGET) 

# Clean rule to remove object files and executable
clean:
	rm -f $(TARGET)
