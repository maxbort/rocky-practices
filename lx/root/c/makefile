helloworld: helloworld.o UserHeader.o
	gcc -o helloworld helloworld.o UserHeader.o

helloworld.o: helloworld.c
	gcc -c helloworld.c


UserHeader.o: UserHeader.c
	gcc -c UserHeader.c

clean:
	rm -f hello *.o
