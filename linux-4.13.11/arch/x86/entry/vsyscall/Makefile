#
# Makefile for the x86 low level vsyscall code
#
obj-y					:= vsyscall_gtod.o
ifdef CONFIG_X86_VSYSCALL_EMULATION
CFLAGS_vsyscall_64.o := -O1
endif
obj-$(CONFIG_X86_VSYSCALL_EMULATION)	+= vsyscall_64.o vsyscall_emu_64.o

