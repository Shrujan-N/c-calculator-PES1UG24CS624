CC = gcc
CFLAGS = -Wall -Isrc

# Default target: build the main program
all:
	$(CC) $(CFLAGS) src/calculator.c src/main.c -o calculator

# Target to compile and run tests
test:
	$(CC) $(CFLAGS) src/calculator.c tests/test_calculator.c -o test_runner
	./test_runner

# Target to clean up compiled files
clean:
	rm -f calculator test_runner