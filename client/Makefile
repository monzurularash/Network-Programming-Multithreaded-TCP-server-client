CC=clang
CFLAGS=-g

all: tcpc

tcpc: tcpclient.c
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm -rf *.dSYM tcpc