include $(srctree)/drivers/misc/mediatek/Makefile.custom

#obj-$(CONFIG_ION_MTK) += ion_drv.o ion_mm_heap_old.o ion_sys_contig_heap.o
obj-$(CONFIG_ION_MTK) += ion_drv.o ion_mm_heap.o ion_fb_heap.o
ccflags-$(CONFIG_ION_MTK)  += -I$(srctree)/drivers/staging/android/ion #fro kernel-3.10 ion
ccflags-$(CONFIG_ION_MTK)  += -I$(srctree)/drivers/gpu/ion  #for kernrl-3.4 ion

ccflags-y += -DION_RUNTIME_DEBUGGER=0
