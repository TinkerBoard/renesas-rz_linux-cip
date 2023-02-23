# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the Renesas device drivers.
#

obj-$(CONFIG_SH_ETH) += sh_eth.o

ravb-objs := ravb_main.o ravb_ptp.o eth_mac_tinker.o

obj-$(CONFIG_RAVB) += ravb.o

ccflags-$(CONFIG_TINKER_V_ETH) += -DTINKER_V
