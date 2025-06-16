CC=clang

CFLAGS=-march=native -fopenmp

OFLAGS=-O2 -ffast-math -lm 

all: nbody3D

nbody3D: withoutpowparallel.c
	$(CC) $(CFLAGS) $(OFLAGS) $< -o $@ -lm

clean:
	rm -Rf *~ nbody3D *.optrpt

