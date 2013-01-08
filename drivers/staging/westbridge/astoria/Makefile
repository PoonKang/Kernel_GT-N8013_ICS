#
# Makefile for the kernel westbridge device drivers.
#

ifneq ($(CONFIG_WESTBRIDGE_DEBUG),y)
	EXTRA_CFLAGS		+= -WESTBRIDGE_NDEBUG
endif

ifeq ($(CONFIG_MACH_U1_NA_SPR),y)
else
obj-$(CONFIG_WESTBRIDGE)		+= block/
obj-$(CONFIG_WESTBRIDGE)		+= gadget/
endif

