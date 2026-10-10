# Nombre del programa final
PROGRAMA := suma

# TODO 1: Definí el compilador a usar
#         Asigná el valor "gcc" a la variable CC
CC := gcc
CFLAGS := -Wall


all: $(PROGRAMA)

$(PROGRAMA): suma.c
	$(CC) $(CFLAGS) suma.c -o $(PROGRAMA)

clean:
	rm -f $(PROGRAMA)

.PHONY: all clean
