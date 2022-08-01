#HEADERS = program.h headers.h


CC= gcc
SOURCES= main.cpp
TARGET= srvMonitor2

default: all

all: clean compile install
	
compile:
	$(CC) -o $(TARGET) $(SOURCES)

install:
	cp $(TARGET) /usr/bin/

clean:
	-rm -f $(TARGET)

