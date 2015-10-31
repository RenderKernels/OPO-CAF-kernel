#
# Makefile for the Linux IrDA IrNET protocol layer.
#

obj-$(CONFIG_IRNET) += irnet.o

irnet-y := irnet_ppp.o irnet_irda.o
CFLAGS_KERNEL += -fstrict-aliasing
CFLAGS_KERNEL += -fno-strict-aliasing
