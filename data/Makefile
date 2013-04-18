all:	data rservice xor

data:	data.c
	$(CROSS_COMPILE)gcc -s -O -o data data.c
rservice:	rservice.c
	$(CROSS_COMPILE)gcc -s -O -o rservice rservice.c
xor:	xor.c
	$(CROSS_COMPILE)gcc -s -O -o xor xor.c
clean:
	rm -f *.o data rservice xor
