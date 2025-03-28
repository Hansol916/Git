shop : main.c menu.o guest.o
	gcc -o shop main.c menu.o guest.o
menu.o : menu.c menu.h
	gcc -c menu.c -o menu.o
guest.o : guest.c guest.h
	gcc -c guest.c
clean:
	rm *.o shop

