BINARY=bin/tbusmgr
TARGET= $(BINARY)
HOME=../
CINC=-I/usr/local/tlibc/include/ -Iinclude -I$(HOME)/tcommon/include -I$(HOME)/tcommon/tdr -I$(HOME)/tbus/include/
DEPOFILE=$(HOME)/tbus/lib/libtbus.a

CFILE=$(wildcard source/*.c)
DFILE=$(wildcard source/*.d)

include $(HOME)/build.mk

dep:
	@mkdir -p bin

install:
	mkdir -p $(PREFIX)
	cp -rf bin $(PREFIX)

