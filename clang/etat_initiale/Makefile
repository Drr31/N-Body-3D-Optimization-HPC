CC=clang

CFLAGS=-march=native -fopenmp

OFLAGS=-O0 -lomp

all: nbody3D

nbody3D: nbody.c
	$(CC) $(CFLAGS) $(OFLAGS) $< -o $@ -lm

clean:
	rm -Rf *~ nbody3D *.optrpt

