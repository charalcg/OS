# Compiler and flags
CC = gcc
CFLAGS = -Wall -g

# Source files
SOURCES = example1.c example2.c example3.c example4.c example5.c

# Object files (add .o extension)
OBJECTS = example1.o example2.o example3.o example4.o example5.o

# Default target (compile and link everything separately)
all: example1 example2 example3 example4 example5

# Targets for each file to compile and link separately
example1: example1.c
	$(CC) $(CFLAGS) -o $@ $<

example2: example2.c
	$(CC) $(CFLAGS) -o $@ $<

example3: example3.c
	$(CC) $(CFLAGS) -o $@ $<

example4: example4.c
	$(CC) $(CFLAGS) -o $@ $<

example5: example5.c
	$(CC) $(CFLAGS) -o $@ $<

# Clean target to remove compiled files
clean:
	rm -f example1 example2 example3 example4 example5
