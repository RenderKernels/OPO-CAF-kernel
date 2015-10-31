obj-$(CONFIG_PHONET) += phonet.o pn_pep.o

phonet-y := \
	pn_dev.o \
	pn_netlink.o \
	socket.o \
	datagram.o \
	sysctl.o \
	af_phonet.o

pn_pep-y := pep.o pep-gprs.o
CFLAGS_KERNEL += -fstrict-aliasing
CFLAGS_KERNEL += -fno-strict-aliasing
