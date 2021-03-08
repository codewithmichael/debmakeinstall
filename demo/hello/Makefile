CC = gcc
PREFIX ?= /usr/local

hello: hello.c
	$(CC) -o $@ $^

.PHONY: clean install

clean:
	@rm -f hello

install:
	@mkdir -p "$(PREFIX)/bin"
	@cp hello "$(PREFIX)/bin/"; \

