main:main.o
	gcc -E main.c -o main.i
	gcc -S main.i -o main.s
	gcc -c main.s -o main.o
	gcc main.o -o main
	
clean:
	rm -rf *.i *.s *.o main