SRC := $(wildcard *.bpf.c)

.PHONY: build
build: 
	ecc $(SRC)

.PHONY: run
run: 
	sudo ecli run package.json

.PHONY: clean
clean:
	@rm -rf *.o *.json
