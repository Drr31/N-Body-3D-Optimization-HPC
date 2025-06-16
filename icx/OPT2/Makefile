CC=icx

CFLAGS=-xHost -g1

OFLAGS=-O2 -qopenmp

all: nbody3D

nbody3D: soaalligned_restrict.c
	$(CC) $(CFLAGS) $(OFLAGS) $< -o $@ -lm

clean:
	rm -Rf *~ nbody3D *.optrpt

