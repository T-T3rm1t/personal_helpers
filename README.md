Day3 of Compact-Seminar: Intro to Programming with C. Libraries & Linking. Aufgabe 8. Created and commited personal_helpers.h and personal_helpers.c.
Also added libpersonal_helpers.a and personal_helpers.o that are used for creating my own liblrary. They are should be stored in /usr/local/lib and /usr/local/include accordingly.
To use a liblrary call gcc <prog_name>.c -o <out_name>.elf -l personal_helpers.
makefile has 3 functions: build, install, clean.
build: executes gcc compiler
install: needs sudo rights to add my custom libraries to the folders /usr/local/lib and /usr/local/include respectfully,
clean: removes changes to the library.