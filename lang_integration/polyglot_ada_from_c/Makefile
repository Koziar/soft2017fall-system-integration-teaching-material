build:
	gcc -c main.c
	gnatmake -c unit1.adb
	gnatmake -c unit2.adb
	gnatbind -n unit1.ali unit2.ali
	gnatlink unit2.ali main.o -o main

clean:
	rm *.o
	rm *.ali
	rm main