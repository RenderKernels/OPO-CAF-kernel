#
# Makefile for the Linux Bluetooth CMTP layer
#

obj-$(CONFIG_BT_CMTP) += cmtp.o

cmtp-objs := core.o sock.o capi.o
CFLAGS_KERNEL += -fstrict-aliasing
CFLAGS_KERNEL += -fno-strict-aliasing
