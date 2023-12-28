ifeq ($(CONFIG_ARCH_SUN),y)
dtbo-y += sun-kiwi-cnss.dtbo
dtbo-y += sun-kiwi-cnss-v8.dtbo
dtbo-y += sun-peach-cnss.dtbo
dtbo-y += sun-peach-cnss-v8.dtbo
endif

always-y	:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
