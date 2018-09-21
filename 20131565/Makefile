testlib : main.o list.o hash.o bitmap.o
	gcc -W -o testlib main.o list.o hash.o bitmap.o
main.o : main.c
	gcc -W -c main.c
list.o : list.c list.h
	gcc -W -c list.c
hash.o : hash.c hash.h
	gcc -W -c hash.c
bitmap.o : bitmap.c bitmap.h
	gcc -W -c bitmap.c
clean:
	rm testlib main.o list.o hash.o bitmap.o