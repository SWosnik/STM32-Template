TARGET = Demo.elf

TEMPLATEROOT = ..

BUILD_DIR=./build/

# compilation flags for gdb

CFLAGS  = -O1 -g
ASFLAGS = -g

# object files

vpath %.c ./src

OBJS=  $(STARTUP) $(BUILD_DIR)main.o

# include common make file

include $(TEMPLATEROOT)/Makefile.common


