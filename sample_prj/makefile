#ROOT_DIR:/home/willie/Blowfish_text
#include ./Makefile.parm

MY_OBJS = main.o

CFLAGS =-I ./MyLibary

LIBS =-L./MyLibary -lsample

default:all
all: my

my:     $(MY_OBJS)
	#$(CC) $(CFLAGS) -o $@ $^ $(LIBS) $(LDFLAGS) 
	$(CC) $(CFLAGS) -static -o $@ $^ $(LIBS) 

clean:
	@rm -vrf *.o test $(MY_OBJS)




