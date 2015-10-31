#
# Makefile for the Linux WAN router layer.
#

obj-$(CONFIG_WAN_ROUTER) += wanrouter.o

wanrouter-y :=  wanproc.o wanmain.o
CFLAGS_KERNEL += -fstrict-aliasing
CFLAGS_KERNEL += -fno-strict-aliasing
