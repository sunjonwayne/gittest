cc   = main.c value.c
objs = main.o value.o
libs = -lm

main:${objs}
	gcc -O ${cc} -c
	gcc -o $@ ${objs} ${libs}
	./main
	
clean:
	rm -f main ${objs}

ezadd:
	git add .
	git st

ezcommit:
	git commit -m "test"

ezpush:
	git push -u origin master
