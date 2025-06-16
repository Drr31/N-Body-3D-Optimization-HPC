CC=icx

CFLAGS=-xHost -g1

OFLAGS=-O1 -qopenmp 

all: nbody3D

nbody3D: nbody.c
	$(CC) $(CFLAGS) $(OFLAGS) $< -o $@ -lm

clean:
	rm -Rf *~ nbody3D *.optrpt

