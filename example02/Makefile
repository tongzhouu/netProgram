all:lopen lread fds

lopen:low_open.c
	gcc -o lopen low_open.c

lread:low_read.c
	gcc -o lread low_read.c

fds:fd_seri.c
	gcc -o fds fd_seri.c

clean:
	rm -rf lopen lread fds
