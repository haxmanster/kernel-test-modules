obj-m += hello.o

KDIR = /usr/src/debian_kernel-2.0.7
all:
	$(MAKE) -C $(KDIR) SUBDIRS=$(PWD) modules

clean:
	rm -rf *.o *.ko *.mod.* *.symvers *.order
