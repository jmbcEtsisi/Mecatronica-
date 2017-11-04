ifndef PDIR
GEN_LIBS = libuser.a
endif

CC=gcc

LIB := -L /home/esp8266/Share/ESP8266/lib


INCLUDES := -I /home/esp8266/Share/ESP8266_NONOS_SDK-2.1.0/include/
INCLUDES := -I /home/esp8266/Share/ESP8266_NONOS_SDK-2.1.0/include/json
INCLUDES += -I ./
INCLUDES += -I ../../include/ets
PDIR := ../$(PDIR)
sinclude $(PDIR)Makefile

