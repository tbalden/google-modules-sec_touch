# SPDX-License-Identifier: GPL-2.0

ccflags-y += -I$(srctree)/../private/google-modules/display
ccflags-y += -I$(srctree)/../private/google-modules/display/samsung/include/uapi
ccflags-y += -I$(srctree)/../private/google-modules/touch/common
ccflags-y += -I$(srctree)/../private/google-modules/touch/common/include

obj-$(CONFIG_TOUCHSCREEN_SEC_TS)   += sec_touch.o
sec_touch-objs   += sec_ts.o sec_ts_fw.o sec_ts_fn.o sec_cmd.o \
	sec_ts_only_vendor.o
