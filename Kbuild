# SPDX-License-Identifier: GPL-2.0

obj-$(CONFIG_DVB_WETEKPLAY2) += wetekplay.o wetekdvb.o

wetekplay-objs = nimdetect.o \
                 mxl603.o \
                 avl6211.o \
                 mn88436.o \
                 cxd2837.o \
                 cxd2841er_wetek.o \
                 ascot3.o

wetekdvb-objs = wetek_dvb.o \
                wetek_dmx.o 

ccflags-y += -I$(KDIR)/drivers/media/dvb-core
ccflags-y += -I$(KDIR)/drivers/media/dvb-frontends
ccflags-y += -I$(KDIR)/drivers/media/tuners
