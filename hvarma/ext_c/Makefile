all: gradient.so

gradient.so: gradient.o
	gcc -O2 -Wall -Werror -fpic gradient.c -o gradient.so -shared
	
clean:
	rm gradient.so gradient.o
