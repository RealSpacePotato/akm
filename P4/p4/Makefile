all: example1 example2 exploit

example1: example1.c
	gcc -fno-stack-protector -o example1 example1.c

example2: example2.c
	gcc -o example2 example2.c

exploit: exploit.txt
	xxd -r -p exploit.txt > exploit
