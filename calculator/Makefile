make: calculator 
clean:
	rm -f calculator *.o
calculator: addition.o division.o subtraction.o multiplication.o main.o
	cc -o calculator addition.o division.o subtraction.o multiplication.o main.o
addition.o division.o subtraction.o multiplication.o main.o: operations.h

.PHONY: make, clean
