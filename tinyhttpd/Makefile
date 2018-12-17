all: httpd

httpd: httpd.c
	gcc -g -W -Wall -lsocket -o httpd httpd.c -lpthread

clean:
	rm httpd
