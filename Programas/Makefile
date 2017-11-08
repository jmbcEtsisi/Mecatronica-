TARGET = eagle
#FLAVOR = release
FLAVOR = debug

#EXTRA_CCFLAGS += -u

ifndef PDIR # {
GEN_IMAGES= eagle.app.v6.out
GEN_BINS= eagle.app.v6.bin
SPECIAL_MKTARGETS=$(APP_MKTARGETS)
SUBDIRS=   \
        user
endif # } PDIR


APPDIR = .
LDDIR = ../ld

CCFLAGS += -Os

TARGET_LDFLAGS =              \
        -nostdlib \
	-Wl, -EL \
	--longcalls \
	--
