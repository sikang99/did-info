#
# Makefile for id gen
#
PROG=sample01
usage:
	@echo "usage: make [edit|build|run]"

edit e:
	vi $(PROG).go

build b:
	go build -o $(PROG) $(PROG).go

run r:
	go run -race $(PROG).go

clean:
	rm -f $(PROG)

get:
	go get -u ./...

