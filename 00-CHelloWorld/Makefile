CC = gcc
CFLAGS = -Wall -Wextra -Werror -std=c23 -g -pedantic
TARGET = programa
SRC = hello.c

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) $(SRC) -o $(TARGET)

# Una regla para ejecutarlo con la redirección que vimos antes
run: $(TARGET)
	./$(TARGET