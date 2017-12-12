build:
	gcc -c file1.c
	gcc -c file2.c
	gnatmake -c my_main.adb
	gnatbind my_main.ali
	gnatlink my_main.ali file1.o file2.o

clean:
	rm *.o
	rm *.ali
	rm my_main
