CC:=gcc
caculate: main.o add.o minus.o divide.o multiply.o 
	$(CC) main.o add.o minus.o divide.o multiply.o -o caculate
main.o: main.c math.h
	$(CC) -c main.c
add.o: add.c math.h
	$(CC) -c add.c
minus.o: minus.c math.h
	$(CC) -c minus.c
divide.o: divide.c math.h
	$(CC) -c divide.c
multiply.o: multiply.c math.h
	$(CC) -c multiply.c
clean:
	rm caculate main.o add.o minus.o divide.o multiply.o 
