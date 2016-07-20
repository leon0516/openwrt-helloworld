# build a Makefile for hellowrold.c
# e.g. LIBS += -lcurl
LIBS +=
helloworld: helloworld.o   
	$(CC) $(LDFLAGS) helloworld.o -o helloworld $(LIBS)
helloworld.o: helloworld.c        
	$(CC) $(CFLAGS) -c helloworld.c
clean: 
	rm *.o helloworld

