CC = gcc
TARGET = ./bin/Sim
SRC = ./SRC/Sim.c

COMP_PATH    = $(shell pwd)/../Component
INC_FLAG = -I$(COMP_PATH)/include
LIB_PATH_FLAG = -L$(COMP_PATH)/lib
LIB_FLAG = $(COMP_PATH)/lib/Comp.so

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) -o $(TARGET) $(SRC) $(INC_FLAG) $(LIB_PATH_FLAG) $(LIB_FLAG)

clean:
	rm -f ./bin/*