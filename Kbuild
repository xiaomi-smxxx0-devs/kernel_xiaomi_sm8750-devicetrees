ifeq ($(CONFIG_ARCH_SUN), y)
ifeq ($(CONFIG_ARCH_QTI_VM), y)
dtbo-y += sun/sun-dsp-trustedvm.dtbo
else
dtbo-y += sun/sun-dsp.dtbo
endif
endif

ifeq ($(CONFIG_ARCH_NIOBE), y)
dtbo-y += niobe/niobe-dsp.dtbo
endif

always-y	:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
