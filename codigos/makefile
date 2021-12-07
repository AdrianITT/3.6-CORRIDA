disco:disco.o
	ld disco disco.o

disco.o:disco.s
	as -g -o disco.o disco.s
clean:
	rm disco disco.o
d:
	gdb disco
