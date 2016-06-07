all: hello

hello: main.o wc.o map.o
	gcc -Wall main.o wc.o map.o -o hello

main.o: main.c
	gcc -c -Wall main.c

wc.o: wc.c
	gcc -c -Wall wc.c

map.o: map.c
	gcc -c -Wall map.c

clean:
	rm *o hello 

