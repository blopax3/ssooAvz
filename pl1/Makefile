all: experimento_mem

experimento_mem: experimento_mem.o mem_dinamica.o
	gcc experimento_mem.o mem_dinamica.o -o experimento_mem -g -Wall

experimento_mem.o: experimento_mem.c mem_dinamica.h
	gcc -c experimento_mem.c -o experimento_mem.o -g -Wall

mem-dinamica.o: mem_dinamica.c mem_dinamica.h
	gcc -c mem_dinamica.c -o mem-dinamica.o -g -Wall

.PHONY: clean

clean:
	rm -f *.o
