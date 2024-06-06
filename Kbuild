ifeq ($(CONFIG_ARCH_SUN),y)
dtbo-y += sun-kiwi-cnss.dtbo
dtbo-y += sun-kiwi-cnss-v8.dtbo
dtbo-y += sun-peach-cnss.dtbo
dtbo-y += sun-peach-cnss-v8.dtbo
dtbo-y += sunp-hdk-peach-cnss-v8.dtbo
endif

ifeq ($(CONFIG_ARCH_PINEAPPLE),y)
dtbo-y += pineapple-kiwi-cnss.dtbo
dtbo-y += pineapplep-hdk-kiwi-cnss.dtbo
endif

ifeq ($(CONFIG_ARCH_X1E80100),y)
dtbo-y += x1e80100-kiwi-cnss.dtbo
endif

always-y	:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
