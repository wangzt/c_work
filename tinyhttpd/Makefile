all: httpd

httpd: httpd.c
	gcc -W -Wall -lsocket -o httpd httpd.c -lpthread

clean:
	rm httpd
