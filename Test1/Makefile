objs = main.o value.o
libs = -lm

main:${objs}
	gcc -o $@ ${objs} ${libs}
	
clean:
	rm -f main ${objs}

ezadd:
	git add .

ezcommit:
	git commit -m "test"

ezpush:
	git push origin master
