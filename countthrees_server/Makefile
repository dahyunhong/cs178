
.PHONY :  test clean all

all : 
	+$(MAKE) -C src

clean : 
	rm -rf build

test : 
	mkdir build
	cp src/ServerCountThrees build/ServerCountThrees
	cp data/threesData.bin build/threesData.bin
	build/ServerCountThrees
