# Makefile.in for splat kernel module

MODULE := splat
EXTRA_CFLAGS = $(SPL_MODULE_CFLAGS)

# Solaris Porting LAyer Tests
obj-$(CONFIG_SPL) := $(MODULE).o

$(MODULE)-objs += splat-ctl.o
$(MODULE)-objs += splat-kmem.o
$(MODULE)-objs += splat-taskq.o
$(MODULE)-objs += splat-random.o
$(MODULE)-objs += splat-mutex.o
$(MODULE)-objs += splat-condvar.o
$(MODULE)-objs += splat-thread.o
$(MODULE)-objs += splat-rwlock.o
$(MODULE)-objs += splat-time.o
$(MODULE)-objs += splat-vnode.o
$(MODULE)-objs += splat-kobj.o
$(MODULE)-objs += splat-atomic.o
$(MODULE)-objs += splat-list.o
$(MODULE)-objs += splat-generic.o
$(MODULE)-objs += splat-cred.o
$(MODULE)-objs += splat-zlib.o
$(MODULE)-objs += splat-linux.o
