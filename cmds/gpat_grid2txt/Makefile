
PROG = gpat_grid2txt

LIBS = \
../../lib/SML/libsml.a \
../../lib/ezGDAL/libezgdal.a \
../../lib/tools/libtools.a \
../../lib/argtable/libargtable3.a

ifndef PREFIX
	PREFIX = /usr/local
endif

all: $(PROG)

$(PROG): main.o
	$(CC) -o $(PROG) main.o $(LIBS) $(CFLAGS) $(EXTFLAGS)

main.o: main.c ../../lib/argtable/argtable3.h
	$(CC) $(CFLAGS) $(EXTFLAGS) -c main.c

install: $(PROG)
	mv -f $(PROG) $(PREFIX)/bin

clean:
	rm -f $(PROG) *.o
